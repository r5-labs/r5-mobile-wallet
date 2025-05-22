# R5 Mobile Wallet

Open-source mobile wallet that allow you to save, spend, and receive R5 Coins on the R5 Network. Compatible with Android and iOS. Built using TypeScript and Capacitor.

## Installing

You can use `npm` to install the wallet before running it in your development environment:

```bash
npm install
```

## Running Development Environment

To start a development environment, you can use the `start` script with `npm`:

```bash
npm start
```

The local application will start at `localhost:3000` and you can use your browser's development tools to constrain the screen size according to the device you are developing to.

The baseline device used for the development of the wallet is the **iPhone SE** with a screen resolution of **375px by 667px**.

## Building

First, run the `build` script with `npm`:

```bash
npm run build
```

You may need to sync the mobile builds with Capacitor depending on the changes you have made to the codebase:

```bash
npx cap sync
```

To apply your changes to the iOS and Android pre-compiled code, run the `copy` command with Capacitor:

```bash
npx cap copy
```

Now you can use the `open` command with Capacitor to open either Android or iOS' IDEs to build your application:

```bash
npx cap open android
```

Or

```bash
npx cap open ios
```
> It's important to note that **you can only build the iOS version of the application on a macOS machine**. You can run Android Studio with the Android SDK to build the Android version on any device.
# Expo WalletConnect Demo

Without ejecting, we're able to connect an Expo app to MetaMask via WalletConnect.

<img src="./Demo.gif" width="250" />

Scan this QR code to try this on your phone or visit [Expo](https://expo.dev/@peterpme/WalletConnectExample)
![expo qr code](./expo-qrcode.png)

## What do these changes consist of?

- Polyfilling NodeJS' libraries within [metro.config.js](./metro.config.js)
- Creating and updating [global.ts](./global.ts)

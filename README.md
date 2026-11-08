# Apex Downloads

Apex is a calculator and everyday math toolbox for Windows, phones, and tablets. This repository contains the downloads and setup information only; it does not include the application source code.

## Downloads

- [Windows installer](https://github.com/wassimplyhere-ai/apex-downloads/raw/refs/heads/main/Apex-Setup.exe) — installs Apex for the current Windows account. The public build omits personal contact details.
- [Mobile and iPad package](https://github.com/wassimplyhere-ai/apex-downloads/raw/refs/heads/main/Apex-Mobile-PWA.zip) — a Progressive Web App package for hosting and adding to a device home screen.

## Mobile setup

The mobile ZIP is not a native Android APK or iPad IPA. Host the package at an HTTPS address, then open that address on the device. On iPhone or iPad, use Safari’s **Share → Add to Home Screen**. On Android, use Chrome’s **Install app** or **Add to Home screen** option. HTTPS is required for the service worker, offline cache, and update notices.

The app keeps calculation history and preferences locally on each device. Dictionary and search features need internet access.

## Windows setup

Run `Apex-Setup.exe` and follow the installer. It installs for the current Windows account and does not require administrator access.

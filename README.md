# Apex Downloads

Apex is a calculator and everyday math toolbox for Windows, phones, and tablets. This repository contains the downloads and setup information only; it does not include the application source code.

## Latest update · 1.1.2

The new **Math Lab** adds function graphs, linear and quadratic equation solving, interval root finding, numerical derivatives and integrals, data statistics with quartiles, and a trig bench with degree/radian controls. The formula notebook saves named formulas locally and supports JSON import/export. The Windows app also adds Aurora Glass and Monochrome Studio themes plus theme import/export.

This build improves numeric function parsing for names such as `log10(x)`, refreshes the mobile app shell, and keeps Windows theme export colors aligned with the preset you select. Graph, calculus, and interval-root outputs are numerical estimates. The general root finder searches for sign changes inside the interval you choose; it may not find repeated roots or roots outside that interval.

## Downloads

- **[Download Apex for Windows (64-bit)](https://raw.githubusercontent.com/wassimplyhere-ai/apex-downloads/main/Apex-Setup.exe)** — direct binary link with no GitHub file-page redirect. If that link doesn't start, open the [Windows file page](https://github.com/wassimplyhere-ai/apex-downloads/blob/main/Apex-Setup.exe) and click **Download raw file**. The installer omits personal contact details.
- [Mobile and iPad package](https://raw.githubusercontent.com/wassimplyhere-ai/apex-downloads/main/Apex-Mobile-PWA.zip) — a Progressive Web App package for hosting and adding to a device home screen.

## Mobile setup

The mobile ZIP is not a native Android APK or iPad IPA. It is a host-ready Progressive Web App package; host it at an HTTPS address, then open that address on the device. On iPhone or iPad, use Safari’s **Share → Add to Home Screen**. On Android, use Chrome’s **Install app** or **Add to Home screen** option. HTTPS is required for the service worker, offline cache, and update notices. The mobile app can apply an available update when it tells you one is ready, so you do not need to download the ZIP each time you open an installed copy.

The app keeps calculation history, formulas, and preferences locally on each device. Dictionary and search features need internet access. Math Lab expressions and data are calculated in the app and are not uploaded.

## Windows setup

Run `Apex-Setup.exe` and follow the installer. It installs for the current Windows account and does not require administrator access.

The installer can be run again over an existing installation to replace the app files with the current version. The app keeps saved history, formulas, and preferences in your Windows account.

## Verify a download

SHA-256 checksums:

- `Apex-Setup.exe`: `BB83C78A15AD109B0CE2986DC4111D17673036C1CF68CD66D92F9B72D8AE8383`
- `Apex-Mobile-PWA.zip`: `F3DEF2D5133537B8BF691CE0BF772AF3365E0E96C6A64D6F9FAC42E326DACE03`

## Contact and support

Questions, feedback, or ideas for Apex? Reach me on Discord at **simplysimpleealt**.

Enjoying Apex? If you’d like to support me while I keep improving it, optional contributions are appreciated. Using Apex and downloading it are free; support is never required.

- [Support me on PayPal](https://paypal.me/YeonIslonely) — paypal.me/YeonIslonely

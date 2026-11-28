# AUR1Xf

<p align="center">
  <img src="readme-res/banner.png" alt="AUR1Xf Banner"/>
</p>

<p align="center">
  <strong>Beyond the Ordinary.</strong>
</p>

<p align="center">
  <a href="https://github.com/salvogiangri/UN1CA/blob/sixteen/LICENSE">
    <img src="https://img.shields.io/github/license/salvogiangri/UN1CA?style=for-the-badge&logo=github" alt="License"/>
  </a>
  <a href="https://github.com/salvogiangri/UN1CA/commits/sixteen">
    <img src="https://img.shields.io/github/last-commit/salvogiangri/UN1CA/sixteen?style=for-the-badge" alt="Last Commit"/>
  </a>
  <a href="https://github.com/salvogiangri/UN1CA/stargazers">
    <img src="https://img.shields.io/github/stars/salvogiangri/UN1CA?style=for-the-badge" alt="Stars"/>
  </a>
  <a href="https://github.com/salvogiangri/UN1CA/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/salvogiangri/UN1CA/ci.yml?style=for-the-badge" alt="Build Status"/>
  </a>
  <a href="https://crowdin.com/project/UN1CA">
    <img src="https://img.shields.io/badge/Crowdin-263238?style=for-the-badge&logo=crowdin" alt="Crowdin"/>
  </a>
</p>

<p align="center">
  A premium, performance-focused One UI experience for Samsung Galaxy devices.
</p>

<p align="center">
  <a href="https://github.com/salvogiangri/UN1CA/discussions">Discussions</a>
  &bull;
  <a href="https://t.me/unicarom">Telegram</a>
</p>

---

## About AUR1Xf

**AUR1Xf** is an independent fork of [UN1CA](https://github.com/salvogiangri/UN1CA), built with the ambition of bringing an enhanced One UI experience to Samsung Galaxy devices.

Designed around the foundations of UN1CA, AUR1Xf aims to extend compatibility with **One UI 9**, adapting and evolving the original build system wherever possible.

Our vision is simple: deliver a refined, smooth, and feature-rich experience while maintaining the flexibility and customization that power users expect.

AUR1Xf builds upon the original UN1CA build system, which automates tool compilation, firmware acquisition and extraction, patch application, and the generation of flashable firmware packages.

### Open Source & Contributions

AUR1Xf is developed under the terms of the **GNU General Public License v3.0 (GPL-3.0)**.

Contributions, suggestions, bug reports, and feature requests are always welcome. If you encounter an issue involving attribution or licensing, please report it through our community channels or project contact.

---

## Features

### Core Features

- Based on the latest stable Galaxy S23 FE firmware
- EROFS-powered filesystem
- Galaxy S23 FE wallpapers and sounds
- Galaxy AI integration:
  - Audio Eraser
  - Browsing Assist
  - Call Assist
  - Drawing Assist
  - Interpreter
  - Note Assist
  - Now Brief
  - Photo Assist
  - Semantic Search
  - Transcript Assist
  - Writing Assist
- High-end system animations
- Native live blur support
- Always On Display (AOD) clock transitions
- Adaptive Color Tone support
- Adaptive refresh rate support
- Extra Brightness support
- Picture Remaster support
- Object, Shadow, and Reflection Eraser
- Image Clipper support
- Multi-user support
- Samsung DeX support*
- Camera privacy toggle
- Debloated system services and unnecessary applications
- Dual Messenger support for all applications
- Custom FlipFont support
- Outdoor Mode support
- Automatic PIN confirmation (4 digits)
- [BluetoothLibraryPatcher](https://github.com/3arthur6/BluetoothLibraryPatcher) integration
- [KnoxPatch](https://github.com/salvogiangri/KnoxPatch) integration
- Additional CSC features:
  - Native call recording
  - Hiya integration
  - Network speed indicator in the status bar
  - AltZLife

*Samsung DeX over HDMI is unavailable on devices without USB-C DisplayPort support.*

### AUR1Xf Exclusive Features

- Integrated OTA Updates application
- Native live blur toggle
- One UI Home animation options
- Vulkan renderer toggle
- Key attestation spoofing options via [TrickyStore](https://github.com/5ec1cff/TrickyStore)*
- Integrated Play Integrity Fix
- Application hiding support via [Hide My Applist](https://github.com/Dr-TSNG/Hide-My-Applist)
- Ability to hide Developer Options
- Application downgrade permission toggle
- Installation support for applications targeting older SDK versions
- Secure screenshot permission toggle
- Screenshot and screen recording detection toggle
- Unlimited Google Photos backup storage
- Game FPS unlock toggle

*Requires a valid keybox. Availability and functionality depend on the device and configuration.*

---

## Build System

AUR1Xf inherits the automated build infrastructure from UN1CA.

The build system handles:

1. Building the required tools and dependencies.
2. Downloading and extracting firmware components.
3. Applying device-specific patches and modifications.
4. Integrating additional features and optimizations.
5. Generating a flashable firmware package.

---

## Licensing

AUR1Xf is licensed under the [GNU General Public License v3.0](LICENSE).

Some external dependencies are distributed under their own respective licenses:

| Dependency | License |
|---|---|
| [android-tools](https://github.com/nmeum/android-tools) | Apache License 2.0 |
| [apktool](https://github.com/iBotPeaches/Apktool) | Apache License 2.0 |
| [erofs-utils](https://github.com/sekaiacg/erofs-utils/) | GPL-2.0 / Apache-2.0 |
| [img2sdat](https://github.com/xpirt/img2sdat) | MIT License |
| [platform_build](https://android.googlesource.com/platform/build/) | Apache License 2.0 |

Please refer to the respective upstream repositories for complete licensing information.

---

## Contributors

<p align="center">
  <a href="https://github.com/salvogiangri/UN1CA/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=salvogiangri/UN1CA" alt="UN1CA Contributors"/>
  </a>
</p>

## Credits & Acknowledgements

AUR1Xf would not be possible without the work, contributions, and support of the developers and communities behind its foundations.

Special thanks to:

- **[ShaDisNX255](https://github.com/ShaDisNX255)** — For the help, time, and inspiration from [NcX ROM](https://github.com/ShaDisNX255/NcX_Stock).
- **[DavidArsene](https://github.com/DavidArsene)** — For the help and continued support.
- **[paulowesll](https://github.com/paulowesll)** — For the help and support.
- **[Simon1511](https://github.com/Simon1511)** — For the support and device-specific patches.
- **[ananjaser1211](https://github.com/ananjaser1211)** — For troubleshooting assistance and time.
- **[Fede2782](https://github.com/Fede2782)** — For contributions and assistance with Exynos/MTK support.
- **[iDrinkCoffee](https://github.com/iDrinkCoffee-TG)** and **[RisenID](https://github.com/RisenID)** — For their continued support.
- **[LineageOS Team](https://www.lineageos.org/)** — For the original [OTA updater implementation](https://github.com/LineageOS/android_packages_apps_Updater).

Thanks to all UN1CA forks, contributors, developers, testers, and users.

<p align="center">
  <strong>AUR1Xf</strong>
  <br/>
  <em>Beyond the Ordinary.</em>
</p>

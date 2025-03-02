# BewlyBewly! Ave Mujica

English | [官话 - 简体中文](README-cmn_CN.md) | [官話 - 繁體中文](README-cmn_TW.md) | [廣東話](README-jyut.md)

<p align="center" style="margin-bottom: 0px !important;">
<img width="300" alt="BewlyBewly icon" src="https://cdn.jsdelivr.net/gh/BewlyBewly/Imgs/logos/bewlybewly-vtuber-logo.png"><br/>
</p>

<p align="center">Just make a few small changes to your bilibili homepage.</p>

<!-- ![min1](https://github.com/hakadao/BewlyBewly/assets/33394391/951f9e2a-d0e1-452c-83a9-dc6d85c4d441)
![min2](https://github.com/hakadao/BewlyBewly/assets/33394391/3e75dd20-f60b-4645-b434-23a24c72959c) -->

## 👋 Introduction

> [!IMPORTANT]
> BewlyBewly! Ave Mujica mainly focuses on page adjustments and optimization rather than improving functionally and efficiency.
>
> The dark mode will only be adapted to commonly used pages due to its efficiency and maintenance difficulty, while less
> frequently used pages will not to be adapted.

> [!IMPORTANT]
> BewlyBewly! Ave Mujica is a fork of [BewlyBewly](https://github.com/BewlyBewly/BewlyBewly), aiming to provide feature updates and bug fixes after the original project was archived.

> [!CAUTION]
> If you are installing this extension, your browser will probably say that it can read your browser history.
>
> This is because BewlyBewly! Ave Mujica uses the ["tabs" permission](https://developer.chrome.com/docs/extensions/reference/api/tabs), which can also be used to read each tab, allowing it to know the browsing history, but it is not utilized here.
>
> **Some browsers will mention the worst-case scenario and the highest risks, ensuring your safety after installation.**
> Additionally, this project is open source, so you can see what exactly what it does.

BewlyBewly is a browser extension for bilibili that aims to enhance the user experience by redesigning the bilibili UI.
The design is inspired by YouTube, Vision OS, and iOS, resulting in a more visually appealing and user-friendly interface.
This project uses the [vitesse-webext](https://github.com/antfu/vitesse-webext) template for development.
Without this template, it may not be possible to develop this project.

## ⬇️ Installation

- (based on) Firefox browsers: https://addons.mozilla.org/en-CA/firefox/addon/bewlybewly-avemujica/
- (based on) Chromium browsers:

## 🤝 Contribution & Build

1. Clone the repository
```sh
git clone https://github.com/VentusUta/BewlyBewly-AveMujica
```

2. Install dependencies (please make sure you already installed pnpm!)
```sh
cd BewlyBewly-AveMujica
pnpm install
```

3. Build
  - For Chromium-based browsers
```sh
pnpm run build
```
  - For Firefox-based browsers
```sh
pnpm run build-firefox
```

4. Pack (optional, please make sure you already build for Chromium!)
```sh
pnpm run pack
```

## ❤️ Credits

- [vitesse-webext](https://github.com/antfu/vitesse-webext) - The template used for this project
- [UserScripts/bilibiliHome](https://github.com/indefined/UserScripts/tree/master/bilibiliHome), [bilibili-app-recommend](https://github.com/magicdawn/bilibili-app-recommend) - Reference source for obtaining the access key
- [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved) - Partial implementation of functionalities
- [bilibili-API-collect](https://github.com/SocialSisterYi/bilibili-API-collect)

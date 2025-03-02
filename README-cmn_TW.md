# BewlyBewly! Ave Mujica

[English](README.md) | [官话 - 简体中文](README-cmn_CN.md) | 官話 - 繁體中文 | [廣東話](README-jyut.md)

<p align="center" style="margin-bottom: 0px !important;">
<img width="300" alt="BewlyBewly icon" src="https://cdn.jsdelivr.net/gh/BewlyBewly/Imgs/logos/bewlybewly-vtuber-logo.png"><br/>
</p>

<p align="center">對您的 bilibili 頁面進行一些小改動。</p>

<!-- ![min1](https://github.com/hakadao/BewlyBewly/assets/33394391/951f9e2a-d0e1-452c-83a9-dc6d85c4d441)
![min2](https://github.com/hakadao/BewlyBewly/assets/33394391/3e75dd20-f60b-4645-b434-23a24c72959c) -->

## 👋 介紹

> [!IMPORTANT]
> BewlyBewly! Ave Mujica 主要著重於頁面調整和改良，而不是完善功能和提升效率。
>
> 由於考慮到效率和維護困難度，深色模式只會適應常用的頁面，而較少使用的頁面則不會支護。

> [!IMPORTANT]
> BewlyBewly! Ave Mujica 是 [BewlyBewly](https://github.com/BewlyBewly/BewlyBewly) 的一個 fork（分叉），目的是在原專案封存後提供其他更新和錯誤修復。

> [!CAUTION]
> 如果您正在安裝此擴充功能，您的瀏覽器可能會提示它可以讀取您的瀏覽歷史記錄。
>
> 這是因爲 BewlyBewly! Ave Mujica 使用了["tabs" 權限](https://developer.chrome.com/docs/extensions/reference/api/tabs)，該權限也可用於讀取每個分頁，從而瞭解瀏覽歷史，但在這裏並未使用。
>
> **一些瀏覽器會提到最壞的情況和最高的風險，以確保您在安裝後的安全。**
> 此外，這個專案是開源的，所以您可以看到它究竟做了什麼。

BewlyBewly! Ave Mujica 是一個針對 bilibili 的瀏覽器擴充功能，旨在透過重新設計 bilibili 的介面來提升用戶體驗。設計靈感來自於 YouTube、Vision OS 和 iOS，使介面更具視覺吸引力和用戶友好性。

該專案使用 [vitesse-webext](https://github.com/antfu/vitesse-webext) 範例進行開發。如果沒有此範例，可能無法開發出此專案。

## ⬇️ 安裝

- Firefox 系瀏覽器：https://addons.mozilla.org/en-CA/firefox/addon/bewlybewly-avemujica/
- Chromium 系瀏覽器：

## 🤝 貢獻與建置專案

1. 克隆儲存庫
```sh
git clone https://github.com/VentusUta/BewlyBewly-AveMujica
```

2. 安裝依賴（確保您已安裝 pnpm！）
```sh
cd BewlyBewly-AveMujica
pnpm install
```

3. 建構
  - 基於 Chromium 的瀏覽器
```sh
pnpm run build
```
  - 基於 Firefox 的瀏覽器
```sh
pnpm run build-firefox
```

4. 打包（可選，確保您已建構 Chromium 的擴充功能！）
```sh
pnpm run pack
```

## ❤️ 鳴謝

- [vitesse-webext](https://github.com/antfu/vitesse-webext)——此專案所用的範例
- [UserScripts/bilibiliHome](https://github.com/indefined/UserScripts/tree/master/bilibiliHome)、[bilibili-app-recommend](https://github.com/magicdawn/bilibili-app-recommend)——參考取得 access key 之方法
- [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)——部分功能的實現
- [bilibili-API-collect](https://github.com/SocialSisterYi/bilibili-API-collect)

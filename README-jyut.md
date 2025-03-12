# BewlyBewly! Ave Mujica

[English](README.md) | [官话 - 简体中文](README-cmn_CN.md) | [官話 - 繁體中文](README-cmn_TW.md) | 廣東話

<p align="center" style="margin-bottom: 0px !important;">
<img width="300" alt="BewlyBewly icon" src="https://cdn.jsdelivr.net/gh/BewlyBewly/Imgs/logos/bewlybewly-vtuber-logo.png"><br/>
</p>

<p align="center">係咁以執吓你嘅 bilibili 頁面。</p>

<!-- ![min1](https://github.com/hakadao/BewlyBewly/assets/33394391/951f9e2a-d0e1-452c-83a9-dc6d85c4d441)
![min2](https://github.com/hakadao/BewlyBewly/assets/33394391/3e75dd20-f60b-4645-b434-23a24c72959c) -->

## 👋 介紹

> [!IMPORTANT]
> BewlyBewly! Ave Mujica 主要着重頁面調整同埋改善，而唔係完善功能同提升效率
>
> 事關考慮到維護嘅效率同埋難度，深色模式淨係會適應常用頁面，一啲冇咁常用嘅頁面唔會適應調整

> [!IMPORTANT]
> BewlyBewly! Ave Mujica 係 [BewlyBewly](https://github.com/BewlyBewly/BewlyBewly) 嘅一個 fork（分叉），目的係原專案封存之後提供其他更新同埋錯誤修復。

> [!CAUTION]
> 如果你單緊呢個延伸功能，你嘅瀏覽器可能會話佢可以睇到你嘅瀏覽紀錄。
>
> 呢個係因爲 BewlyBewly! Ave Mujica 用咗["tabs" 權限](https://developer.chrome.com/docs/extensions/reference/api/tabs)，呢個權限亦都可以用嚟讀取每個分頁，從而知道瀏覽紀錄，但係喺呢度冇用到。
>
> **有啲瀏覽器會同你講最壞嘅情況係點同最高嘅風險，確保你單咗之後嘅安全。**
> 另外，呢個項目係開源嘅，所以你可以睇到佢究竟做緊乜。

BewlyBewly! Ave Mujica 係一個用於 bilibili 嘅瀏覽器延伸功能，目的係透過重新設計 bilibili 嘅 UI 令到用戶體驗提升。設計靈感源於 YouTube、Vision OS 同 iOS，從而實現更具視覺吸引力同用戶友好嘅介面。

呢個專案係用咗 [vitesse-webext](https://github.com/antfu/vitesse-webext) 範例進行開發。若果冇咗呢個範例，BewlyBewly 得個吉。

## ⬇️ 單撈

- Firefox 系瀏覽器：https://addons.mozilla.org/en-CA/firefox/addon/bewlybewly-avemujica/
- Chromium 系瀏覽器：https://chromewebstore.google.com/detail/bewlybewly-ave-mujica/lildghglkgcoanblbmenbefhnhifghjj

## 🤝 貢獻同建置專案

1. 克隆儲存庫
```sh
git clone https://github.com/VentusUta/BewlyBewly-AveMujica
```

2. 裝依賴（要確定你已經裝咗 pnpm 㗎！）
```sh
cd BewlyBewly-AveMujica
pnpm install
```

3. 建構
  - 基於 Chromium 嘅瀏覽器
```sh
pnpm run build
```
  - 基於 Firefox 嘅瀏覽器
```sh
pnpm run build-firefox
```

4. 打包（可以唔使嘅，最緊要你整好咗 Chromium 嘅擴充功能先！）
```sh
pnpm run pack
```

## ❤️ 鳴謝

- [vitesse-webext](https://github.com/antfu/vitesse-webext)——專案所用嘅範例
- [UserScripts/bilibiliHome](https://github.com/indefined/UserScripts/tree/master/bilibiliHome)、[bilibili-app-recommend](https://github.com/magicdawn/bilibili-app-recommend)——參考取得 access key 之方法
- [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)——部分功能嘅實現
- [bilibili-API-collect](https://github.com/SocialSisterYi/bilibili-API-collect)

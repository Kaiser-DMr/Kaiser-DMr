<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
    <img src="./assets/hero-light.svg" width="100%" alt="Kaiser-DMr — Embedded systems · iOS apps · Web tooling">
  </picture>
</div>

<div align="center">
  <a href="https://github.com/Kaiser-DMr?tab=followers">
    <img alt="followers" src="https://img.shields.io/github/followers/Kaiser-DMr?style=flat-square&labelColor=0B0D10&color=FF4D4D&logo=github&logoColor=white">
  </a>
  <img alt="visitors" src="https://komarev.com/ghpvc/?username=Kaiser-DMr&label=VISITORS&color=FF4D4D&style=flat-square">
  <img alt="focus" src="https://img.shields.io/badge/FOCUS-ESP32%20%C2%B7%20CAN%20%C2%B7%20SwiftUI%20%C2%B7%20WEB-0B0D10?style=flat-square&labelColor=0B0D10">
</div>

<br>

## 关于 / About

写完整链路的人：**固件 → 网页仪表盘 → 原生 App**。

2019 年注册账号，从 Vue 后台管理页面写起；2022 年一个 3D 心跳页面意外被 fork 了 180 多次；
现在主要在折腾 **P4-CAN** 这条线 —— 跑在 ESP32-P4 上的三路 CAN 工具固件、板子自带的网页仪表盘，
以及装进 iPhone / Mac 的原生控制台。

习惯把「能不能用」放在「写得优雅」前面：能一条命令还原的改动，就不做不可逆的魔改；
能回读校验的写入，就不假设它成功了。

<br>

## 现在在做什么 / Now

- 🛠 &nbsp;**P4 管家 3.44** — SwiftUI 重写的 iOS / iPadOS / macOS 控制台，把状态、灯光、诊断做成可视化面板，写入后回读校验。
- 🌏 &nbsp;**P4-CAN 汉化壳** — 注入式中文化，不动固件一行逻辑；外加一层原生 iOS 外壳，刷原厂英文固件也有中文界面。
- 📊 &nbsp;**TikTok 广告批量搭建后台** — Next.js + Marketing API 的投放作业台（私有项目）。

> 车载相关项目与 Tesla, Inc. 无任何关联。CAN 写入有风险，请仅在驻车或封闭场地、并遵守当地法律法规的前提下使用。

<br>

## 精选项目 / Featured

| 项目 | 说明 |
| :-- | :-- |
| **[P4 管家 · P4-CAN Companion](https://github.com/Kaiser-DMr/p4can-companion)**<br><sub>`SwiftUI` `ESP32-P4` `iOS 17+` `macOS 14+`</sub> | 原生 iOS / iPadOS / macOS 控制台。所有状态直接来自设备 HTTP API，不是网页套壳；写入后回读校验。ad-hoc IPA 需自行签名。 |
| **[P4-CAN 中英双语汉化](https://github.com/Kaiser-DMr/p4can-zh-ios)**<br><sub>`JavaScript` `WKWebView` `Sideload`</sub> | 给 P4-CAN 网页仪表盘做的注入式汉化 + 原生 iOS 外壳。不改固件逻辑，一条命令即可还原英文；未连设备时可进「界面预览」。 |
| **[3D 心跳 · -3D](https://github.com/Kaiser-DMr/-3D)**<br><sub>`JavaScript` `CSS 3D`</sub> | 纯前端的 3D 爱心跳动页面，2022 年的意外小爆款（200+ ★ / 180+ fork），至今仍有人拿去做表白页。 |
| **[广告后台 · ads--admin-code](https://github.com/Kaiser-DMr/ads--admin-code)**<br><sub>`JavaScript` `Vue`</sub> | 广告投放后台的全代码实现，早期前端工程化的练习沉淀。 |

<br>

## 技术栈 / Stack

<div align="center">

`嵌入式`&nbsp;
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![CAN](https://img.shields.io/badge/TWAI%20%2F%20CAN-0B0D10?style=flat-square)

`Apple`&nbsp;
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-1C8AC9?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat-square&logo=apple&logoColor=white)

`Web`&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

`工具`&nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

<br>

## 数据 / Stats

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Kaiser-DMr&show_icons=true&hide_border=true&rank_icon=github&bg_color=0B0D10&title_color=FF6B6B&icon_color=FF4D4D&text_color=C9D1D9&card_width=420">
    <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Kaiser-DMr&show_icons=true&hide_border=true&rank_icon=github&bg_color=FFFFFF&title_color=C4352C&icon_color=D93A32&text_color=33404E&card_width=420">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Kaiser-DMr&layout=compact&langs_count=8&hide_border=true&bg_color=0B0D10&title_color=FF6B6B&text_color=C9D1D9&card_width=380">
    <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kaiser-DMr&layout=compact&langs_count=8&hide_border=true&bg_color=FFFFFF&title_color=C4352C&text_color=33404E&card_width=380">
  </picture>
</div>

<br>

<div align="center">
  <sub>暂居地球 🌍 · 随时上线</sub>
</div>

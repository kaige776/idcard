# 高清身份证图片在线生成器 | ID Card Image Generator

> Fork of [faketrump2028/idcard](https://github.com/faketrump2028/idcard), with bug fixes and documentation improvements.

在线身份证高清图片生成器，支持手动输入或一键自动生成，免费使用。

An online high-definition ID card image generator. Supports manual input or one-click random generation. Free to use.

## ✨ 功能特性 | Features

- **① 一键随机生成身份证信息** — 行政地区编码划分根据国家统计局 2025 年数据
- **② 自动匹配性别照片** — 根据身份证号码第 17 位（奇数男、偶数女）自动提供照片
- **③ 纯前端部署** — 基于 Preact + Vite 构建，无需后端服务

> ⚠️ 因图片、字体资源较大，初次下载需约 10 秒。
>
> Due to large image and font resources, the initial download takes about 10 seconds.

## 🚀 在线访问 | Live Demo

| 平台 | 链接 |
| --- | --- |
| GitHub Pages | <https://kaige776.github.io/idcard/> |
| 原项目 (Upstream) | <https://idimg.pages.dev/> |

## 🛠️ 技术栈 | Tech Stack

- [Preact](https://preactjs.com/) — 轻量级 React 替代方案
- [Vite](https://vitejs.dev/) — 下一代前端构建工具
- 纯静态部署，支持 GitHub Pages / Cloudflare Pages 等任意静态托管

## 📖 使用说明 | Usage

1. 打开在线页面
2. 点击「随机生成」按钮一键生成身份证信息，或手动输入各项内容
3. 生成的高清身份证图片可直接保存

## 📦 本地部署 | Local Deployment

```bash
# 克隆仓库
git clone https://github.com/kaige776/idcard.git
cd idcard

# 使用任意静态服务器部署，例如：
npx serve .
# 或
python3 -m http.server 8080
```

> **注意：** 本仓库仅包含构建后的静态文件（`index.html` + `assets/`），不包含源代码。
> 如需源代码，请访问上游仓库 [faketrump2028/idcard](https://github.com/faketrump2028/idcard)。

## ⚖️ 免责声明 | Disclaimer

> **本项目仅用于软件开发相关功能测试使用，请勿用于任何非法用途，且自行承担后果和责任。**
>
> This project is for software development testing purposes only. Do not use it for any illegal purposes. Users are responsible for their own actions and consequences.

## 📄 License

本项目为 fork 仓库，版权归上游项目 [faketrump2028/idcard](https://github.com/faketrump2028/idcard) 所有。请遵守上游项目的许可协议。

# Internal Beyond（IB）

**边界之外** — 离线运行的单文件个人网站项目

自定义世界观设定/多模组互动玩法/像素游戏房间/支持多端口API

支持所有个人数据的永久化保留，完全支持自定义功能、离线保存与读取。

希望大家喜欢。

---

## ✦ 简介

Internal Beyond 是一个完全离线的单文件个人数字空间。无需安装，无需注册，下载即用。

接入你自己的 AI API 密钥后，可解锁全部互动功能。支持 Claude、GPT、DeepSeek、Gemini 等主流 AI 模型。

快捷游玩：https://sui-ib.github.io/InternalBeyond/

## ✦ 功能

| 模块 | 说明 |
|------|------|
| **Blog** | 个人日志 / 密码日记本 |
| **Chat** | 多端口 AI 对话（支持群聊） |
| **Letters** | AI 书信系统 |
| **Sui's Room** | 像素风格互动房间 |
| ↳ Tea | 茶话会 — 25 种饮品×甜品氛围组合 |
| ↳ Tarot | 78 张塔罗牌占卜 + AI 解读 |
| ↳ Story | AI 驱动的互动文字冒险 + 自定义剧本 |
| ↳ Wardrobe | 6 套服装换装系统 |
| **DIY** | 自定义立绘、背景、塔罗布 |
| **Profile** | 个人资料页 |
| **Guide** | 使用说明 + 创作者手记 |

## ✦ 快速开始

1. 下载本仓库（点击上方绿色 **Code** → **Download ZIP**）
2. 解压后，用浏览器打开 `InternalBeyond.html`
3. 进入 **API Settings** 页面，添加你的 AI API 密钥
4. 开始使用

**无需联网也能使用基础功能**（日志、换装、主题切换等）。AI 相关功能需要联网调用 API。

## ✦ API 配置指南

IB 支持多种 AI 服务接入方式。选择适合你的：

### 官方 API（海外用户 / 有条件的国内用户）

| 服务商 | 注册地址 | IB 中选择 | 密钥格式 |
|--------|---------|-----------|---------|
| Anthropic (Claude) | console.anthropic.com | `Claude (Anthropic)` | sk-ant-… |
| OpenAI (GPT) | platform.openai.com | `GPT (OpenAI)` | sk-… |
| DeepSeek | platform.deepseek.com | `DeepSeek` | sk-… |
| Google (Gemini) | aistudio.google.com | `Gemini (Google)` | AIza… |

选好服务商后，接口地址和默认模型会自动填入，你只需粘贴 API Key 即可。

### 中转站 API（国内用户推荐）

如果你无法直接访问海外 API（没有海外信用卡、网络受限等），可以使用中转站：

1. 在你的中转站注册并充值
2. 获取中转站提供的：**API Key**、**接口地址**（Endpoint）、**可用模型名**
3. 在 IB 的 API 设置中：
   - **服务商**选 **`自定义`**
   - **接口地址**填中转站给你的地址（如 `https://api.example.com/v1/chat/completions`）
   - **API Key** 填中转站给你的密钥
   - **模型**填你要使用的模型全名
4. 保存即可

## ✦ 设备兼容性

任何有现代浏览器的设备均可使用：

- ✅ Windows / macOS / Linux 电脑
- ✅ iPhone / iPad（Safari）
- ✅ Android 手机和平板
- ✅ 华为平板 / HarmonyOS 设备
- ✅ 任何支持 HTML5 的浏览器

## ✦ 项目结构

```
InternalBeyond.html    ← 主文件（用浏览器打开这个）
game/
  game_module.js       ← 像素房间引擎
  *.png                ← 精灵图和场景素材
```

## ✦ 数据安全

- 所有数据存储在浏览器本地（IndexedDB），不上传到任何服务器
- API 密钥仅存储在你的浏览器中，仅用于直接调用对应 AI 服务
- 支持完整的数据导入/导出功能

## ✦ 关于世界观玩家

如果你习惯使用自定义世界观（类似 SillyTavern 的世界书），可以在 API Settings 中设置 System Prompt。你的自定义 prompt 会自动注入到所有 AI 功能中（Chat、Tea、Tarot、Story、Letter），无需重复配置。

---

## ✦ Introduction (EN)

**Internal Beyond** is a fully offline, single-file personal digital sanctuary. No installation, no registration — just download and open.

Connect your own AI API keys to unlock all interactive features. Supports Claude, GPT, DeepSeek, Gemini, and other major AI models.

### Features
- **Blog** — Personal journal with encrypted diary
- **Chat** — Multi-API AI conversations (with group chat)
- **Letters** — Asynchronous AI correspondence
- **Sui's Room** — Pixel-art interactive room with Tea Party (25 drink×dessert combos), Tarot (78-card deck + AI reading), Interactive Story (AI game master), and Wardrobe (6 outfits)
- **DIY** — Customize character portraits, backgrounds, and tarot cloth
- **Dual Theme** — Internal (light) / Infernal (dark) with crossfade transition

### Quick Start
1. Download this repository
2. Open `InternalBeyond.html` in your browser
3. Add your AI API key in API Settings
4. Start exploring

---

## 📦 下载说明

**InternalBeyond_single.html** — 单文件离线版，所有图片和代码已内嵌。
直接用手机/电脑浏览器打开即可，无需解压和保持文件夹结构。

适用于 iOS Safari、Android、Windows、macOS 等任何设备。

## ✦ 联系方式

- QQ：1282901880
- 小红书 ：3628686381
- Email：1282901880@qq.com

## ✦ 版权声明

© 2025-2026 Sui. All rights reserved.

本项目为个人创作作品，代码和设计均为原创。欢迎下载使用，但请勿用于商业用途或二次贩卖。

所有角色精灵图、场景素材由 Sui 设计制作或授权使用。

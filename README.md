# Cyber ANIME Record Terminal // 赛博风格番剧记录终端

> 
> **A Retro Cyberpunk, Todo-list style anime tracker.**
> 
> **一个复古赛博风格、类 Todo-list 的番剧备忘录。**
<img width="1652" height="1044" alt="image" src="https://github.com/user-attachments/assets/76eb3ebf-3ed1-4ea9-9239-09e79038aa1e" />


## 📖 Introduction // 简介

**Cyber Anime Record Terminal** is a single-page application designed for anime enthusiasts who love **Terminal style** aesthetics. Unlike traditional heavy databases, this is a lightweight, **Todo-list style anime tracker** that lives in your browser.

With **Retro Cyberpunk style** visuals, including parallax deep-space backgrounds, glitch effects, and maglev card interactions.

**赛博风格番剧记录终端**是一个为喜爱**终端风格**的追番者设计的单页应用。与传统臃肿的数据库不同，这是一个轻量级的、**类 Todo-list 的番剧备忘录**，直接运行在你的浏览器中。

它拥有极致的**复古赛博风格**视觉效果，包含视差深空背景、故障艺术文字和磁悬浮卡片交互。

## ✨ Features // 功能特性

### 🎨 Visuals & Immersion // 视觉与沉浸感

- **Retro Cyberpunk Style**: Neon glow, dot-matrix fonts (VT323), and glitch art headers.

    - **复古赛博风格**：霓虹辉光、点阵字体和故障特效标题。
- **Dynamic Parallax**: A deep-space background that moves inversely to your mouse cursor.

    - **动态视差**：随鼠标反向移动的深空背景系统。
- **Maglev Cards**: List items float and glow upon hovering, simulating a 3D interface.

    - **磁悬浮卡片**：列表项在悬停时会浮起并发出辉光，模拟 3D 界面。

### 🛠️ Functionality // 核心功能

- **Todo-list Workflow**: Manage anime status easily: `WAITING` (Todo), `SYNCING` (Doing), and `COMPLETE` (Done).

    - **类 Todo-list 管理**：轻松管理番剧状态：`WAITING`（未看）、`SYNCING`（在看）、`COMPLETE`（看完）。
- **Convenient Operations**: Support for batch selection, batch deletion, and Undo/Redo operation.

    - **便捷操作**：支持批量选择、批量删除以及撤销/重做操作。
- **Serverless Sync**: No backend required. Data is stored locally and can be synchronized across devices using an **Raw Stream** *ANIME SYNC CODE*.

    - **无服务器同步**：无需后端。数据本地存储，并可通过**纯文本流**的“*番剧同步码*”在不同设备间一键同步。
- **Smart Sync**: Intelligent merging algorithm that updates existing records and injects new ones during import, ensuring no data loss or overwrite.

    - **智能同步**：导入数据时采用非破坏性合并算法。系统会自动更新现有记录并注入新条目，不会暴力覆盖，确保本地数据的完整性。

## 🚀 Deployment // 部署与使用

This project is a **Single File Application**. You don't need a server to run it.

本项目是一个**单文件应用**，无需服务器即可运行。

### Method 1: GitHub Pages (Recommended // 推荐)

1. Fork this repository.
2. Go to `Settings` -&gt; `Pages`.
3. Select `main` branch and save.
4. Your personal deck is now online!

    - *Fork 本仓库 -&gt; 设置 -&gt; Pages -&gt; 选择 main 分支保存 -&gt; 你的专属终端上线了！*

### Method 2: Local / Mobile (本地/手机)

1. Download the `index.html` file.
2. **PC**: Open directly with Chrome/Edge.
3. **Mobile (iOS/Android)**: Transfer the file to your phone, open in Safari/Chrome, and select **"Add to Home Screen"**. It will work like a native app.

    - *下载 index.html -&gt; 电脑直接打开，或在手机浏览器中打开并选择“添加到主屏幕”，体验如原生App。*

## 🕹️ Controls // 操作指南

| **Action** | **Description** | **操作** | **说明** |
| --- | --- | --- | --- |
| **[ + ]** | Create new protocol | **[ + ]** | 新建番剧记录 |
| **[ √ ]** | Toggle selection mode | **[ √ ]** | 开启/关闭批量选择模式 |
| **[ 🗑️ ]** | Delete selected items | **[ 🗑️ ]** | 删除选中的项目（需二次确认） |
| **Undo/Redo** | Revert/Reapply changes | **撤销/重做** | 回滚或重做之前的操作 |
| **Export** | Generate Sync Code | **导出** | 生成压缩后的番剧同步码（自动复制到剪贴板） |
| **Import** | Load data from Code | **导入** | 读取同步码同步当前数据 |

## 🏗️ Tech Stack // 技术栈

- **Core**: React 18 (Runtime compilation via Babel)
- **Styling**: Tailwind CSS (CDN)
- **Logic**: LocalStorage API, Custom Base36 Stream
- **Fonts**: Orbitron, VT323, Share Tech Mono (Google Fonts)

## 📄 License

[MIT License](https://www.google.com/search?q=LICENSE "null") © 2026

> 
> *System.V13.2.3 //* *Ready for data injection...*

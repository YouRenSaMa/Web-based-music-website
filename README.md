# 🎶 基于 Web 的音乐在线平台 (Web-based Music Website)

[![Tech Stack](https://img.shields.io/badge/Tech_Stack-Java_/_Vue_/_MySQL-orange.svg)](https://github.com/YouRenSaMa)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Interface](https://img.shields.io/badge/UI-Responsive-brightgreen.svg)](https://github.com/YouRenSaMa)

---

## 🎵 项目简介 (Project Overview)
本项目是一个全栈 Web 音乐播放平台，集成了音乐在线播放、歌词同步显示、用户收藏管理及音乐搜索功能。旨在为用户提供流畅的听歌体验，同时为管理员提供便捷的后台资源管理工具。

This is a full-stack Web music platform featuring online playback, synchronized lyrics, collection management, and music search, providing a seamless audio experience and robust management tools.

---

## ✨ 核心功能 (Core Features)

### 1. 音乐播放引擎 (Playback Engine)
* **实时播放控制**：支持顺序、随机、单曲循环播放模式。
* **进度条交互**：支持点击、拖动进度条跳转播放位置。
* **Audio Control**: Supports sequential, random, and single-loop modes with interactive progress bars.

### 2. 歌词同步渲染 (Lyric Synchronization)
* **动态滚动**：自动解析 `.lrc` 文件，根据当前播放时间高亮并滚动显示对应歌词。
* **Dynamic Scrolling**: Parses `.lrc` files and highlights lyrics in real-time.

### 3. 用户互动 (User Interaction)
* **个人收藏列表**：用户可以收藏喜爱的歌曲并生成专属歌单。
* **音乐搜索**：支持按歌手名或歌曲名快速检索。
* **Collections & Search**: Personalized favorite lists and keyword-based search.

### 4. 后台管理 (Admin Dashboard)
* **资源管理**：管理员可上传/删除歌曲文件、封面图片及编辑音乐详情。
* **Content Management**: Upload/delete songs, covers, and edit music metadata.

---

## 🛠️ 技术架构 (Tech Stack)

* **前端 (Frontend)**: HTML5 / CSS3 / JavaScript (或 Vue.js/React)
* **后端 (Backend)**: Java (Spring Boot) / Node.js
* **数据库 (Database)**: MySQL
* **音频处理**: HTML5 Web Audio API
* **网络通信**: Axios / Ajax

---

## 📂 项目结构 (Project Structure)
```text
.
├── src/
│   ├── main/java/        # 后端业务逻辑 (Backend Logic)
│   └── resources/        # 配置文件与静态资源 (Config & Assets)
├── web/                  # 前端页面与样式 (Frontend Pages)
│   ├── css/              # 样式表 (Stylesheets)
│   ├── js/               # 播放器核心逻辑 (Player Logic)
│   └── index.html        # 主入口 (Main Entrance)
└── sql/                  # 数据库表结构 (Database Schema)

<div align="center">

# 🐍 复古贪吃蛇

**经典复古风格 HTML5 贪吃蛇游戏**

[![GitHub](https://img.shields.io/badge/GitHub-Project-blue?logo=github)](https://github.com/aiyangtongxue/retro-games-hub)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 📌 项目简介

复古贪吃蛇是一款采用 HTML5 Canvas 与面向对象架构开发的经典贪吃蛇游戏。项目使用 ES6 Class 封装游戏逻辑，代码结构清晰，具备动态难度递增、碰撞检测、最高分持久化等完整游戏机制。复古像素风格设计搭配深色主题，还原经典游戏体验。

---

## ✨ 核心特性

- 🐍 **经典贪吃蛇玩法** — 方向键控制蛇身移动，吃食物增长
- 📈 **动态难度** — 每吃一个食物速度递增，越玩越刺激
- 🏆 **最高分记录** — localStorage 持久化存储，挑战自我
- 🎨 **复古像素风格** — Courier New 字体 + 深色主题，怀旧感十足
- 📱 **移动端支持** — 响应式虚拟方向键，触屏可玩
- ⌨️ **键盘控制** — 方向键操控，手感流畅
- 🧱 **碰撞检测** — 撞墙或撞自身即 Game Over
- 🏗️ **OOP 架构** — ES6 Class 封装，代码可维护性强

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 Canvas | 游戏渲染引擎 |
| JavaScript (ES6+) | 游戏逻辑（Class 面向对象封装） |
| CSS3 | 复古风格样式与响应式布局 |
| localStorage | 最高分持久化存储 |
| setInterval | 游戏主循环定时器 |

---

## 🚀 快速开始

### 前置条件

- 现代浏览器（Chrome / Firefox / Safari / Edge）
- 无需安装任何依赖

### 安装步骤

```bash
git clone https://github.com/aiyangtongxue/retro-games-hub.git
cd retro-games-hub
```

### 运行命令

```bash
# 方式一：直接打开
start index.html

# 方式二：VSCode Live Server（推荐）

# 方式三：Python 简易服务器
python -m http.server 8080
```

### 在线演示

🔗 [复古贪吃蛇在线体验](https://aiyangtongxue.github.io/retro-games-hub)

---

## 📂 项目结构

```
retro-games-hub/
├── index.html          # 游戏主页面
├── css/
│   └── style.css       # 复古风格样式与响应式布局
├── js/
│   └── game.js         # 游戏核心逻辑（SnakeGame Class）
├── tcs.png             # 游戏截图
├── .gitignore          # Git 忽略配置
├── CNAME               # 自定义域名配置
└── README.md           # 项目说明文档
```

---

## 🎮 游戏规则

| 规则 | 说明 |
|------|------|
| 🎯 目标 | 控制蛇吃掉红色食物 |
| 🏅 得分 | 每个食物 +10 分 |
| ⚡ 加速 | 每吃一个食物速度递增 |
| 💀 死亡 | 撞墙或撞到自身 |
| 🏆 记录 | 最高分自动保存 |

---

## 🤝 贡献与许可证

欢迎提交 Issue 和 Pull Request 来帮助改进项目！

本项目采用 **MIT License** 开源协议，详情请见 [LICENSE](LICENSE) 文件。

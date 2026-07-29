# 🎮 坦克大战 (Battle City)

经典坦克大战的 HTML5 Canvas 重制版，纯前端实现，打开浏览器即可游玩。

![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🕹️ 在线游玩

访问 GitHub Pages 即可直接在浏览器中游玩：

👉 **https://YOUR_USERNAME.github.io/tank-battle/**

（请将 `YOUR_USERNAME` 替换为你的 GitHub 用户名）

## 🎯 游戏特色

- 🏆 **3个关卡** — 不同的地图布局，通关后循环增加难度
- 🎖️ **4种敌方坦克** — 普通、快速、强力、装甲，各有特点
- 🧱 **多种地形** — 砖墙（可破坏）、钢墙、水域、树林、冰面
- ⭐ **道具系统** — 火力增强、护盾、全屏炸弹、额外生命、冻结敌人、加固基地
- 🔊 **音效** — 使用 Web Audio API 合成的复古音效
- 📱 **简洁界面** — 侧边栏实时显示关卡、得分、生命和剩余敌人

## 🕹️ 操作说明

| 按键 | 功能 |
|------|------|
| `↑ ↓ ← →` / `W A S D` | 移动坦克 |
| `空格` / `J` | 射击 |
| `P` | 暂停/继续 |
| `Enter` | 确认/重新开始 |

## 🗺️ 地形说明

| 地形 | 效果 |
|------|------|
| 🧱 砖墙 | 可被子弹摧毁 |
| ⬜ 钢墙 | 普通子弹无法摧毁（火力增强后可破） |
| 🌊 水域 | 坦克无法通过 |
| 🌲 树林 | 坦克可通过，提供视觉遮挡 |
| 🧊 冰面 | 坦克会滑行 |

## 🎁 道具说明

| 道具 | 效果 |
|------|------|
| ⭐ 星星 | 增强火力，子弹可破钢墙 |
| 🛡 护盾 | 临时无敌 |
| 💣 炸弹 | 消灭屏幕上所有敌人 |
| ❤ 生命 | 额外一条命 |
| ❄ 冻结 | 冻结所有敌人 |
| 🏰 堡垒 | 用钢墙加固基地 |

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/YOUR_USERNAME/tank-battle.git

# 进入目录
cd tank-battle

# 用任意 HTTP 服务器打开，或直接用浏览器打开 index.html
open index.html
```

## 📁 项目结构

```
tank-battle/
├── index.html      # 游戏主文件（HTML + CSS + JS 一体）
└── README.md       # 项目说明
```

## 📜 许可证

MIT License

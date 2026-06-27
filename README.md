<div align="center">

# Hermes Agent 中文教程 · 保姆级安装 + 实战手册

**Nous Research 开源 AI Agent 从零上手到自动化变现 —— 国内可用、自带网页控制台、不用翻墙**

蓝皮书（安装配置入门）· 红皮书（进阶实战与变现）· 持续更新

<br>

<a href="https://www.u-king.org/?from=hermes">
<img src="https://img.shields.io/badge/⬇%20一键安装%20Hermes-用%20U--King%20·%20免环境配置-5e6ad2?style=for-the-badge&logo=python&logoColor=white" alt="下载 U-King 一键安装 Hermes" height="46">
</a>

**嫌装 Python、配环境麻烦？** 上面这个 [U-King](https://www.u-king.org/?from=hermes) 帮你一键装好 Python 运行时 + Hermes + 接好国内可用的算力驱动，双击即用。

</div>

---

## 这是什么

[Hermes](https://github.com/NousResearch) 是 [Nous Research](https://nousresearch.com) 官方开源的 **AI Agent（智能体）框架**——它不只会聊天，更能**自己跑多步任务**：抓数据、发消息、定时执行、把一长串流程自动串起来跑完。它还自带一个**网页控制台**（默认端口 `9119`），在浏览器里就能下达任务、看 agent 干到哪一步了。

但国内用它有三个坑：

1. **装不上 / 环境难配**——它靠 **Python 的 pip** 安装（不是 npm），比 Codex、Claude Code 这种"下个 exe 就跑"的工具重；缺 Python、`Scripts` 没进 PATH、依赖装不上，新手一上来就劝退。
2. **模型不好接**——Hermes 默认指向国外模型，国内充值、网络都是门槛。
3. **比别的工具门槛高**——所以 U-King 把它归为**"进阶 / 选装"工具**：先把 Claude Code、Codex、ClawX 这些轻量的玩顺了，再上 Hermes 做自动化。

这本手册把这三个坑全部填平，并给你一条**最省事的路**：用 [U-King](https://www.u-king.org/?from=hermes) 一键装好 Python 运行时 + Hermes、接好国内可用的 **虾盘云驱动**（¥1 ≈ 50 万 token，不用注册任何国外账号），开箱就能跑第一个 agent 任务。

> 💡 **U-King 是什么？** 一个"谁火装谁、装完教会用"的 AI 工具学习盘 / 装机管家：Codex、Claude Code、Hermes、ClawX 一键装好并接好国内算力，免去环境配置和翻墙。本手册就是它配套的 Hermes 教程。

---

## 📖 手册目录

| | 内容 | 适合 |
|---|---|---|
| 📘 **[蓝皮书 · 安装配置入门](./蓝皮书-入门.md)** | 是什么 → 装法（U-King 一键 / 手动 pip）→ 启动网页控制台（9119）→ 配模型 → 跑通第一个 agent 任务 → 报错 TOP5 | 第一次用 Hermes |
| 📕 **[红皮书 · 进阶实战与变现](./红皮书-进阶.md)** | 自动化获客、留言机器人、定时抓取播报、多步任务编排、接私活搭自动化系统、提示词/配置模板库 | 已装好、想玩深 |

---

## 🚀 三步上手（最快路径）

1. **装好** —— 下载 [U-King](https://www.u-king.org/?from=hermes)，在里面一键安装 Hermes（它会顺带把 Python 运行时备好；或照 [蓝皮书](./蓝皮书-入门.md) 手动 `pip install`）。
2. **配模型** —— U-King「AI 设置 → Hermes」选「虾盘云」，自动配好，充值即用，不用折腾国外 Key。
3. **开干** —— 启动 Hermes 控制台（浏览器开 `http://127.0.0.1:9119`），用中文给它派第一个自动化任务。看 [红皮书](./红皮书-进阶.md) 学进阶玩法。

---

<div align="center">

## 卡住了？想要更多模板 / 定制？

<img src="./assets/wechat-qr.jpg" alt="加微信" width="220">

**扫码加微信** —— 安装报错、配置疑难、搭自动化系统接私活，1v1 帮你搞定
更多工具教程见 👉 **[u-king.org/学院](https://www.u-king.org/?from=hermes)**

</div>

---

## 关于本手册

- **谁火就教谁**：本手册是 [U-King 学习盘](https://www.u-king.org/?from=hermes) 教程矩阵的一员（Codex / Claude Code / Hermes / ClawX / AI 作图 / Obsidian）。
- **原创内容**：所有步骤经实测，非搬运。Hermes 为 Nous Research 官方开源产品，本手册只讲怎么在国内顺畅地用上它。
- **许可**：[CC BY-NC 4.0](./LICENSE) —— 欢迎转载分享，请保留出处与二维码，禁止商用。

⭐ 觉得有用点个 Star，让更多人少踩坑。

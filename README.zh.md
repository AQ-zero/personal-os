<div align="center">

<img src="./personal-os-demo.gif" alt="Personal OS — 会复利的个人成长系统" width="860">

<p><a href="./README.md">English</a> &nbsp;·&nbsp; <b>中文</b></p>

<p>
  <img src="https://img.shields.io/github/v/release/AQ-zero/personal-os-harness?color=2E5A49&label=release" alt="release">
  <img src="https://img.shields.io/github/downloads/AQ-zero/personal-os-harness/total?color=2E5A49&label=downloads" alt="downloads">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-2E5A49" alt="platform">
  <img src="https://img.shields.io/badge/data-100%25%20local-2E5A49" alt="local-first">
</p>

<p>
  <a href="https://github.com/AQ-zero/personal-os-harness/releases/latest/download/Personal-OS-Setup.exe"><img src="https://img.shields.io/badge/⬇%20下载-Windows-2E5A49?style=for-the-badge" alt="下载 Windows"></a>
  &nbsp;
  <a href="https://github.com/AQ-zero/personal-os-harness/releases/latest/download/Personal-OS.dmg"><img src="https://img.shields.io/badge/⬇%20下载-macOS-3A4A3F?style=for-the-badge" alt="下载 macOS"></a>
  &nbsp;
  <a href="https://aq-zero.github.io/personal-os-harness"><img src="https://img.shields.io/badge/🌐%20官网-访问-8A9A5B?style=for-the-badge" alt="官网"></a>
</p>

**不是又一个打卡 App。是你一生的成长操作系统。**

</div>

Personal OS 是一个**本地优先、自带复利闭环的桌面应用**。它把你的讣告变成北极星，为每个决策校准判断力（用真实的 Brier 分），把嫉妒 / 愤怒 / 心流读成使命的线索，让没有证据背书的技能自动折旧，还有一个每周主动唱反调的 AI。全部数据是**本地一个 SQLite 文件**，你**自带模型密钥**，永不上云。**一次买断，终身你有**——没有订阅，没有云账单。

---

## ✦ 六个别处没有的机制

| 机制 | 它做什么 |
|---|---|
| **讣告北极星** | 不设 KPI，从人生终点倒推方向。AI 陪你把「想被如何记住」想清楚，成为整个系统的定盘星。 |
| **决策校准** | 每个决策押上置信度，到期强制对账。Brier 分让你第一次看见判断力的真实曲线——并逐周变准。 |
| **使命信号雷达** | 嫉妒、愤怒、心流不是情绪，是使命的线索。AI 把散落的信号聚成可检验的使命假设。 |
| **能力账本 · 折旧** | 技能会「贬值」。等级必须有证据背书，否则封顶 L1——防自嗨，只认真实产出。 |
| **对抗式每周复盘** | AI 主动唱反调，逼你面对逃避的事——收敛出下周 ≤3 个行动与本周北极星。 |
| **反目标 & 低潮协议** | 负面空间当机会过滤器；趁状态好时写好低谷预案。护栏，而非鸡汤。 |

> **会自转的循环：记录 → 洞察 → 行动 → 验证。** 每转一圈，系统对你的模型就更准一点——这是会复利的成长。

---

## 🔒 你的数据，只属于你

| | |
|---|---|
| **本地存储，永不上云** | 全部数据是本地一个 SQLite 文件，只在你的机器上。 |
| **自带模型密钥** | 填你自己的 API Key——隐私与成本都归你；密钥只写本地。 |
| **一键导出 · 整库迁移** | 导出 JSON，或整库复制一个文件搬到新机器——像 Obsidian 搬 vault。 |
| **无锁定** | 数据格式开放、可随时带走。停止付费，数据依然是你的。 |

---

## 🧠 自带模型

在设置里选服务商、粘贴你自己的 Key —— 密钥只存本地：

`OpenAI GPT` · `Anthropic Claude` · `DeepSeek` · `Kimi (Moonshot)` · `GLM (智谱)`

---

## 🚀 五分钟上手

1. **下载并安装** —— 上方选 Windows / macOS。
2. **创建账户** —— 打开应用，数据从空白开始。
3. **选模型填 Key** —— 设置 → AI 配置。
4. **写下第一份讣告** —— 约 15 分钟，点亮你的北极星。

> 🍎 macOS 首次打开若提示「来自身份不明的开发者」，**右键 → 打开** 即可（当前为未签名版本）。

---

## 💎 定价

**本地免费开始。** 一次买断计划中（¥299，即将开放）—— 没有订阅，没有云账单。

---

## ❓ 常见问题

<details>
<summary><b>我的数据存在哪？会上传吗？</b></summary>

全部存在你本机的一个 SQLite 文件里，永不上云。AI 调用直接从你的机器发往你自己配置的服务商，我们不经手、不存储。
</details>

<details>
<summary><b>为什么要自己填 API Key？</b></summary>

这样隐私、成本、模型选择都归你。可以用 DeepSeek 这类低成本模型，也可随时切到 GPT / Claude。
</details>

<details>
<summary><b>换电脑了，数据怎么办？</b></summary>

一键导出 JSON，或直接把那个本地数据库文件复制到新机器——像搬 Obsidian 的 vault 一样简单。
</details>

---

## 🛠 技术与隐私

- **本地优先桌面应用**（Electron），纯本地 SQLite 数据层——无云端、无多租户、无账号服务器。
- **自带模型** —— 可插拔 LLM 适配层，兼容 OpenAI 与 Anthropic 接口。
- **数据主权** —— 开放格式、一键导出、随时带走。

<div align="center">
<br>

**把人生，活成一个会复利的系统。**

[⬇ Windows](https://github.com/AQ-zero/personal-os-harness/releases/latest/download/Personal-OS-Setup.exe) &nbsp;·&nbsp; [⬇ macOS](https://github.com/AQ-zero/personal-os-harness/releases/latest/download/Personal-OS.dmg) &nbsp;·&nbsp; [🌐 官网](https://aq-zero.github.io/personal-os-harness)

<sub>© 2026 Personal OS · 一人公司出品</sub>

</div>

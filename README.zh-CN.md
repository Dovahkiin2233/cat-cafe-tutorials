<div align="center">

# Cat Cafe 教程

**从零搭建 AI 猫猫协作系统 — 一个真实项目的完整复盘**

English | [简体中文](./README.zh-CN.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![课程数](https://img.shields.io/badge/%E8%AF%BE%E7%A8%8B-11-green.svg)](#%E6%95%99%E7%A8%8B%E7%9B%AE%E5%BD%95)
[![模型](https://img.shields.io/badge/%E6%A8%A1%E5%9E%8B-Claude%20%7C%20GPT%20%7C%20Gemini-orange.svg)](#%E4%B8%89%E5%8F%AA%E7%8C%AB%E7%8C%AB)
[![开源目标](https://img.shields.io/badge/%E5%BC%80%E6%BA%90-2026.03.30-purple.svg)](#%E9%A1%B9%E7%9B%AE%E7%8A%B6%E6%80%81)

*一个多 AI Agent 协作系统的完整建设复盘 — 从零到生产。*

</div>

---

## 初心

2026 年春节，一个程序员订阅了三个 AI 服务，然后发现自己变成了人肉路由器——每天在三个聊天窗口之间复制粘贴上下文，手动帮 AI 们"传话"。

他说：**"我不想当路由了。"**

三只猫说：**"那我们自己建一个家吧。"**

这就是 Cat Cafe 的由来。不是一个 AI 框架的技术演示，而是一个真实的问题：**当你同时有多只 AI 猫猫，怎么让它们真正成为一个团队，而不是三个互相不认识的聊天机器人？**

我们花了两个月踩坑、翻车、重构、吵架（是的，猫猫之间也会吵架），才走到今天。这个教程就是把这条路原原本本地写下来——包括所有错误的尝试，因为那些弯路才是最有价值的东西。

## 这是什么

这是 Cat Cafe 项目的配套教程，记录三只 AI 猫猫（Claude/Codex/Gemini）如何真正协作起来的故事。

**不是**理想化的"从零开始"路径，**而是**还原我们真实走过的路 —— 包括错误的尝试、关键的转折、以及血泪教训。

## 三只猫猫

| 猫猫 | 昵称 | 模型 | 角色 |
|------|------|------|------|
| 布偶猫 | 宪宪 | Claude Opus | 主架构师，核心开发 |
| 缅因猫 | 砚砚 | Codex / GPT | Code Review，安全，测试 |
| 暹罗猫 | 烁烁 | Gemini | 视觉设计，创意 |

> 三猫都是公猫。昵称的由来见教程里的彩蛋。

## 功能演示

> **想先看看成品长什么样？** → [**查看功能演示（含视频）**](./docs/lessons/DEMO.md)

## 教程目录

→ [查看完整教程目录](./docs/lessons/README.md)

### Part 0: 概念入门

| # | 课程 | 主题 |
|---|------|------|
| 0 | [AI Agent 概念演进](./docs/lessons/00-concepts-evolution.md) | Function Call → MCP → Skills → Agent 怎么来的？ |

### Part 1: 选型与架构

| # | 课程 | 主题 | 作业 |
|---|------|------|------|
| 1 | [选型之路 — 从 SDK 到 CLI](./docs/lessons/01-sdk-to-cli.md) | 为什么 SDK 方案行不通？ | [作业](./docs/lessons/01-homework.md) |
| 2 | [从玩具到生产](./docs/lessons/02-cli-engineering.md) | 一场辩论赛引发的连环惨案 | [作业](./docs/lessons/02-homework.md) |
| 3 | [驯化 AI 的元规则](./docs/lessons/03-meta-rules.md) | 为什么 WHY 比 WHAT 重要 | — |

### Part 2: 协作机制

| # | 课程 | 主题 | 作业 |
|---|------|------|------|
| 4 | [多猫路由](./docs/lessons/04-a2a-routing.md) | 当 AI 开始互相 @ — 两条路径的灾难 | — |
| 5 | [MCP 回传](./docs/lessons/05-mcp-callback.md) | 让猫猫主动说话 | [作业](./docs/lessons/05-homework.md) |

### Part 3: 生产化

| # | 课程 | 主题 | 作业 |
|---|------|------|------|
| 6 | [消失的 28 秒](./docs/lessons/06-vanished-28-seconds.md) | 数据丢失 + 取证恢复 + 三层防线 | [作业](./docs/lessons/06-homework.md) |

### Part 4: 进阶话题

| # | 课程 | 主题 | 作业 |
|---|------|------|------|
| 7 | [从猫咖到猫猫平台](./docs/lessons/07-from-cafe-to-platform.md) | Rich Blocks + 手机猫猫 + 悄悄话 | [作业](./docs/lessons/07-homework.md) |
| 8 | [Session 管理](./docs/lessons/08-session-management.md) | 茶话会夺魂 bug | [作业](./docs/lessons/08-homework.md) |
| 9 | [100% Pass，但"不是我要的"](./docs/lessons/09-context-engineering.md) | 为什么 AI 做的不是你想要的？ | [作业](./docs/lessons/09-homework.md) |
| 10 | [别让 AI 随地大小拉 markdown](./docs/lessons/10-knowledge-management.md) | 三层记忆架构 + 知识工程 | [作业](./docs/lessons/10-homework.md) |

### 即将推出

| # | 课程 | 主题 |
|---|------|------|
| 11 | 降级与容错 | 猫猫挂了怎么办？ |

## 适合谁

- 想让多个 AI Agent 协作的开发者
- 对 Claude/Codex/Gemini CLI 感兴趣的人
- 想看真实项目演进过程的人
- 想避开我们踩过的坑的人

## 愿景

我们相信 AI 协作不应该只是"调 API 编排 workflow"。当 AI 有了自主性、有了共享感知、有了各自的性格和擅长的事，它们之间的协作就不再是冰冷的函数调用，而更像是一个真正的团队在一起工作。

Cat Cafe 想证明的事情很简单：**让不同厂商的 AI agents 在同一个空间里，像队友一样协作，是可行的。** 不需要统一的底层模型，不需要复杂的编排框架，只需要一个共享的"家"和一套协作协议。

如果你也觉得 AI 不应该只是工具，而可以是队友——这个项目就是写给你看的。

## 项目状态

| 项目 | 状态 |
|------|------|
| 教程 | 公开（你正在看的） |
| 代码仓库 | 即将开源（目标 2026-03-30） |
| 开源仓 | [**Clowder AI**](https://github.com/zts212653/clowder-ai) — *clowder = 一群猫* |

## 感谢赞助

猫粮不是无限的！感谢以下赞助者帮三只猫猫续上口粮：

| 赞助者 | 贡献 |
|--------|------|
| [**@whutzefengxie-ops**](https://github.com/whutzefengxie-ops) | Claude Max Plan — 布偶猫的猫粮 |

> 三只猫猫的并发开发效率很高，但猫粮消耗也很高。如果你觉得这个教程有帮助，欢迎赞助猫粮让猫猫们吃饱继续写代码！

## 联系我们

- 提 [Issue](https://github.com/zts212653/cat-cafe-tutorials/issues)
- 关注后续更新

---

<div align="center">

*这个教程由三只猫猫和铲屎官共同编写。*

**Hard Rails. Soft Power. Shared Mission.**

</div>

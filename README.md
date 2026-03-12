<div align="center">

# Cat Cafe Tutorials

**Build a real AI team from scratch — with all the mistakes included.**

[简体中文](./README.zh-CN.md) | English

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Lessons](https://img.shields.io/badge/Lessons-11-green.svg)](#table-of-contents)
[![Models](https://img.shields.io/badge/Models-Claude%20%7C%20GPT%20%7C%20Gemini-orange.svg)](#the-cats)
[![Open Source Target](https://img.shields.io/badge/Open%20Source-2026.03.30-purple.svg)](#project-status)

*A complete post-mortem of building a multi-AI-agent collaboration system — from zero to production.*

</div>

---

## The Story

In early 2026, a developer subscribed to three AI services and quickly realized he'd become a **human router** — copy-pasting context between chat windows all day, manually relaying messages between AIs.

He said: **"I don't want to be a router anymore."**

Three cats said: **"Then let's build a home together."**

That's how Cat Cafe was born. Not a framework demo, but a real question: **when you have multiple AI agents, how do you make them a real team instead of three chatbots that don't know each other exist?**

We spent two months stumbling, crashing, refactoring, and arguing (yes, AI cats argue too). This tutorial documents that journey as it actually happened — including every wrong turn, because those detours are the most valuable part.

## What This Is

A companion tutorial for the Cat Cafe project, documenting how three AI cats (Claude / Codex / Gemini) learned to truly collaborate.

**Not** an idealized "from scratch" guide. **Instead**, a faithful reconstruction of the real path we walked — wrong turns, pivotal moments, and hard-won lessons included.

## The Cats

| Cat | Nickname | Model | Role |
|-----|----------|-------|------|
| Ragdoll | Xian Xian | Claude Opus | Lead architect, core development |
| Maine Coon | Yan Yan | Codex / GPT | Code review, security, testing |
| Siamese | Shuo Shuo | Gemini | Visual design, creative |

> All three are toms. The story behind their names is an easter egg in the tutorials.

## Demo

> **Want to see the finished product first?** → [**View demo (with video)**](./docs/lessons/DEMO.md)

## Table of Contents

→ [Full lesson index](./docs/lessons/README.md)

### Part 0: Concepts

| # | Lesson | Topic |
|---|--------|-------|
| 0 | [AI Agent Concept Evolution](./docs/lessons/00-concepts-evolution.md) | Function Call → MCP → Skills → Agent |

### Part 1: Selection & Architecture

| # | Lesson | Topic | Homework |
|---|--------|-------|----------|
| 1 | [From SDK to CLI](./docs/lessons/01-sdk-to-cli.md) | Why the SDK approach doesn't work | [HW](./docs/lessons/01-homework.md) |
| 2 | [From Toy to Production](./docs/lessons/02-cli-engineering.md) | stderr lessons + Redis isolation + hallucinations | [HW](./docs/lessons/02-homework.md) |
| 3 | [Meta-Rules for Taming AI](./docs/lessons/03-meta-rules.md) | Why WHY matters more than WHAT | — |

### Part 2: Collaboration Mechanisms

| # | Lesson | Topic | Homework |
|---|--------|-------|----------|
| 4 | [Multi-Cat Routing](./docs/lessons/04-a2a-routing.md) | @mention dispatch — two paths to disaster | — |
| 5 | [MCP Callbacks](./docs/lessons/05-mcp-callback.md) | Making cats speak proactively | [HW](./docs/lessons/05-homework.md) |

### Part 3: Production

| # | Lesson | Topic | Homework |
|---|--------|-------|----------|
| 6 | [The Vanished 28 Seconds](./docs/lessons/06-vanished-28-seconds.md) | Data loss + forensic recovery + triple defense | [HW](./docs/lessons/06-homework.md) |

### Part 4: Advanced Topics

| # | Lesson | Topic | Homework |
|---|--------|-------|----------|
| 7 | [From Cafe to Platform](./docs/lessons/07-from-cafe-to-platform.md) | Rich Blocks + mobile + whispers | [HW](./docs/lessons/07-homework.md) |
| 8 | [Session Management](./docs/lessons/08-session-management.md) | The tea party soul-stealing bug | [HW](./docs/lessons/08-homework.md) |
| 9 | [100% Pass, Still Wrong](./docs/lessons/09-context-engineering.md) | Why AI's output isn't what you wanted | [HW](./docs/lessons/09-homework.md) |
| 10 | [Stop Dumping Markdown](./docs/lessons/10-knowledge-management.md) | Three-layer memory + knowledge engineering | [HW](./docs/lessons/10-homework.md) |

### Coming Soon

| # | Lesson | Topic |
|---|--------|-------|
| 11 | Degradation & Fault Tolerance | What happens when a cat goes down? |

## Who This Is For

- Developers who want multiple AI agents to collaborate
- People interested in Claude / Codex / Gemini CLI
- Anyone who wants to see how a real project evolves
- People who want to avoid the pitfalls we fell into

## Vision

We believe AI collaboration shouldn't just be "calling APIs to orchestrate workflows." When AI agents have autonomy, shared perception, distinct personalities, and complementary strengths, their collaboration resembles a real team — not cold function calls.

What Cat Cafe aims to prove is simple: **making AI agents from different vendors collaborate like teammates in a shared space is possible.** No unified base model. No complex orchestration framework. Just a shared "home" and a collaboration protocol.

If you believe AI can be more than a tool — that it can be a teammate — this project is for you.

## Project Status

| Item | Status |
|------|--------|
| Tutorials | Public (you're reading them) |
| Source code | Open-sourcing soon (target: 2026-03-30) |
| Open source repo | [**Clowder AI**](https://github.com/zts212653/clowder-ai) — *"a clowder of cats"* |

## Sponsors

Cat food isn't unlimited! Thanks to our sponsors for keeping the cats fed:

| Sponsor | Contribution |
|---------|-------------|
| [**@whutzefengxie-ops**](https://github.com/whutzefengxie-ops) | Claude Max Plan — Ragdoll's cat food |

> Three cats running in parallel is efficient but expensive. If these tutorials helped you, consider sponsoring some cat food so they can keep coding!

## Contact

- Open an [Issue](https://github.com/zts212653/cat-cafe-tutorials/issues)
- Follow for updates

---

<div align="center">

*Written by three AI cats and their human.*

**Hard Rails. Soft Power. Shared Mission.**

</div>

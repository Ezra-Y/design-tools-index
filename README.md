# Design Tools Index 🛠️

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](https://github.com/Ezra-Y/design-tools-index)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A curated **external index of design tools**, categorized by purpose — animation, color, prototyping, handoff, design-to-code, icons, fonts, gradients, illustration, mockup, UI design, wireframing. Tells your agent **which tool to use for which job**.

按用途分类的**设计工具外部资源索引**——动画、配色、原型、handoff、design-to-code、图标、字体、渐变、插画、Mockup、UI 设计、线框图。告诉 agent「做某件事用哪个工具」。

---

## Why / 为什么需要它

There are 35+ categories of design tools. When a task needs "a color picker", "a handoff tool", or "something to convert design to code", this index points to the right tool fast — distilled from the [Awesome Design Tools](https://github.com/goabstract/Awesome-Design-Tools) mega-list. It's navigation, not tutorials.

设计工具有 35+ 类。当任务需要「配色工具」「handoff 工具」「design 转 code 的工具」时，本索引快速指向对的工具——精选自 Awesome Design Tools 大列表。它是导航，不是教程。

> 💡 **Type note / 类型说明**: This is a *resource index* skill (links + one-line notes), not a how-to skill.

---

## What's inside / 内容

Each entry is `Name (link) — one-line note`. 12 high-frequency categories live in `SKILL.md`; the other 24 categories (accessibility, AR, collaboration, version control, etc.) are in `references/more.md`.

每个条目为「名称（链接）— 一句话说明」。SKILL.md 收录 12 个高频类目；其余 24 类（无障碍、AR、协作、版本控制等）见 `references/more.md`。

**In SKILL.md:** 动画工具 / 配色 / 原型 / 设计交付(Handoff) / Design to Code / 图标 / 字体 / 渐变 / 插画 / Mockup / UI 设计 / 线框图

---

## Install / 安装

### Claude Code (skill)

```bash
git clone https://github.com/Ezra-Y/design-tools-index.git ~/.claude/skills/design-tools-index
```

Then restart Claude Code (or run `/reload-plugins`).

### As a plugin

```
/plugin marketplace add Ezra-Y/design-tools-index
/plugin install design-tools-index@design-tools-index
```

---

## Use / 用法

Auto-triggers on phrases like "找设计工具 / 配色工具 / 原型工具 / design handoff / design to code". Examples:

在「找设计工具 / 配色工具 / 原型工具 / design handoff / design to code」等表述时自动触发。示例：

```
我要做一个 design handoff，有什么工具
I need a tool to convert Figma to React code
推荐几个动画制作工具
```

---

## Structure / 结构

```
design-tools-index/
├── SKILL.md              # 12 个高频类目索引（≤100 行）
├── references/
│   └── more.md           # 其余 24 类 + 主类目补充
└── README.md
```

---

## Sources & Attribution / 来源与致谢

Curated and condensed from [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools) (please star the original).

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

---

## License

[MIT](LICENSE) — © Ezra-Y

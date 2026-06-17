<div align="center">

# Design Tools Index 🛠️

A curated external index of design tools, categorized by purpose — animation, color, prototyping, handoff, design-to-code, and more.

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[中文](README.zh-CN.md) · English

</div>

---

## Why

There are 35+ categories of design tools. When a task needs "a color picker", "a handoff tool", or "something to convert design to code", this index points to the right tool fast — distilled from the [Awesome Design Tools](https://github.com/goabstract/Awesome-Design-Tools) mega-list. It's navigation, not tutorials.

> 💡 **Type note:** This is a *resource index* skill (links + one-line notes), not a how-to skill.

## What's inside

Each entry is `Name (link) — one-line note`. `SKILL.md` is a **dispatch index**: 2–3 top picks per category inline, with the full list in per-category reference files (loaded on demand):

- 🎨 Color → `references/color.md`
- 🖼 Graphic assets (icons, fonts, illustrations…) → `references/graphic-assets.md`
- 🖊 UI design & wireframing → `references/ui-and-wireframe.md`
- 🎞 Prototyping & animation → `references/prototyping-and-animation.md`
- 🔁 Handoff & design-to-code → `references/handoff-and-code.md`
- 📱 Mockup → `references/mockup.md`
- ♿ Accessibility → `references/accessibility.md`
- 🔎 User research & information architecture → `references/user-research-and-ia.md`
- 🤝 Collaboration, feedback & version control → `references/collaboration-feedback-vcs.md`
- 🧩 Design systems & dev → `references/design-systems-and-dev.md`
- 🎞 Media assets → `references/media-assets.md`
- 💡 Creation & inspiration → `references/creation-and-inspiration.md`
- 🧊 3D & AR → `references/3d-and-ar.md`

## Install

```bash
git clone https://github.com/Ezra-Y/design-tools-index.git ~/.claude/skills/design-tools-index
```

Then restart Claude Code (or run `/reload-plugins`).

## Use

Auto-triggers on phrases like "找设计工具 / 配色工具 / 原型工具 / design handoff / design to code". Examples:

```
I need a tool to convert Figma to React code
我要做一个 design handoff，有什么工具
Recommend a few animation tools
```

## Structure

```
design-tools-index/
├── SKILL.md              # dispatch index: 2-3 picks per category + pointers
├── references/           # per-category full lists (loaded on demand)
│   ├── color.md
│   ├── graphic-assets.md
│   ├── ui-and-wireframe.md
│   ├── prototyping-and-animation.md
│   ├── handoff-and-code.md
│   ├── mockup.md
│   ├── accessibility.md
│   ├── user-research-and-ia.md
│   ├── collaboration-feedback-vcs.md
│   ├── design-systems-and-dev.md
│   ├── media-assets.md
│   ├── creation-and-inspiration.md
│   └── 3d-and-ar.md
└── README.md
```

## Sources & Attribution

Data sourced from [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools) — the mega-list of design tools (originally maintained by Flawless App / Abstract) covering 35+ categories. This skill curates the high-frequency tool categories into `SKILL.md`'s dispatch index and groups the rest into per-category reference files. The original list is more complete and updated more often — please star the original repo.

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

## License

[MIT](LICENSE) — © Ezra-Y

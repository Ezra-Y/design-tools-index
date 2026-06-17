<div align="center">

# 设计工具索引 🛠️

按用途分类的设计工具外部资源索引——动画、配色、原型、handoff、design-to-code 等。

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[English](README.md) · 中文说明

</div>

---

## 为什么需要它

设计工具有 35+ 类。当任务需要「配色工具」「handoff 工具」「design 转 code 的工具」时，本索引快速指向对的工具——精选自 Awesome Design Tools 大列表。它是导航，不是教程。

> 💡 **类型说明**：这是*资源索引* skill（链接 + 一句话说明），不是 how-to skill。

## 内容

每个条目为「名称（链接）— 一句话说明」。`SKILL.md` 是**调度索引**：每类 2–3 条精选内联，完整列表在按分类的 reference 文件（按需读取 / loaded on demand）：

- 🎨 配色 → `references/color.md`
- 🖼 图形素材（图标、字体、插画…）→ `references/graphic-assets.md`
- 🖊 UI 设计与线框图 → `references/ui-and-wireframe.md`
- 🎞 原型与动画 → `references/prototyping-and-animation.md`
- 🔁 交付(Handoff)与 design-to-code → `references/handoff-and-code.md`
- 📱 Mockup → `references/mockup.md`
- ♿ 无障碍 → `references/accessibility.md`
- 🔎 用户研究与信息架构 → `references/user-research-and-ia.md`
- 🤝 协作、反馈与版本控制 → `references/collaboration-feedback-vcs.md`
- 🧩 设计系统与开发 → `references/design-systems-and-dev.md`
- 🎞 媒体素材 → `references/media-assets.md`
- 💡 创作与灵感 → `references/creation-and-inspiration.md`
- 🧊 3D 与 AR → `references/3d-and-ar.md`

## 安装

```bash
git clone https://github.com/Ezra-Y/design-tools-index.git ~/.claude/skills/design-tools-index
```

然后重启 Claude Code（或跑 `/reload-plugins`）。

## 用法

在「找设计工具 / 配色工具 / 原型工具 / design handoff / design to code」等表述时自动触发。示例：

```
我要做一个 design handoff，有什么工具
I need a tool to convert Figma to React code
推荐几个动画制作工具
```

## 结构

```
design-tools-index/
├── SKILL.md              # 调度索引：每类 2-3 精选 + 指针
├── references/           # 按分类的完整列表（按需读取）
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

## 来源与致谢

本 skill 的数据来自 [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools)——设计工具大全（原由 Flawless App / Abstract 维护），原列表覆盖 35+ 类。本 skill 从中精选高频类目进入 `SKILL.md` 的调度索引，其余按类目分入各 reference 文件；原列表更全、更新更勤，建议给原仓库点 star。

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y

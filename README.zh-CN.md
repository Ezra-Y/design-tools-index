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

每个条目为「名称（链接）— 一句话说明」。SKILL.md 收录 12 个高频类目；其余 24 类（无障碍、AR、协作、版本控制等）见 `references/more.md`。

**SKILL.md 中：** 动画 · 配色 · 原型 · 设计交付(Handoff) · Design to Code · 图标 · 字体 · 渐变 · 插画 · Mockup · UI 设计 · 线框图

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
├── SKILL.md              # 12 个高频类目索引（≤100 行）
├── references/
│   └── more.md           # 其余 24 类 + 主类目补充
└── README.md
```

## 来源与致谢

内容精选、精简自 [goabstract/Awesome-Design-Tools](https://github.com/goabstract/Awesome-Design-Tools)（请给原仓库点 star）。

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y

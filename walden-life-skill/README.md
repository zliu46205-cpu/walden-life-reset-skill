# Walden Life Reset Skill

一个中文优先、兼顾英文用户的 Codex skill。它把《瓦尔登湖》的思想结构蒸馏成可用于生活心态整理、简化生活、恢复注意力、减少内耗和重新开始的 AI 辅助框架。

This is a Chinese-first Codex skill inspired by Walden / Thoreau. It helps an AI assistant respond to users who want to slow down, simplify life, recover attention, reflect on values, and design small deliberate-living experiments.

## What This Skill Is

它不是《瓦尔登湖》摘要，也不是电子书。它是一个面向 AI 助手的行为说明文件，让 AI 在合适场景下用《瓦尔登湖》的框架回应用户。

核心框架包括：

- `经济篇`
- `我生活的地方，我为何生活`
- `清醒就是生活`
- `更高的规律`
- `春天`
- `结束语`

适合用户说这些话时使用：

- “我很焦虑，开导一下我”
- “我最近很内耗”
- “我想慢下来”
- “我想重新开始”
- “我不知道自己想过怎样的生活”
- “我被工作/手机/消息/社交/消费/比较拖着走”
- “我想找回自己”
- “我是一个什么样的人”

## Install

把整个 `walden-life-reset` 文件夹复制到你的 Codex skills 目录。

Windows 通常是：

```text
C:\Users\<你的用户名>\.codex\skills\
```

macOS / Linux 通常是：

```text
~/.codex/skills/
```

最终目录结构应类似：

```text
~/.codex/skills/walden-life-reset/SKILL.md
~/.codex/skills/walden-life-reset/agents/openai.yaml
```

然后重启 Codex。

## Usage

显式调用：

```text
使用 $walden-life-reset，帮我做一次生活心态整理。我最近很焦虑、很内耗，想慢下来。
```

也可以自然表达：

```text
我不知道自己想过什么样的生活，帮我整理一下。
```

```text
我被工作和手机拖着走，想重新找回自己。
```

## Customize

如果你想让 skill 更容易被自动召回，可以编辑 `walden-life-reset/SKILL.md` 开头的 `description`，加入你自己或目标用户常说的话。

例如：

```text
我最近心很乱
我想重新开始
我不想再这么忙
我不知道自己正在变成谁
```

## Notes

- 本 skill 基于《瓦尔登湖》的思想框架进行蒸馏和转化，不包含原书全文。
- 它不是心理咨询、医疗诊断、法律建议或财务建议。
- 如果你要公开分发，请避免加入受版权保护的译文全文或出版物 PDF。

## License

MIT


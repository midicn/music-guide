---
id: scene-game-demo
site: home
cat: SCENE
title: 游戏 Demo 音频
title_en: Audio for a Game Demo
summary: 游戏要的是可循环、可触发、可打断的素材，不是一首成品
summary_en: A game needs assets that loop, trigger and interrupt, not a finished track
level: page
tags: [游戏音频, 循环, 引擎, 交付]
tags_en: [game audio, loops, engine, delivery]
alias: [游戏配乐, demo 音频, game demo audio]
order: 3
sources:
  - 本页为场景导航，链接目标为已发布条目（2026-10-31 核对）
updated: 2026-10-31
---

::: zh
demo 阶段最常见的返工，是音乐进引擎时循环点不对、名字对不上。

## 这活要交什么

一套能被引擎直接用掉的资产：探索、战斗、菜单各一到两段，外加几个音效。**每一段都要能无缝循环、能被事件打断、能在两秒内淡出。** 不是一首三分钟的作品。

## 三步走

1. 先列资产表：每段用在哪、多长、循环点在第几小节、和哪段能互相切换。
2. 做分层循环：鼓、和声、旋律分开导出，同长度、同起点，程序才能按战斗强度加减层。
3. 按引擎约定整理命名、采样率与响度余量，让程序不用回来问你。

## 用到的页面

- [游戏音频导论](https://prod.midicn.com/game-audio-introduction/) —— 先分清"素材系统"和"一首曲子"的区别。
- [交互与自适应音乐](https://prod.midicn.com/interactive-adaptive-music/) —— 分层、分支与参数化，决定你导几轨。
- [AI 与游戏音频](https://ai.midicn.com/ai-for-game-audio/) —— 生成工具能出 loop，但循环点仍要人核。
- [交付给引擎](https://ai.midicn.com/delivering-to-engine/) —— 采样率、循环点、响度、命名，四项错一项就返工。
- [音源分离](https://prod.midicn.com/source-separation/) —— 只有成品没有分层时，这是补救而不是方案。

## 验收标准

- 每段循环连续播放三遍无爆音、无断点、无电平跳变。
- 所有资产 48 kHz、同起点、命名符合引擎约定，切换点在 100 ms 内完成。
- 音乐总线留 6 dB 余量给音效，整体响度按 demo 混音而非发行母带处理。
:::

::: en
The most underrated rework in a demo build happens when the programmer wires your music into the engine and finds broken loop points and mismatched names.

## What this job delivers

A set of assets the engine can consume directly: one or two pieces each for exploration, combat and menus, plus a few sound effects. **Every piece must loop seamlessly, respond to events and fade out within two seconds.** Not a three-minute track.

## Three steps

1. Write the asset sheet first: where each piece plays, how long, which bar the loop starts at, and what it can crossfade to.
2. Build layered loops: export drums, harmony and melody separately at the same length and start point so the engine can add and remove layers with combat intensity.
3. Follow the engine's naming, sample rate and headroom conventions so no one has to come back and ask.

## Pages you will use

- [Game audio introduction](https://prod.midicn.com/game-audio-introduction/) — start with the difference between an asset system and a track.
- [Interactive and adaptive music](https://prod.midicn.com/interactive-adaptive-music/) — layers, branches and parameters decide how many files you export.
- [AI for game audio](https://ai.midicn.com/ai-for-game-audio/) — generators produce loops, but a human still checks the loop point.
- [Delivering to the engine](https://ai.midicn.com/delivering-to-engine/) — sample rate, loop points, loudness and naming; one wrong means a redo.
- [Source separation](https://prod.midicn.com/source-separation/) — if you only have a finished mix, this is a rescue, not a plan.

## Acceptance criteria

- Each loop plays three times continuously with no click, gap or level jump.
- All assets are 48 kHz, share a start point, follow the naming convention, and switch within 100 ms.
- Music bus leaves 6 dB of headroom for effects, and loudness follows the demo mix rather than a release master.
:::

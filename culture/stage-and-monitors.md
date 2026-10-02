---
id: culture/stage-and-monitors
site: home
cat: C6
title: 舞台与监听：一场演出怎么「通」起来
title_en: Stage and Monitors — How a Show Gets Wired
summary: 音乐家听的和观众听的，是两个不同的东西
summary_en: What musicians hear and what the audience hears are two different things
level: standard
tags: [演出工业, 监听, 工程]
tags_en: [live industry, monitors, engineering]
alias: [监听, 返听, 调音, monitor, foldback]
order: 118
links:
  - "[[concept:stage-experience]]"
  - "[[instrument:organ]]"
instances:
  - abcmisc-000709 | 一首婚礼进行曲的三个移调版本 —— 同一旋律在三个调上，乐队要靠监听知道自己该在哪个调 | Three transposed versions of a wedding march — same melody in three keys; the band needs monitors to know which key they are in
  - abcmisc-000637 | 一首婚礼圆舞曲 —— 婚礼上常有两组人轮流上场，监听切换必须是自动的 | A wedding hora — at weddings two groups take turns, so monitor changes must be automatic
  - giantmidi-001081 | 奥涅格的一首对位与众赞歌 —— 声部多的时候，每一组的监听必须只送该听的 | Honegger's Fugue et choral — with many parts, each group's monitor must carry only what it needs
sources:
  - 本文为舞台监听工作流程的通识性介绍；具体设备配置、信号链与工程规范不在本文范围
  - 涉及的曲目均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
「排练时大家都听得见，一上台就听不见」——这是每个乐队都遇到过的。**原因不是设备坏了，是台上和台下听的本来就是两个不同的东西。**

## 台上听到的是什么

舞台上音乐家需要听的，按重要性排：

1. **自己** —— 最优先。必须清楚到能判断自己的音准与时值；
2. **和声/节奏组** —— 决定跟不跟得上；
3. **主旋律或领唱** —— 决定在哪个调、什么时候进；
4. **其他** —— 视曲目而定。

上面第一个实例是最直接的证据：**同一支婚礼进行曲有三个移调版本**，乐队必须靠监听（或调音声部）确认自己在哪个调上。**这在排练里靠看一眼就能解决，在台上只能靠监听。**

## 返听的三种常见做法

- **入耳式（in-ear）** —— 只听到自己那一份，最干净，但要提前调好；
- **耳返** —— 一个挂在耳朵后面的小盒子；
- **舞台返听音箱** —— 传统做法，音量可控范围大但会串音。

**入耳式的代价是失去了"环境"**：你听不见观众席、听不见厅堂、也听不见自己漏掉的东西——**它把所有上下文都拿掉了，只给你需要的。**

## 调音是一条链，不是混音台

一场演出的信号链大致是：

**话筒/拾音 → 通道条（前置放大） → 混音台 → 分总线 → 处理 → 主扩 + 监听**

关键在于**分总线**这一步：

- 每一路被分到"给观众的总线"和"给舞台的总线"；
- **两条总线可以完全独立**。

这就是本站[现场扩声](../live-sound/)那篇说的：前区要什么和台上要什么，经常相反。**它不是冲突，是两个独立的目标。**

## 一场演出怎么"通"起来

现场工程的核心工作不是调音，是**在排练里把不确定性消掉**：

1. **标记（marking）** —— 每次进出的位置；
2. **谈话段与演奏段交替**时要能自动切换（上面第二个实例那种"两组人轮流上场"的场合最需要这个）；
3. **对讲** —— 让工程师能即时告诉台上"再一遍"；
4. **备份** —— 麦克风失效时的预案。

上面第三个实例说的就是这个需求的规模：**声部多的时候，每一组的监听必须只送该听的东西** —— 声部越多，监听分组的复杂度越高。

## 排练是监听的真正考场

一个常见经验：**排练时监听不好，演出时一定会出问题。**

- 排练时不戴返听 → 台上就没法依赖它；
- 台上第一次调返听 → 等于在演出中做调试。

**监听要在排练时就固定下来，演出中不再改结构，只改音量。** 这是现场技术的一条硬规矩。

## 听一听：一个"只送该听的"的示意

下面这段是三小节。**想象第一位演奏者只听到高音声部，第二位只听到低声部**（各自返听），而观众听到两者合起来。**三个不同的听觉现实，同一个演出。**

```audiolab
{"type":"scale","notes":["C4","G4","C5","G4","C4","E4","G4","C5"],"label":"同一个演出，三个不同的听觉现实","label_en":"One performance, three different listening realities","hint":"想象第一组只听到高音、第二组只听到低音、观众听到全部","hint_en":"Imagine group one hearing only the top line, group two only the bottom, the audience both"}
```

## 下一步

- 台上的心理体验：[[concept:stage-experience|舞台经验]]。
- 紧张的影响：[[concept:performance-anxiety|演奏紧张]]。
- 观众那一侧：[现场扩声](../live-sound/)。
- 两个世界的差别：[现场与录音棚](../live-vs-studio/)。
:::

::: en
"In rehearsal everyone can hear; on stage nobody can" — every band hits this. **It is not broken equipment: what is on stage and what is in the hall are genuinely two different things.**

## What is audible on stage

What musicians need to hear, in order of priority:

1. **Themselves** — top priority, clear enough to judge their own intonation and timing;
2. **Harmony/rhythm section** — determines whether they stay together;
3. **Lead line or singer** — determines the key and when to enter;
4. **Everything else** — depending on the piece.

The first example is the most direct evidence: **the same wedding march exists in three transposed versions**, and the band needs monitors (or a shouted key) to know which one they are playing. **In rehearsal a glance settles it; on stage only monitors can.**

## Three common ways of monitoring

- **In-ear** — you hear only your own mix, cleanest, but pre-configured;
- **Earphones** — a small box worn behind the ear;
- **Stage wedges** — the traditional approach, wider level control but they bleed into each other.

**The cost of in-ears is losing "environment"**: you no longer hear the audience, the hall, or what you dropped. **It removes all context and gives you only what you need.**

## The signal chain, not the console

A show's signal chain runs roughly:

**mic/pickup → channel strip (preamp) → console → busses → processing → main PA + monitors**

The crucial step is **the bussing**:

- each channel is routed to a "to audience" bus and a "to stage" bus;
- **the two buses can be entirely independent**.

This is what the site's piece on [live sound](../live-sound/) refers to: what the front of house wants and what the stage wants are frequently opposite. **It is not a conflict; it is two separate goals.**

## How a show gets "wired"

The engineer's core job is not mixing — it is **removing uncertainty during rehearsal**:

1. **Marking** — the position of every entry and exit;
2. **Automatic switching** between spoken and playing sections (most needed in the second example's case, "two groups taking turns");
3. **Talkback** — so the engineer can say "again, please" instantly;
4. **Redundancy** — a plan for when a microphone dies.

The third example shows the scale of this requirement: **with many parts, each group's monitor must carry only what it needs** — the more parts, the more monitor grouping complexity.

## Rehearsal is the real test of monitors

A rule of thumb: **if monitors are bad in rehearsal, they will fail in the show.**

- Rehearsing without in-ears → on stage there is nothing to rely on;
- Setting up in-ears for the first time on stage → that is debugging during a performance.

**Fix the monitoring in rehearsal; during the show change only levels, never the structure.** This is a hard rule of live engineering.

## Listen: "only what you need to hear"

Below are three bars. **Imagine the first player hearing only the top line, the second hearing only the bottom line** (each on their own monitor), while the audience hears both. **Three different listening realities, one performance.**

```audiolab
{"type":"scale","notes":["C4","G4","C5","G4","C4","E4","G4","C5"],"label":"One performance, three different listening realities","label_en":"One performance, three different listening realities","hint":"Imagine group one hearing only the top line, group two only the bottom, the audience both","hint_en":"Imagine group one hearing only the top line, group two only the bottom, the audience both"}
```

## Next

- The psychological side of being on stage: [[concept:stage-experience|Stage experience]].
- The effect of tension: [[concept:performance-anxiety|Performance anxiety]].
- The audience side: [live sound](../live-sound/).
- Two different worlds: [live versus studio](../live-vs-studio/).
:::


---
id: culture/live-sound
site: home
cat: C6
title: 现场扩声：声音是怎么被送到你耳边的
title_en: Live Sound — How Sound Gets to Your Ears
summary: 扩声不是把声音放大，是补上乐器做不到的那几件事
summary_en: Reinforcement is not amplification; it fixes what instruments cannot do
level: standard
tags: [演出工业, 扩声, 工程]
tags_en: [live industry, sound reinforcement, engineering]
alias: [扩声, 音响, PA, 调音台, sound reinforcement, PA]
order: 112
links:
  - "[[concept:dynamics]]"
  - "[[concept:sound]]"
instances:
  - abcmisc-000709 | 一首东欧犹太社群的婚礼进行曲 —— 婚礼乐队通常自带声学，不需要电声 | A Jewish wedding march — a wedding band usually generates enough sound acoustically, with no electronics
  - m21-002673 | 一首苏格兰的哑剧 reels —— 舞台上的喜剧节奏必须让最后一排也听得见清点 | A Scottish pantomime reel — comic rhythm on stage must reach the back row clearly
  - pdmx-000656 | 一部圣诞清唱剧 —— 合唱团的自然音量常常不够，需要声学与电声配合 | A Christmas oratorio — a choir's natural volume often falls short and needs acoustic and electric help together
sources:
  - 本文为现场扩声原理的通识性介绍；具体设备型号、场地声学测量与工程规范不在本文范围
  - 涉及的曲目均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
「扩声」这个词容易让人以为是「把声音变大」。**实际上，扩声做的四件事里只有一件是变大。**

## 扩声真正解决的四件事

### 1. 可懂度（最主要）

人声和复杂织体在小厅里可能**听不清内容**。上面第三例那种清唱剧就是典型：合唱团自然音量不足以让每个字送到后排。

**这是扩声最不可替代的功能** —— 它不是为了"更震撼"，是为了**听得清**。

### 2. 覆盖均匀

自然声有个硬伤：**离声源近的人听得太响，远的人听得太小**。

上面第一例那种婚礼进行曲就说明了反例：如果乐队现场够响，电声往往**只会破坏它** —— 加上电声之后近处更炸、远处照样听不清。**很多场合的正确决定是不加。**

### 3. 补齐平衡

现场有天然的平衡问题：

- 打击乐太抢（因为瞬态强、位置靠前）；
- 人声被乐队盖住；
- 某些乐器在扩声系统里几乎听不见。

**扩声在这里做的是"调音"而不是"放大"** —— 压掉抢的，抬起弱的。

### 4. 处理"听不到的部分"

有些成分几乎无法在厅堂里被听见，需要电声系统专门送：

- 舞台脚灯区；
- 低音的极低频段（管风琴、打击乐的低频在自然声里传不远）；
- 观众席后排的清晰度。

## 一个反直觉的原则：少即是多

现场扩声最常见的失败**不是不够响，是加太多**。

理由是可测的：**每增加一路扬声器，就往空间里多注入一份声压和混响激励。**

- 一支麦 + 两只音箱 + 房间混响 → 清楚；
- 四支定向麦 + 十二只音箱 → **每个听众听到的是四条不同声音的叠加，混响被重复激励**，听起来更浑。

**声学上"多点覆盖"听着更稳，实际会更糊。** 这是很多人直觉会搞反的地方。

## 台上台下是两个系统

这一点是现场工程的核心，也是最容易被观众误解的：

- **观众听到的**（front of house）—— 目标是所有人听得舒服；
- **台上听到的**（stage / monitors）—— 目标是表演者听到**自己该听的**。

**这两个信号经常是相反的。** 一个音量很大的贝斯手在台上需要监听里把他的低频**压小**，否则他听不清自己唱的旋律；而前区观众可能需要低频被**抬起来**才能感受到节奏。

**所以现场调音不是"把声音调好"，是"把两个不同的听觉现实都安排好"。**

## 听一听：同一个信号覆盖变化的听感

下面这段音阶是同一个东西，但它同时被想象成两种情况：一次只送到你耳朵（清晰），一次通过多条路径叠加（变糊）。**这就是"多点覆盖"的代价。**

```audiolab
{"type":"scale","notes":["A4","B4","C5","B4","A4","G4","A4"],"label":"同一条声路，两种覆盖方式","label_en":"One signal, two ways of covering a room","hint":"想象它只走一条路径到你耳朵，再想象四条路径叠加——后者会变糊","hint_en":"Imagine it arriving by one path, then by four paths at once — the second is muddier"}
```

## 下一步

- 扩声调的是什么：[[concept:dynamics|力度]]。
- 台上的听觉：[[concept:stage-experience|舞台经验]]。
- 现场与录音棚的差别：[现场与录音棚](../live-vs-studio/)。
- 声音从哪来：[[concept:sound|音色]]。
:::

::: en
The word "reinforcement" invites the reading "making it louder". **In fact only one of the four things it does is louder.**

## The four things reinforcement actually solves

### 1. Intelligibility (the main one)

Voices and dense textures can be **unintelligible** in a small hall. The oratorio in the third example is the case in point: a choir's natural volume may not carry every word to the back row.

**This is the irreplaceable job of reinforcement** — not more impact, but **comprehension**.

### 2. Even coverage

Natural sound has a hard flaw: **people near the source get too much, people far away get too little.**

The wedding march in the first example shows the converse: if a live band is already loud enough, electronics usually **only make it worse** — the front gets more blown out while the back is still unintelligible. **The correct decision in many rooms is to add nothing.**

### 3. Filling in the balance

Live music has inherent balance problems:

- percussion dominates (strong transients, placed up front);
- voices are buried by the band;
- some instruments are nearly inaudible through the system.

**Here reinforcement is "mixing", not "amplifying"** — pulling back what dominates, lifting what is missing.

### 4. Handling what cannot be heard

Some elements barely carry in a hall and need the system specifically:

- under-stage footlight areas;
- the very lowest frequencies (organ and percussion low end simply does not travel in natural sound);
- clarity in the back rows.

## A counter-intuitive principle: less is more

The most common failure of live reinforcement **is not insufficient level, it is too much of it.**

The reason is measurable: **every extra loudspeaker injects another dose of sound pressure and reverberant excitation into the space.**

- One mic, two speakers, room reverb → clear;
- four directional mics, twelve speakers → **each listener hears four overlapping versions and the reverb is driven repeatedly**, which is muddier.

**Acoustically, "more coverage" sounds safer but is actually worse.** This is where intuition tends to get it backwards.

## Front of house and stage are two different systems

This is the core of live engineering and the thing audiences most often misunderstand:

- **Front of house** — what the audience hears, optimised for everyone being comfortable;
- **Stage / monitors** — what the performers hear, optimised for **hearing what they need to hear**.

**The two signals are often opposite.** A loud bassist may need their low frequencies *reduced* in the monitors, or they cannot hear the melody they are singing over it; the front-of-house audience may need the bass *lifted* to feel the pulse.

**So live mixing is not "making the sound good" — it is arranging two different listening realities at once.**

## Listen: the same signal, two coverages

Below is one scale, but it invites you to imagine two situations: arriving at your ears along a single path (clear), versus arriving as four overlapping paths (muddier). **That is the cost of "more coverage".**

```audiolab
{"type":"scale","notes":["A4","B4","C5","B4","A4","G4","A4"],"label":"One signal, two ways of covering a room","label_en":"One signal, two ways of covering a room","hint":"Imagine it arriving by one path, then by four paths at once — the second is muddier","hint_en":"Imagine it arriving by one path, then by four paths at once — the second is muddier"}
```

## Next

- What reinforcement mixes: [[concept:dynamics|Dynamics]].
- The listening situation on stage: [[concept:stage-experience|Stage experience]].
- Live versus studio: [live versus studio](../live-vs-studio/).
- Where the sound comes from: [[concept:sound|Timbre]].
:::


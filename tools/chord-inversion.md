---
id: tools/chord-inversion
site: home
cat: TOOLS
title: 转位：为什么 C 调不一定从 C 开始
title_en: Inversions — Why a Key in C Does Not Always Start on C
summary: 换位置会改变低音，而低音决定了你听到的和弦叫什么
summary_en: Changing position changes the bass, and the bass decides what you call the chord
level: standard
tags: [工具, 听辨, 和弦]
tags_en: [tools, ear training, chord]
alias: [转位, 第一转位, 第二转位, inversion]
order: 210
instances:
  - giantmidi-006222 | 一套音阶琶音与终止式练习 —— 琶音练习里转位是最先要稳的一项 | Scales, Arpeggios, and Cadences — inversions are the first thing to stabilise in arpeggio practice
  - m21-000000 | 巴赫的一首众赞歌 —— 四声部的低音线独立于和弦名之外 | A Bach chorale — the bass line in four-part writing moves independently of the chord name
  - atepp-000238 | 肖斯塔科维奇的一首前奏曲与赋格 —— 赋格的低声部常以转位形式进入 | A Shostakovich Prelude and Fugue — fugue subjects often enter in inversion in the low voice
sources:
  - 本页为转位对比练习的说明；转位命名依据通用乐理记法
  - 实例均标注来源与许可档位，可在线试听；练习用的合成音由浏览器实时生成，非录音
updated: 2026-10-03
---

::: zh
下面三组是**同一个和弦**，只是**最低的那个音换了位置**。这会改变两件事：**你听到的低音**，以及**它在功能上的名字**。

## 同一个和弦，三个位置

**第一种：原位（根音在低音）**

```audiolab
{"type":"chord","root":"C4","quality":"maj","label":"原位 · 根音在最低","label_en":"Root position — root in the bass","hint":"听那个最低的音——它就是和弦的名字","hint_en":"Listen to the lowest note — that is the chord's name","hint2":"低音 = 根音 C","hint2_en":"Bass = root C"}
```

**第二种：第一转位（三音在低音）**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":1,"label":"第一转位 · 三音跑到最低","label_en":"First inversion — the third is now lowest","hint":"三个音一个没变，只是最低的那个换了","hint_en":"Not one note changed; only the lowest one moved","hint2":"低音 = E（原三音），记作 C/E","hint2_en":"Bass = E (the original third), written C/E"}
```

**第三种：第二转位（五音在低音）**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":2,"label":"第二转位 · 五音在最低，听起来最「空」","label_en":"Second inversion — fifth lowest, the most open sound","hint":"低音离根音最远，所以有一种「悬着」的空","hint_en":"The bass lies furthest from the root, giving a suspended emptiness","hint2":"低音 = G（原五音），记作 C/G","hint2_en":"Bass = G (the original fifth), written C/G"}
```

## 关键：和弦的名字由最低音决定

上面三组**音完全一样**（C E G），但它们的**名字不一样**：

- C → **C**
- E 在下 → **C/E**
- G 在下 → **C/G**

**这不是咬文嚼字。** 名字变了，说明**功能变了**：

- **C**（原位）：稳定，是"家"；
- **C/E**（第一转位）：有"要往上走"的倾向（E 是 C 和弦里最高的音）；
- **C/G**（第二转位）：**最不稳定**，G 是五音，它想往上或者往下解决。

**所以一个和弦转位之后，它的"重力"变了。** 这就是为什么同一组音在钢琴上随手一放可能就不好听——**因为你可能随手把它放在了第二转位。**

## 一个能自己验证的动作

1. 只听第一组（原位）的「整体」；
2. 只听第三组（第二转位）的「整体」；
3. **交替快速听**——你会发现第二转位有一种明显的"没站稳"的感觉。

**这个"没站稳"就是 G 这个低音在起作用。** 它离根音最远，没有解决的支撑。

## 转位在音乐里为什么重要

三个实用理由：

1. **低音线条可以独立走** —— 上方和弦不动，低音可以走向任何音，这是四部和声的基础（上面那个众赞歌实例就是这个）；
2. **避免平行五度** —— C 和弦反复用原位会让低音一直在 C–C–C，转位能让低音动起来；
3. **表达情绪** —— 原位稳，转位（尤其第一转位）有一种"悬浮的期待"。

## 一个诚实的说明

上面只演示了三和弦的第一、第二转位。**七和弦有五个转位**，但道理完全一样：**看最低音是哪一个音**。

**所以判断转位的方法只有一条：找到最低的音，看它是和弦里的第几个音。**

## 下一步

- 基础的三种性质：[三和弦的三种性质](../chord-quality/)
- 加一个音：[七和弦](../chord-seventh/)
- 还没解决的那一秒：[挂留与变化音](../chord-suspension/)
- 转位在和声进行里的实际作用：[三个最常见的和声进行](../progression-basic/)
:::

::: en
Below are **the same chord** with only the **lowest note moved**. That changes two things: **the bass you hear**, and **what you may call the chord**.

## One chord, three positions

**One: root position (root in the bass)**

```audiolab
{"type":"chord","root":"C4","quality":"maj","label":"原位 · 根音在最低","label_en":"Root position — root in the bass","hint":"听那个最低的音——它就是和弦的名字","hint_en":"Listen to the lowest note — that is the chord's name","hint2":"低音 = 根音 C","hint2_en":"Bass = root C"}
```

**Two: first inversion (the third is lowest)**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":1,"label":"第一转位 · 三音跑到最低","label_en":"First inversion — the third is now lowest","hint":"三个音一个没变，只是最低的那个换了","hint_en":"Not one note changed; only the lowest one moved","hint2":"低音 = E（原三音），记作 C/E","hint2_en":"Bass = E (the original third), written C/E"}
```

**Three: second inversion (the fifth is lowest)**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":2,"label":"第二转位 · 五音在最低，听起来最「空」","label_en":"Second inversion — fifth lowest, the most open sound","hint":"低音离根音最远，所以有一种「悬着」的空","hint_en":"The bass lies furthest from the root, giving a suspended emptiness","hint2":"低音 = G（原五音），记作 C/G","hint2_en":"Bass = G (the original fifth), written C/G"}
```

## The key: the chord is named after its lowest note

The three groups above contain **exactly the same notes** (C E G), yet they are **not called the same thing**:

- C at the bottom → **C**
- E at the bottom → **C/E**
- G at the bottom → **C/G**

**This is not pedantry.** The name changes because **the function changes**:

- **C** (root position): settled — it is home;
- **C/E** (first inversion): a pull to go up (E is the highest note of a C chord);
- **C/G** (second inversion): **the least stable** — the fifth wants to resolve somewhere.

**So inverting a chord changes its gravity.** That is why the same three notes dropped carelessly onto a keyboard can sound wrong — **you may have put them in second inversion by accident.**

## An action you can verify yourself

1. Listen only to the first (root position) as a block;
2. Then only to the third (second inversion) as a block;
3. **Alternate between them quickly** — second inversion has an unmistakable "unsteady" quality.

**That unsteadiness is the G in the bass at work.** It lies furthest from the root and has nothing supporting it.

## Why inversions matter in music

Three practical reasons:

1. **The bass line can move on its own** — the upper chord stays put while the bass goes anywhere; this is the foundation of four-part writing (the chorale above is exactly this);
2. **They avoid parallel fifths** — a C chord kept in root position puts the bass on C, C, C; inversions let the bass move;
3. **They carry expression** — root position is stable, and inversions (especially the first) produce a sense of suspended expectation.

## An honest note

Only first and second inversion of a triad are demonstrated above. **A seventh chord has five inversions**, but the principle is identical: **look at the lowest note.**

**So there is only one way to identify an inversion: find the lowest note and see which chord member it is.**

## Next

- The three basic qualities: [three chord qualities](../chord-quality/)
- Adding one note: [seventh chords](../chord-seventh/)
- The second before it resolves: [suspensions](../chord-suspension/)
- What inversions do inside a progression: [the three commonest progressions](../progression-basic/)
:::

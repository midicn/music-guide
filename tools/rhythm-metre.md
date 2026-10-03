---
id: tools/rhythm-metre
site: home
cat: TOOLS
title: 拍号：3/4 与 4/4 听起来为什么不一样
title_en: Metre — Why 3/4 and 4/4 Sound Different
summary: 分子告诉你每小节有几拍，分母告诉你以什么为一拍
summary_en: The top number says how many beats; the bottom says what counts as one
level: standard
tags: [工具, 节奏, 拍号]
tags_en: [tools, rhythm, metre]
alias: [拍号, 三四拍, 四四拍, metre, time signature]
order: 214
instances:
  - giantmidi-009379 | 乔普林的一首圆舞曲 —— 圆舞曲的强-弱-弱就是三拍子最直白的体现 | Joplin's Harmony Club Waltz — the strong-weak-weak of a waltz is 3/4 made obvious
  - abcmisc-001160 | 一首东欧传统圆舞曲 —— 民间圆舞曲几乎都用三拍子，因为舞步本身就是三步 | A traditional Eastern European round dance — folk waltzes are nearly always in three, because the dance step is three steps
  - atepp-005648 | 柴可夫斯基《四季》里的八月（收获） —— 收获舞是圆舞曲体裁，3/4 | Tchaikovsky's August (Harvest) from The Seasons — the harvest dance is a waltz movement, in 3/4
sources:
  - 本页为拍号听辨练习的说明；拍号与节奏型记号依据通用乐理记法
  - 实例均标注来源与许可档位，可在线试听；练习用的节拍由浏览器实时生成，非录音
updated: 2026-10-03
---

::: zh
下面两组用的是**完全相同的四个音**，只是拍号不同。**如果你的耳朵够用，你会听出这两组完全不同 —— 而且差别不在音上。**

## 两组对照：同样的音，不同的拍号

**第一组：4/4（四个四分音符）**

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4 · 每拍都一样强","label_en":"4/4 — every beat equally strong","hint":"点「节拍器」先听四拍，然后点「节奏型」听同样的四个音","hint_en":"Play the click first to hear four beats, then play the pattern — the same four notes","cycles":3}
```

**第二组：3/4（三个四分音符，强-弱-弱）**

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":104,"label":"3/4 · 第二三拍变弱","label_en":"3/4 — beats two and three weaken","hint":"同样的三个音，但听起来像三步舞而不是四拍","hint_en":"The same three notes, but they sound like a three-step dance rather than four beats","cycles":3}
```

## 关键：拍号不是"有多少个音"

**这是本页最重要的一句。**

上面第一组有**四个**音，第二组有**三个**音——但拍号的真正区别在于：

- **分子（上面那个数字）**：每小节有几拍；
- **分母（下面那个数字）**：以什么为一个单位（`4` = 四分音符为一拍）。

**所以 4/4 的"四"和 3/4 的"三"指的是拍数，不是音数。** 如果你在 4/4 里放三个音，那三个音里**第一个是强拍、后面两个要弱下来** —— 它其实还是四拍的感觉，只是空了一拍。

## 强拍在哪里，决定了它是什么

一个拍号真正的内容是**哪一拍被强调**：

| 拍号 | 强调的位置 | 典型用途 |
|---|---|---|
| 4/4 | 第 1 拍（次强在第 3 拍） | 几乎所有流行与古典 |
| 3/4 | 第 1 拍（后面两拍弱） | 圆舞曲 |
| 2/4 | 第 1 拍（第二拍弱） | 进行曲、波兰舞曲 |
| 6/8 | 第 1 与第 4 拍 | 三拍子的两半感觉 |

**你听到的第一件工具按钮（节拍器）就是告诉你这件事的**：**第一下那个「叮」（高音）就是强拍。** 听的时候注意听那个区别。

## 一个能自己验证的动作

**把上面第一组（4/4）的 `pattern` 改成 `q q s s`（四个音，两长两短），再听。**

**你会发现它其实比 4 个等长的音更像「舞曲」。** 因为 **节奏型（音的长短）** 和 **拍号（拍子强弱）** 是两套独立的东西：

- 拍号决定"每拍有多强"；
- 节奏型决定"每拍里发生什么"。

**很多人混淆这两者。** 4/4 里完全可以有舞曲式的长短音，3/4 里也可以有全等长的音。

## 一个诚实的边界

本页只演示了 4/4 与 3/4。真实拍号还有：

- **2/4、3/8、6/8、9/8、12/8** 等—— 它们对应不同的分组方式；
- **混合拍号**（比如 5/4、7/8）—— 现代音乐里很常见。

**但判断方法始终是同一个：强拍在哪，弱拍在哪，每小节有几次强拍。**

## 下一步

- 节奏型的花样：[常见节奏型](../rhythm-patterns/)
- 节奏为什么让人想动：[节奏与身体](../../culture/rhythm-and-body/)
- 律动与"扫描"（tapping）：本站[练习研究](../../culture/practice-research/)
- 音程听辨的同类训练：[音程听辨练习](../interval-identification/)
:::

::: en
Below are **exactly the same sounds** under two different time signatures. **If your ears are working, you will hear these as completely different — and the difference is not in the notes.**

## Two passes, same sounds, different metre

**One: 4/4 (four quarter notes)**

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4 · 每拍都一样强","label_en":"4/4 — every beat equally strong","hint":"点「节拍器」先听四拍，然后点「节奏型」听同样的四个音","hint_en":"Play the click first to hear four beats, then play the pattern — the same four notes","cycles":3}
```

**Two: 3/4 (three quarter notes, strong-weak-weak)**

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":104,"label":"3/4 · 第二三拍变弱","label_en":"3/4 — beats two and three weaken","hint":"同样的三个音，但听起来像三步舞而不是四拍","hint_en":"The same three notes, but they sound like a three-step dance rather than four beats","cycles":3}
```

## The key: a time signature is not "how many notes"

**This is the most important sentence on the page.**

The first group has **four** notes and the second has **three** — but the real difference is:

- **the top number**: how many beats per bar;
- **the bottom number**: what unit a beat is (`4` = the quarter note).

**So the "four" in 4/4 and the "three" in 3/4 refer to beats, not notes.** If you put three notes in 4/4, the first is strong and the other two must weaken — it still feels like four beats, with one left empty.

## Where the strong beat falls decides what it is

What a time signature really contains is **which beat is stressed**:

| Signature | Stress | Typical use |
|---|---|---|
| 4/4 | beat 1 (secondary on 3) | nearly all pop and classical music |
| 3/4 | beat 1 (beats 2 and 3 weak) | waltzes |
| 2/4 | beat 1 (beat 2 weak) | marches, polkas |
| 6/8 | beats 1 and 4 | two half-groups of a triple feel |

**The "click" button above is telling you exactly this**: **that first higher "ding" is the strong beat.** Listen for the difference.

## An action you can verify yourself

**Change the `pattern` of the first group to `q q s s`** (four notes, two long and two short) and listen again.

**You will find it sounds more like a "dance" than four even notes.** That is because **rhythm pattern and metre are two independent things**:

- the metre decides **how strong each beat is**;
- the pattern decides **what happens inside each beat**.

**Many people conflate these.** 4/4 can easily carry a dance-like long-short pattern, and 3/4 can carry entirely even notes.

## An honest boundary

Only 4/4 and 3/4 are shown here. Real signatures also include:

- **2/4, 3/8, 6/8, 9/8, 12/8** — each implying a different grouping;
- **irregular metres** (5/4, 7/8) — very common in modern music.

**But the test is always the same: where is the strong beat, where are the weak ones, and how many strong beats per bar.**

## Next

- The range of patterns: [common rhythm patterns](../rhythm-patterns/)
- Why rhythm makes you move: [rhythm and body](../../culture/rhythm-and-body/)
- Keeping time: [practice research](../../culture/practice-research/)
- A parallel kind of drill: [interval identification drill](../interval-identification/)
:::

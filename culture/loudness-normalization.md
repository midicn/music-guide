---
id: culture/loudness-normalization
site: home
cat: C6
title: 流媒体时代的声音：响度归一是什么
title_en: Sound in the Streaming Era — What Loudness Normalisation Does
summary: 你听到的音量差异，有一部分不是音乐家的选择，而是平台的规则
summary_en: Part of the loudness difference you hear is a platform rule, not a musician's choice
level: standard
tags: [演出工业, 响度, 平台]
tags_en: [live industry, loudness, platforms]
alias: [响度归一, 响度, 音量标准化, LUFS, loudness normalisation]
order: 120
links:
  - "[[concept:dynamics]]"
  - "[[concept:sound]]"
instances:
  - pdmx-000369 | 一部安魂曲的记录 —— 老录音的动态范围很大，归一之后高潮会明显变弱 | A recorded Requiem — old recordings have wide dynamics, so after normalisation the climaxes get noticeably weaker
  - pdmx-000656 | 一部圣诞清唱剧 —— 早期录音的响度远低于今天的成品，归一之后整体会明显变响 | A Christmas oratorio — early recordings sit far below modern masters in level, so after normalisation everything gets noticeably louder
  - atepp-000179 | 德彪西的《快乐岛》（现场标记版） —— 现场录音的动态完全不可预测，归一必须处理这种不确定性 | Debussy's L'isle joyeuse, marked as a live take — a live take's dynamics are wholly unpredictable, and normalisation has to cope with that
sources:
  - 本文为响度归一原理的通识性说明；不涉及任何平台的具体规则数值与实施细节
  - 涉及的曲目均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
「这张专辑比那张吵」——**在流媒体上，这句话有一部分不是音乐做的决定，而是平台做的。**

## 问题从哪来

数字时代之前，**不同年代的录音之间响度差异极大**：

- 二十世纪早期的唱片为了在 noisy 设备上听起来清楚，做得特别响；
- 八十年代的母带处理（"响度战争"）让声音更响更响；
- 同时古典录音保留了大量动态，因为现场本身就是那样。

**到流媒体这里就出问题了**：如果按文件原样播放，一首七十年代录音会轻得几乎听不见，而一首九十年代母带会响得压过一切。

## 平台的做法

平台的解法是**自动归一**：播放前分析整个文件的响度，然后统一调整到目标水平。

**于是有了两条后果链：**

### 后果一：老的录音变响了

上面第二例那部清唱剧就是：它在 2026 年的手机上听起来会比当年在音响上响得多。**动态被压扁了**——因为它必须被拉到和其他文件同一档。

### 后果二：新的录音变轻了

反过来，一首已经按新规范做过母带的歌，归一之后会被**调低**，因为它本来就在目标档位之上。

**这就是一个悖论**：**越认真做母带的版本，播放时可能反而越轻。**

## 更麻烦的是：归一不可预测

上面第三例是关键：现场录音的动态是**完全不可预测的**——这一次特别响，下次特别轻。

**归一算法必须先分析文件，而它分析的"响度"是个整体统计值。** 结果是：

- 一首大部分安静、只有一处高潮的现场录音 → **那处高潮会被压得很扁**；
- 一个安静段落后面接爆发的段落 → 归一的判断会显得"很奇怪"。

**这就是为什么现场版在流媒体上往往听起来"动态不对"。** 不是演奏的问题，是统计的问题。

## 一个可验证的现象

拿三张不同年代的唱片，用平台播放，然后：

1. 关掉一切音效处理，只比较**同一首曲子**的不同录音；
2. 注意**安静段落之间的相对差异**；
3. 再注意**最大声的那一下在哪里**。

**你会发现整体音量差不多了，但动态形状被改了。** 归一调的是"整体"，不是"每一处"。

## 实际怎么办

三条务实建议：

1. **听原版**：能找到物理唱片或未归一的文件时，听原版；
2. **注意动态形状**：如果一段音乐本该有一个爆发，而你在流媒体上听不到，那个爆发可能不是没有，是被压掉了；
3. **不要用音量当质量判据**：**响 ≠ 好。** 这条在归一时代尤其重要——因为响度已经不是音乐家的选择了。

## 一个立场

响度归一本身是**善意的技术决定**：它让一个 1900 年的录音能在手机上被听完。

**代价是牺牲了动态，而动态是音乐里最直接表达"这一刻发生了什么"的东西。**

上面第一例那种安魂曲是代价最明显的例子：**归一之后，高潮变成了一种"稍响一点"，而不是一次释放。**

**所以真正的损失不是音质，是"起伏"这个信息本身。**

## 听一听：一个"动态被压平"的示意

下面这段先是一个安静的四音动机，然后突然到一个高八度的音。**想象两种播放：一种保留这个跳（动态完整），一种把全程压到同一响度（你几乎听不到那个跳）。**

```audiolab
{"type":"scale","notes":["C4","E4","G4","C5"],"label":"一次爆发——归一之后会怎样","label_en":"One climax — and what normalisation does to it","hint":"先记住最后那个高八度的音有多突出，再想象把它压平——差别就是这个音的去向","hint_en":"Remember how far the last note stands out, then imagine it levelled — that difference is the whole story"}
```

## 下一步

- 动态是什么：[[concept:dynamics|力度]]。
- 动态在哪里被处理：[混音与母带](../mixing-and-mastering/)。
- 它的上游：[[concept:sound|音色]]。
- 老媒介的另一种答案：[黑胶复兴](../vinyl-revival/)。
:::

::: en
"This album is noisier than that one" — **on streaming services, part of that statement is not the musician's decision but the platform's.**

## Where the problem comes from

Before digital, **level differences between recordings of different eras were enormous**:

- early twentieth-century discs were made very loud so they would cut through noisy playback equipment;
- 1980s mastering (the "loudness war") made things louder and louder;
- while classical recordings kept wide dynamics, because live performance is like that.

**Streaming broke on this**: played as-is, a 1970s recording is nearly inaudible while a 1990s master bulldozes everything else.

## What platforms do

The platform's answer is **automatic normalisation**: analyse the whole file's loudness before playback, then bring it to a target level.

**Two consequence chains follow:**

### Consequence one: old recordings get louder

The oratorio in the second example is exactly this: on a phone in 2026 it is far louder than it ever was on a hi-fi. **Dynamics get squashed**, because it must be pulled to the same level as everything else.

### Consequence two: new recordings get quieter

In reverse, a track mastered to the modern spec is **turned down** by normalisation, because it already sat above the target.

**Here is the paradox: the more carefully a version is mastered, the quieter it may play.** That is not anyone choosing to make it worse; it is what happens when a gain instruction and a signal both act.

## The more awkward part: normalisation is unpredictable

The third example is the key: a live take's dynamics are **wholly unpredictable** — very loud this time, very quiet the next.

**The algorithm must analyse the file first, and what it analyses is a single statistical value.** The result:

- a live recording that is mostly quiet with one climax → **that climax gets flattened**;
- a quiet passage followed by an explosion → the decision looks arbitrary.

**This is why live versions often sound "wrong" dynamically on streaming.** It is not a performance problem. It is a statistics problem.

## A verifiable phenomenon

Take three records from different decades, play them on a streaming service, then:

1. compare **the same piece** across recordings, with all playback effects off;
2. notice **the relative differences between quiet passages**;
3. then notice **where the loudest moment sits**.

**You will find the overall level is now similar, but the shape of the dynamics has changed.** Normalisation adjusts "the whole", not "each moment".

## What to do in practice

Three pragmatic steps:

1. **Listen to originals** — when you can find a physical record or a non-normalised file, listen to that;
2. **Watch the dynamic shape** — if a passage should have an explosion and you cannot hear it on streaming, the explosion may not be missing; it may be compressed out;
3. **Never use loudness as a quality judgement** — **loud is not good.** This matters more in the normalisation era, because loudness is no longer the musician's choice.

## A position

Normalisation is itself a **well-intentioned technical decision**: it lets a 1900 recording be heard to the end on a phone.

**The price is paid in dynamics — and dynamics are the most direct expression of "what is happening at this moment".**

The first example is where that price is most visible: **after normalisation, a climax becomes "a little louder" rather than a release.**

**So the real loss is not fidelity. It is the information contained in "rise and fall" itself.**

## Listen: what a flattened dynamic looks like

Below is first a quiet four-note motif, then a sudden note an octave higher. **Imagine two playbacks: one preserving that jump (dynamics intact), one levelling the whole thing (the jump becomes almost inaudible).**

```audiolab
{"type":"scale","notes":["C4","E4","G4","C5"],"label":"One climax — and what normalisation does to it","label_en":"One climax — and what normalisation does to it","hint":"First remember how far the last note stands out, then imagine it levelled — that difference is the whole story","hint_en":"First remember how far the last note stands out, then imagine it levelled — that difference is the whole story"}
```

## Next

- What dynamics are: [[concept:dynamics|Dynamics]].
- Where dynamics get processed: [mixing and mastering](../mixing-and-mastering/).
- Its upstream layer: [[concept:sound|Timbre]].
- Another answer to the same problem: [the vinyl revival](../vinyl-revival/).
:::


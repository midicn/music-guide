---
id: tools/rhythm-metre
site: home
cat: TOOLS
title: 拍号：3/4 与 4/4 听起来为什么不一样
title_en: Metre — Why 3/4 and 4/4 Sound Different
summary: 区分记谱单位、小节与强弱组织，比较单拍子和复拍子的分组
summary_en: Distinguish note units, measures and accent patterns in simple and compound metres
level: standard
tags: [工具, 节奏, 拍号]
tags_en: [tools, rhythm, metre]
alias: [拍号, 三四拍, 四四拍, metre, time signature]
order: 214
instances:
  - giantmidi-009379 | 节奏练习素材；拍号与重音请结合谱面或事件查看，不由题名推断 | Rhythm practice material; inspect the score or events for metre and accents rather than inferring them from the title
  - abcmisc-001160 | 节奏练习素材；拍号与重音请结合谱面或事件查看，不由题名推断 | Rhythm practice material; inspect the score or events for metre and accents rather than inferring them from the title
  - atepp-005648 | 节奏练习素材；拍号与重音请结合谱面或事件查看，不由题名推断 | Rhythm practice material; inspect the score or events for metre and accents rather than inferring them from the title
sources:
  - https://fundamentalsofmusictheory.umasscreate.net/unit-9/
  - 这一条为拍号听辨练习的说明；拍号与节奏型记号依据通用乐理记法
  - 实例均标注来源与许可档位，可在线试听；练习用的节拍由浏览器实时生成，非录音
updated: 2026-11-03
---

::: zh
两组示例使用同一类合成音和相同速度，分别按四拍和三拍分组。先跟着拍，再找每小节重新开始的位置。

## 同速度的两组对照

### 4/4：四分音符为一拍，每小节四拍

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4 · 四拍一组","label_en":"4/4 — groups of four beats","hint":"先听节拍器，再听四个等长的音；注意每小节起点","hint_en":"Hear the click, then four even notes. Locate the start of each bar.","cycles":3}
```

### 3/4：四分音符为一拍，每小节三拍

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":88,"label":"3/4 · 三拍一组","label_en":"3/4 — groups of three beats","hint":"保持与上一组相同的速度，比较三拍与四拍的分组","hint_en":"Keep the same tempo and compare grouping in three and four.","cycles":3}
```

## 拍数不等于音符数

4/4 一小节可以写一个全音符、四个四分音符，或更多短音与休止；判断小节是否完整，要加时值，不能只数音符。三个四分音符加一个四分休止符仍可组成完整的 4/4 小节。

| 拍号 | 常见分组 | 数拍提示 |
|---|---|---|
| 2/4 | 两个四分拍 | 1、2 |
| 3/4 | 三个四分拍 | 1、2、3 |
| 4/4 | 四个四分拍 | 1、2、3、4 |
| 6/8 | 两个附点四分拍，各分三份 | 1-la-li、2-la-li |

6/8 是常见的复二拍子，不宜只说“每小节六个主要拍”。慢速教学时可以细数六个八分音符，但要继续辨认 3+3 的大拍分组。

## 一次只改一个变量

先保持 BPM 和音色不变，比较上面两组。再在 4/4 中试 `q q e e q`：时值为 1+1+½+½+1，仍占满四拍。相比之下，`q q s s` 只有 2½ 拍，不能当作完整 4/4 小节。

拍号提示拍子的组织，不规定每个实际声音都必须服从固定音量。切分、跨拍延音和演奏重音都可能与基本拍点交错。

## 继续练习

- [常见节奏型](../rhythm-patterns/)
- [节奏与身体](../../culture/rhythm-and-body/)
:::

::: en
The examples use the same kind of synthesized sound and the same tempo, grouped in four and three. Tap along and locate each new bar.

## Compare at one tempo

### 4/4: four quarter-note beats

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4 · 四拍一组","label_en":"4/4 — groups of four beats","hint":"先听节拍器，再听四个等长的音；注意每小节起点","hint_en":"Hear the click, then four even notes. Locate the start of each bar.","cycles":3}
```

### 3/4: three quarter-note beats

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":88,"label":"3/4 · 三拍一组","label_en":"3/4 — groups of three beats","hint":"保持与上一组相同的速度，比较三拍与四拍的分组","hint_en":"Keep the same tempo and compare grouping in three and four.","cycles":3}
```

## Beats are not a note count

A 4/4 bar can contain one whole note, four quarters, or shorter notes and rests. Add durations rather than counting attacks. Three quarters plus a quarter rest also fill the bar.

| Signature | Usual grouping | Count |
|---|---|---|
| 2/4 | two quarter-note beats | 1, 2 |
| 3/4 | three quarter-note beats | 1, 2, 3 |
| 4/4 | four quarter-note beats | 1, 2, 3, 4 |
| 6/8 | two dotted-quarter beats, divided into threes | 1-la-li, 2-la-li |

6/8 is commonly compound duple. Counting six eighth notes slowly can help, but retain the larger 3+3 grouping.

## Change one variable at a time

Keep tempo and timbre constant first. Then try `q q e e q` in 4/4: 1+1+½+½+1 fills four beats. In contrast, `q q s s` totals only 2½ beats.

Metre organizes beats; it does not require every performed sound to follow fixed loudness levels. Syncopation, ties and performance accents can cross the underlying grouping.

## Continue

- [Common rhythm patterns](../rhythm-patterns/)
- [Rhythm and body](../../culture/rhythm-and-body/)
:::

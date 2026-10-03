---
id: tools/timbre-families
site: home
cat: TOOLS
title: 音色家族：八类发声方式各是什么声音
title_en: Timbre Families — Eight Ways of Making a Sound
summary: 音色不是「高低」，是「用什么办法让空气动起来」
summary_en: Timbre is not how high, but how the air is made to move
level: standard
tags: [工具, 音色, 听辨]
tags_en: [tools, timbre, ear training]
alias: [音色, 音色家族, 乐器分类, timbre]
order: 217
instances:
  - giantmidi-001397 | 一首以斯洛伐克民歌为主题的回旋曲 —— 巴洛克与民歌的音色差别是它写作的前提 | Rondos on Slovak Folk Tunes — the timbral gap between Baroque and folk is the premise of the writing
  - giantmidi-003471 | 一首 Tipperary 布鲁斯 —— 布鲁斯的声音本身就是音色与音阶一起定义的 | Tipperary Blues — blues is defined by timbre and scale together, not either alone
  - giantmidi-002964 | 格里格十九首挪威民歌 —— 十九世纪的钢琴写作把"民族音色"当作曲手段 | Grieg's Nineteen Norwegian Folk Tunes — nineteenth-century piano writing treats "national timbre" as a compositional device
sources:
  - 本页为音色家族的听辨演示说明；音色模型命名依据本站合成器的九类模型
  - 实例均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
下面每一组都是**同一段旋律**，但用不同的合成音色演奏。**注意它们的高音与时值完全一样——变的只有「怎么发出来的」。**

## 拉弦类（持续、有揉弦）

```audiolab
{"type":"instrument","synth":"bowed","phrase":["C4","E4","G4","E4"],"label":"拉弦 · 有揉弦的持续音","label_en":"Bowed — a sustained tone with vibrato","hint":"有明显的颤，像有人轻轻按着弦不放","hint_en":"An audible wobble, like a finger resting lightly on a string"}
```

## 拨弦类（起音快、余音短）

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C4","E4","G4","E4"],"label":"拨弦 · 起音快、余音短","label_en":"Plucked — fast attack, short decay","hint":"每个音都是被拨出来的，一碰就走","hint_en":"Each note is 'picked' and leaves immediately"}
```

## 打击类（瞬态最锐）

```audiolab
{"type":"instrument","synth":"struck","phrase":["C4","E4","G4","E4"],"label":"打击 · 像被敲出来的","label_en":"Struck — as if hit rather than bowed","hint":"起音最硬，泛音最明显，像敲击金属或木头","hint_en":"The hardest attack and the clearest overtones, like hitting metal or wood"}
```

## 吹管类（气息持续、略带气声）

```audiolab
{"type":"instrument","synth":"blown","phrase":["C4","E4","G4","E4"],"label":"吹管 · 气息持续","label_en":"Blown — continuous breath","hint":"有一点气的声音，边缘不如弦乐干净","hint_en":"A touch of breath; the edges are less clean than a string"}
```

## 管子类（硬、方、有鼻音）

```audiolab
{"type":"instrument","synth":"reed","phrase":["C4","E4","G4","E4"],"label":"簧管 · 有鼻音的硬边","label_en":"Reed — a hard edge with nasal colour","hint":"共鸣窄而集中，像笛与单簧管之间","hint_en":"Narrow, focused resonance, somewhere between a flute and a clarinet"}
```

## 铜管类（厚、亮、有推进）

```audiolab
{"type":"instrument","synth":"brass","phrase":["C4","E4","G4","E4"],"label":"铜管 · 厚而亮","label_en":"Brass — thick and bright","hint":"起音不慢但很顶，像号的前几秒","hint_en":"A slightly slower but firm attack, like the first seconds of a horn"}
```

## 一个能自己做的动作

1. 只听第一组（拉弦）与第二组（拨弦）；
2. **来回切换**——你会发现同一段旋律，听起来像两件不同的乐器在「说同一句话」；
3. 再听第三组（打击）——**它像是「念」而不是「唱」**。

**这三组之间的差别就是音色。** 而它们的音高、时值、顺序完全一致。

## 音色为什么重要

一个常被忽略的事实：**音色是音乐里最「物理」的一层。**

- 音高、时值、力度这些是**抽象量**，可以在纸上写；
- **音色是物理量** —— 它就是「空气怎么被推动的」那一套物理过程。

**所以音色也是最接近「演奏者本人」的一层。** 换一个人弹同一首曲子，音高可以一样、时值可以一样，**但音色一定不一样**。

## 音色与音高的一个常见误解

「音色 = 高音区」是错的。**音区和音色是两个独立的东西**：

- 三角铁的音很高，但音色是「脆、金属」；
- 大提琴的音很低，但音色可以非常「厚」；
- **同一件乐器的高音区与低音区音色也不同**（所以小提琴听起来和小提琴低沉时完全不是一回事）。

**所以「高音 = 亮」这个说法只是规律，不是定义。**

## 一个诚实的说明

上面六组是**本站合成器的九类模型里的六类**，它们是**近似**，不是真实乐器的采样。

**真实乐器的音色比这些丰富得多** —— 这也是本站乐器站（inst）用真实 MIDI 音源做演示的原因。

**但听辨的原理是一样的**：注意「起音快不快、边缘干净不干净、有没有气声、有没有颤」这四个维度。

## 下一步

- 同一段旋律换音色：[同一段旋律换音色](../instrument-compare/)
- 音色与音高的区别（本站词典）：[音乐词典](https://gloss.midicn.com/)
- 音色与演奏实践：theo 站的[[concept:articulation|演奏法记号]]
- 合成音色的实现细节：[[instrument:erhu|二胡]]（真实音色的对照）
:::

::: en
Every group below is **the same melody** played with a different synthetic timbre. **Note that the pitches and durations are identical — only "how the sound was produced" changes.**

## Bowed (sustained, with vibrato)

```audiolab
{"type":"instrument","synth":"bowed","phrase":["C4","E4","G4","E4"],"label":"拉弦 · 有揉弦的持续音","label_en":"Bowed — a sustained tone with vibrato","hint":"有明显的颤，像有人轻轻按着弦不放","hint_en":"An audible wobble, like a finger resting lightly on a string"}
```

## Plucked (fast attack, short decay)

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C4","E4","G4","E4"],"label":"拨弦 · 起音快、余音短","label_en":"Plucked — fast attack, short decay","hint":"每个音都是被拨出来的，一碰就走","hint_en":"Each note is picked and leaves immediately"}
```

## Struck (the sharpest transient)

```audiolab
{"type":"instrument","synth":"struck","phrase":["C4","E4","G4","E4"],"label":"打击 · 像被敲出来的","label_en":"Struck — as if hit rather than bowed","hint":"起音最硬，泛音最明显，像敲击金属或木头","hint_en":"The hardest attack and the clearest overtones, like hitting metal or wood"}
```

## Blown (continuous breath)

```audiolab
{"type":"instrument","synth":"blown","phrase":["C4","E4","G4","E4"],"label":"吹管 · 气息持续","label_en":"Blown — continuous breath","hint":"有一点气的声音，边缘不如弦乐干净","hint_en":"A touch of breath; the edges are less clean than a string"}
```

## Reed (a hard edge with nasal colour)

```audiolab
{"type":"instrument","synth":"reed","phrase":["C4","E4","G4","E4"],"label":"簧管 · 有鼻音的硬边","label_en":"Reed — a hard edge with nasal colour","hint":"共鸣窄而集中，像笛与单簧管之间","hint_en":"Narrow, focused resonance, somewhere between a flute and a clarinet"}
```

## Brass (thick and bright)

```audiolab
{"type":"instrument","synth":"brass","phrase":["C4","E4","G4","E4"],"label":"铜管 · 厚而亮","label_en":"Brass — thick and bright","hint":"起音不慢但很顶，像号的前几秒","hint_en":"A slightly slower but firm attack, like the first seconds of a horn"}
```

## An action you can verify yourself

1. Listen only to the first (bowed) and the second (plucked);
2. **Switch between them** — the same melody will sound like two different instruments saying the same sentence;
3. Then listen to the third (struck) — **it sounds like "spoken" rather than "sung".**

**The difference between those three is timbre.** Their pitches, durations and order are identical.

## Why timbre matters

An easily missed fact: **timbre is the most "physical" layer in music.**

- pitch, duration and dynamics are **abstract quantities** — they can be written on paper;
- **timbre is physical** — it is literally the mechanics of pushing air.

**So timbre is also the layer closest to the performer.** Two people playing the same piece can match pitch and match duration, and **their timbre will still differ.**

## A common misreading

"Timbre = high register" is simply wrong. **Register and timbre are independent:**

- a triangle is very high, yet its timbre is brittle metal;
- a cello is very low, yet its timbre can be very thick;
- **the same instrument sounds different in its high and low registers** (which is why a violin and a "low violin" are not remotely alike).

**So "high equals bright" is a regularity, not a definition.**

## An honest note

The six groups above are **six of the nine models in this site's synthesiser**, and they are **approximations**, not samples of real instruments.

**Real instruments are far richer than these** — which is why this site's instrument guide (inst) demonstrates with real MIDI sound sources.

**But the principle of listening is the same**: watch the four dimensions — how fast the attack is, how clean the edges are, whether there is breath, whether there is vibrato.

## Next

- Same melody, different timbre: [one melody, several timbres](../instrument-compare/)
- The difference between timbre and register: the [glossary](https://gloss.midicn.com/)
- Articulation as it relates to timbre: [[concept:articulation|Articulation marks]] on theo
- A real-instrument comparison: [[instrument:erhu|Erhu]]
:::

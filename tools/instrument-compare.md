---
id: tools/instrument-compare
site: home
cat: TOOLS
title: 同一段旋律换音色：换的是声音还是音乐
title_en: One Melody, Several Timbres — Changing Sound or Changing Music?
summary: 换音色不改一个音，但听众听到的"是同一首曲子"这件事会松动
summary_en: Changing timbre alters no note, yet "this is the same piece" starts to wobble
level: standard
tags: [工具, 音色, 听辨]
tags_en: [tools, timbre, ear training]
alias: [音色对比, 换音色, timbre comparison]
order: 218
instances:
  - giantmidi-003471 | 一首 Tipperary 布鲁斯 —— 布鲁斯换一把吉他就换了性格，因为音色参与定义风格 | Tipperary Blues — blues changes character with a different guitar, because timbre participates in defining style
  - giantmidi-000422 | 一首为两架钢琴而写的幻想曲 —— 同一台钢琴的两个声部听起来像两件乐器 | Scriabin's Fantasy for two pianos — two hands on one piano sound like two instruments
  - giantmidi-003224 | 一首众赞歌前奏曲 —— 十九世纪的写法把音色本身当作配器材料 | A chorale prelude — nineteenth-century writing treats timbre itself as material
sources:
  - 本页为音色对比的演示说明；所用合成音色模型依据本站合成器的注册列表
  - 实例均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
下面三组是**同一段旋律、同一速度、同一音量**，只换了音色。**你的任务是：判断"它还是同一首曲子吗"。**

## 先做一次实验

**第一组：弦乐（bowed）**

```audiolab
{"type":"instrument","synth":"bowed","phrase":["C4","E4","G4","A4","G4"],"label":"A · 拉弦","label_en":"A — bowed","hint":"记住这四个音的走向","hint_en":"Remember the shape of these four notes"}
```

**第二组：铜管（brass）**

```audiolab
{"type":"instrument","synth":"brass","phrase":["C4","E4","G4","A4","G4"],"label":"B · 铜管","label_en":"B — brass","hint":"同一个旋律，只是厚了、亮了","hint_en":"The same melody, just thicker and brighter"}
```

**第三组：拨弦（plucked）**

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C4","E4","G4","A4","G4"],"label":"C · 拨弦","label_en":"C — plucked","hint":"还是那四个音，但每个音都短了","hint_en":"Still the same four notes, but each one is now short"}
```

## 一个真实存在的现象

**多数人在 A 和 B 之间会说"还是同一首"，在 A 和 C 之间会说"不太一样了"。**

**但注意：C 变的音更多（每个音都变短了），而 B 什么都没变。**

所以你会得到一个反直觉的结论：

> **「听起来像不像同一首」与「变了多少」不成正比。** C 变化更多，却更容易被听成不同的曲子。

## 为什么

**因为音乐识别不只靠音高，还靠"音是怎么被发出的"。**

- **音高序列**告诉你"是什么旋律"；
- **音色与时值**告诉你"这件乐器怎么回事"。

**两者在大脑里是分开的两条线。** 当音色突然改变时，第二条线的变化会**干扰**第一条线的识别——**即使第一条线一个音都没变。**

## 一个能自己验证的动作

1. 只听 A 若干遍，记住旋律；
2. **立刻**切到 C；
3. 再切回 A。

**第 2 步到第 3 步之间，你会花一点时间才想起旋律。** 那个"卡一下"就是干扰本身。

**如果换成 B，第 3 步几乎不卡。** 同样的旋律，B 的干扰小得多。

## 一个可用的经验

**换音色时，"最像原来的"往往不是音色最接近的那个，而是时值最接近的那个。**

- 铜管的起音与持续接近弦乐 → 干扰小；
- 拨弦的每个音都被切断 → 干扰大。

**所以做配器替换时，先看时值，再看音色。** 这是一条实用经验。

## 一个诚实的说明

上面三组都是**合成音色**（本站合成器的模型），它们之间的差别可能比真实乐器之间更大或更小。

**真实乐器之间的音色距离通常更大**（比如长笛与双簧管的差异远大于上面的三组）。但**识别的原理是一样的**：换音色会在"旋律识别"这条线上制造干扰。

## 下一步

- 六类音色的完整对比：[音色家族](../timbre-families/)
- 音色与音高是两件事：[[concept:timbre|音色]]（theo 站）
- 合成器与真实音源的差别：[[instrument:pipa|琵琶]]（inst 站的真实 MIDI 音源）
- 演奏实践里的对应问题：[[concept:articulation|演奏法记号]]（theo 站）
:::

::: en
Below are **the same melody, the same tempo and the same dynamics**, with only the timbre changed. **Your task: decide whether it is still the same piece.**

## Try this first

**A: bowed**

```audiolab
{"type":"instrument","synth":"bowed","phrase":["C4","E4","G4","A4","G4"],"label":"A · 拉弦","label_en":"A — bowed","hint":"记住这四个音的走向","hint_en":"Remember the shape of these four notes"}
```

**B: brass**

```audiolab
{"type":"instrument","synth":"brass","phrase":["C4","E4","G4","A4","G4"],"label":"B · 铜管","label_en":"B — brass","hint":"同一个旋律，只是厚了、亮了","hint_en":"The same melody, just thicker and brighter"}
```

**C: plucked**

```audiolab
{"type":"instrument","synth":"plucked","phrase":["C4","E4","G4","A4","G4"],"label":"C · 拨弦","label_en":"C — plucked","hint":"还是那四个音，但每个音都短了","hint_en":"Still the same four notes, but each one is now short"}
```

## A real phenomenon

**Most people say "still the same piece" between A and B, and "not quite the same" between A and C.**

**But notice: C alters more (every note is shortened), while B alters nothing.**

So you arrive at a counter-intuitive conclusion:

> **"Does this sound like the same piece" is not proportional to "how much changed".** C changes more, yet it is more readily heard as a different piece.

## Why

**Because musical recognition relies on more than pitch — it also relies on "how the note was produced".**

- the **pitch sequence** tells you *what melody* it is;
- the **timbre and duration** tell you *what this instrument is doing*.

**Those are two separate lines in the brain.** When the timbre changes abruptly, the second line **interferes** with recognition on the first — **even though not a single note on the first line has changed.**

## An action you can verify yourself

1. Listen to A several times and memorise the melody;
2. **Switch straight to C**;
3. Switch back to A.

**Between steps 2 and 3 you will take a moment to recall the melody.** That hitch *is* the interference.

**Try B instead of C, and step 3 barely hitches at all.** Same melody, far less interference.

## A usable piece of advice

**When changing timbre, "closest to the original" is often not the closest in timbre but the closest in duration.**

- brass has an attack and sustain close to bowed string → little interference;
- plucked cuts every note off → much more interference.

**So when substituting instrumentation, look at duration first, timbre second.** That is a practical rule.

## An honest note

The three timbres above are all **synthetic** (models from this site's synthesiser), and the distance between them may be either larger or smaller than between real instruments.

**The gap between real instruments is usually wider** (a flute against an oboe differs far more than the three above). But **the principle of recognition is the same**: changing timbre creates interference on the "melody recognition" line.

## Next

- The full six-way comparison: [timbre families](../timbre-families/)
- Timbre and pitch are two different things: [[concept:timbre|Timbre]]
- Synthesiser versus real sound sources: [[instrument:pipa|Pipa]] on inst
- The corresponding question in playing practice: [[concept:articulation|Articulation marks]] on theo
:::

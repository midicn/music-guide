---
id: culture/microphone-basics
site: home
cat: C6
title: 麦克风入门：动圈、电容与指向性
title_en: Microphone Basics — Dynamic, Condenser, Direction
summary: 麦克风真正决定的是"它在听什么"，不是"它有多贵"
summary_en: A microphone really decides what it listens to, not what it costs
level: standard
tags: [演出工业, 录音, 硬件]
tags_en: [live industry, recording, hardware]
alias: [麦克风, 话筒, 指向性, 动圈, 电容, microphone, condenser]
order: 115
links:
  - "[[concept:sound]]"
  - "[[concept:timbre]]"
instances:
  - abcmisc-000709 | 一首婚礼进行曲的旋律记录 —— 现场录音里最常用的选择是动圈，因为舞台声压本来就够 | The melody of a wedding march — in live recording the usual choice is a dynamic mic, because the stage level is already high enough
  - pdmx-000426 | 一部安魂曲的记录 —— 合唱团录音需要电容，因为气声细节在小动圈上会丢 | A recorded Requiem — choral recording needs condensers, because breath detail disappears on small dynamics
  - giantmidi-003561 | 一首钢琴作品 —— 指向性决定了它会收到房间里的哪一部分 | A piano piece — directionality decides which part of the room it hears
sources:
  - 本文为麦克风工作原理的通识性介绍；具体型号参数、测量方法与选购建议不在本文范围
  - 涉及的曲目均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
麦克风入门最重要的一句话：**它不是在"录声音"，它在"听"。** 一支麦克风的性格主要由两件事决定——**听什么**（指向性）与**怎么听**（换能方式）。

## 两条技术路线：动圈与电容

| | 动圈 | 电容 |
|---|---|---|
| 原理 | 音圈在磁场里运动 | 极板间距随声压改变 |
| 灵敏度 | 较低 | 高 |
| 需要幻象供电 | 不需要 | 需要 |
| 高频上限 | 较低 | 高 |
| 抗环境噪声 | 好 | 稍差 |
| 瞬态反应 | 稍慢 | 快 |

**这两条路不是"便宜 vs 贵"，是两种取舍。**

上面第二例说的就是这个取舍的实用后果：**合唱团录音里的气声与细微动态，小动圈会丢**——不是灵敏度低那么简单，而是动圈的高频上限会把它直接滤掉。

## 指向性：麦克风真正在决定的事

比"是什么类型"更重要的一个维度：

- **全指向** —— 收四面八方。适合安静的室内乐器，也**会收到整个房间**；
- **心形** —— 收前方，拒后方。**现场人声与乐器最常用的选择**，因为它拒掉背后的噪声；
- **八字形** —— 收前与后，拒两侧。适合隔着乐器组；
- **枪式** —— 极窄，收一条线。**用于远距离拾音**，也意味着它对距离极敏感。

上面第三例说明的是关键点：**指向性决定了它会收到房间里的哪一部分** —— 所以在录音棚里，"用哪支麦"一半等于"在什么位置、朝哪个方向听"。

## 一个实践上更重要的选择：距离

新手常以为选择麦克风型号最重要。**实际上麦克风与声源的距离影响更大。**

- **近**（10–20 cm）→ 声音直接、饱满、有压迫感，几乎没有房间；
- **中**（40–60 cm）→ 自然，同时带一点房间；
- **远**（2 m 以上）→ 房间感为主，细节丢失。

**同一支麦克风，近距离录出来是"贴着你唱"，远距离录出来是"一个房间里有人唱"。** 这通常比换一支麦克风的影响更大。

上面第一例是反例：**舞台声压本来就够，用动圈、近距离**，结果往往是最稳的选择——因为不需要拾取弱信号。

## 一个容易被忽略的方向性问题

麦克风有朝向。指向性图说的是"哪个方向最敏感"，但**麦克风的"正面"和"听音"的方向不一定与被摄体朝向一致**。

实践后果：**被摄体的朝向决定音色**。同一个音、一支麦克风，人转过来一点，音色就会变——因为改变了它与麦克风的相对角度与反射路径。

## 听一听：一个"距离"造成的差别

下面这段和前面的 audiolab 是同一组音。**想象两次录音：一次几乎贴着（声音饱满、没有空间），一次在几米外（细节变少、房间感明显）。** 你会发现"听起来像什么"，变的是空间而不是音高。

```audiolab
{"type":"scale","notes":["G3","C4","E4","G4","E4","C4"],"label":"同一个音，两种距离","label_en":"One sound, two distances","hint":"想象一次贴近、一次在几米外——变的是空间感，不是音高","hint_en":"Imagine once close and once several metres away — what changes is space, not pitch"}
```

## 下一步

- 它在听什么：[[concept:sound|音色]]。
- 音色由什么决定：[[concept:timbre|音色]]。
- 录音者的工作：[录音棚里的角色](../studio-roles/)。
- 混音：[[concept:dynamics|力度]]。
:::

::: en
The most important sentence in microphone basics: **it is not "recording sound", it is "listening".** A microphone's character is decided by two things — **what it listens to** (directionality) and **how it listens** (transduction).

## Two technical routes: dynamic and condenser

| | Dynamic | Condenser |
|---|---|---|
| Principle | a coil moves in a magnetic field | plate spacing changes with sound pressure |
| Sensitivity | lower | high |
| Needs phantom power | no | yes |
| High-frequency ceiling | lower | high |
| Rejects room noise | well | less well |
| Transient response | slightly slower | fast |

**These are not "cheap vs expensive"; they are two trade-offs.**

The second example shows the practical consequence: **breath and fine dynamics in choral recording disappear on a small dynamic mic** — not simply because sensitivity is lower, but because the dynamic's ceiling filters them out entirely.

## Directionality: what the microphone actually decides

More important than "which type" is another dimension:

- **Omnidirectional** — hears all around. Good for quiet indoor instruments, and **it also hears the whole room**;
- **Cardioid** — front, rejecting the rear. **The default for live voice and instruments**, because it rejects noise behind;
- **Figure-of-eight** — front and rear, rejecting the sides. Good for picking up across a group;
- **Shotgun** — very narrow, a line. **For distant pickup**, which also makes it extremely sensitive to distance.

The third example makes the point: **directionality decides which part of the room it hears.** So in a studio, "which mic" is half the same question as "where is it, facing which way".

## A practically more important choice: distance

Beginners think the microphone model matters most. **In practice distance matters more.**

- **Close** (10–20 cm) → direct, full, immediate, almost no room;
- **Medium** (40–60 cm) → natural, with a little room;
- **Far** (over 2 m) → room-dominated, detail lost.

**The same microphone close sounds "right at your mouth"; far away it sounds "someone singing in a room".** That usually outweighs swapping microphones.

The first example is the converse: **on stage the level is already adequate, so a dynamic mic close to the source is the stable choice** — because nothing weak needs picking up.

## An easily missed directional issue

Microphones have an orientation. A polar pattern says which direction is most sensitive, but **a microphone's "front" does not necessarily coincide with the direction the performer faces**.

The practical consequence: **the performer's facing changes the timbre**. Same note, same microphone, turn the performer slightly and the timbre changes — because the angle and the reflection path to the mic changed.

## Listen: what distance changes

Below is the same set of notes used in the other audiolabs on this site. **Imagine two takes: one almost touching (full, no space), one several metres off (less detail, obvious room).** You will notice that what changes is *space*, not pitch.

```audiolab
{"type":"scale","notes":["G3","C4","E4","G4","E4","C4"],"label":"One sound, two distances","label_en":"One sound, two distances","hint":"Imagine once close and once several metres away — what changes is space, not pitch","hint_en":"Imagine once close and once several metres away — what changes is space, not pitch"}
```

## Next

- What it listens to: [[concept:sound|Timbre]].
- What decides timbre: [[concept:timbre|Timbre]].
- The recorder's job: [roles in the studio](../studio-roles/).
- Mixing: [[concept:dynamics|Dynamics]].
:::


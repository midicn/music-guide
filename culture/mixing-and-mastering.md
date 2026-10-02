---
id: culture/mixing-and-mastering
site: home
cat: C6
title: 混音与母带：成品的最后两道工序
title_en: Mixing and Mastering — The Last Two Steps
summary: 混音是在平衡里做减法，母带是在约束里做妥协
summary_en: Mixing is subtraction inside a balance; mastering is compromise inside constraints
level: standard
tags: [演出工业, 混音, 母带]
tags_en: [live industry, mixing, mastering]
alias: [混音, 母带, 后期, mix, mastering, post-production]
order: 116
links:
  - "[[concept:dynamics]]"
  - "[[concept:sound]]"
instances:
  - giantmidi-000422 | 一首为两架钢琴而写的幻想曲 —— 混音的核心是把两架钢琴摆成一个"空间里的位置" | Scriabin's Fantasy for two pianos — mixing is placing two pianos as positions inside a space
  - atepp-000179 | 德彪西的《快乐岛》（现场标记版） —— 现场录音混音时要保住的是"它是一次发生"，不是把它修得完美 | Debussy's L'isle joyeuse, marked as a live take — in live mixing the job is preserving "this happened", not perfecting it
  - pdmx-001370 | 一部康塔塔的记录 —— 早期录音的动态范围很大，母带的第一个决定往往是"让它到处都能放" | A recorded cantata — early recordings have wide dynamics, and the first mastering decision is usually "make it playable anywhere"
sources:
  - 本文为混音与母带工序职能的通识性介绍；具体技术标准、交付规格与平台要求不在本文范围
  - 涉及的曲目均标注来源与许可档位，可在线试听
updated: 2026-10-03
---

::: zh
混音和母带是两件事，但常被混为一谈。**一句话分开：混音是在平衡里做减法，母带是在约束里做妥协。**

## 混音：把 N 条轨道变成一个整体

混音的输入是多条独立轨道，输出是一个成品。**它做的核心动作有三个：**

### 1. 摆位（space）

每条轨道被放在"某个位置"：

- **左右位置** —— 谁在左谁在右；
- **前后位置** —— 用混响量与高频多少暗示远近；
- **空间大小** —— 用混响暗示"这是大厅还是小房间"。

上面第一例是最清楚的例子：**两架钢琴不是"两个声部"，而是一个空间里的两个位置** —— 谁更近、谁更远、要不要有共同的房间感。

### 2. 平衡（balance）

每个元素在整体里的比重：

- 人声通常在正中且在最前；
- 鼓通常在正中但不抢；
- 贝斯提供低频但不遮盖；
- 和声乐器在最外圈做填充。

**关键在于"整体"是活的** —— 每一秒的平衡都可能不同（激烈段落低频更靠前，静段要退后）。

### 3. 减法

混音最大的工作量是**删掉东西**：

- 太密的频段被打开；
- 相互打架的元素被压；
- 不必要的装饰被移除。

**减法的理由是：多轨合成天然会累积"糊"。** 每一轨都听得清，合起来就都不清楚。

上面第二例是一个原则性提醒：如果是现场录音，混音的职责**不是把它修成完美的录音，而是保住"它是一次发生"** —— 那些小失误是证据，不是缺陷。

## 母带：为别人的设备负责

母带的输入是成品，输出还是成品，但**面向的听众变了**。

它做的判断主要是三条：

### 1. 动态

母带最直接的影响是**动态范围**：

- 压得太多 → 听不出段落起伏；
- 保留太多 → 在嘈杂环境里听不清。

这是一个**没有最优解的取舍**，取决于发布渠道（详见响度归一那篇）。

### 2. 整体响度

同一个作品，为不同渠道做不同的响度版本是常规操作。

### 3. 高频与低频的"落地"

母带会处理在别的设备上会出问题的地方：

- 高频太刺（在手机上尤其明显）；
- 低频太浑（在耳塞上糊成一片）。

上面第三例说的就是这件事：**一个动态范围很大的老录音，母带的第一个决定往往不是审美，而是"让它到处都能放"。** 这是妥协，不是提升。

## 一条实际的界线

初学者常混淆两者的界线。**一个可用的区分：**

- **混音**是**创作决定** —— 它改变音乐本身；
- **母带**是**翻译决定** —— 它把一个确定的音乐变成在各种条件下都成立的版本。

**如果混完之后你还能说"我想换个处理方式"，那是混音；如果只能说"在手机上太刺了"，那是母带。**

## 听一听：一个"减法"示范

下面这段只有五个音。**想象先把它当成十条轨道叠在一起（所有音同时响、彼此遮盖），然后做减法：把低频压掉、把中间的音退后、把落点留在最前。** 减法之后的东西会比"全部一起响"清楚得多。

```audiolab
{"type":"scale","notes":["C4","E4","A4","G4","E4"],"label":"减法前后：同一堆素材","label_en":"Before and after subtraction — same material","hint":"想象所有音一起响（糊），再想象做过减法（清楚）——差别不是音符，是层次","hint_en":"Imagine all notes at once (muddy), then imagine subtraction (clear) — the difference is layers, not notes"}
```

## 下一步

- 最后那道工序：[[concept:dynamics|力度]]。
- 混音调的是什么：[[concept:sound|音色]]。
- 谁在做这些决定：[录音棚里的角色](../studio-roles/)。
- 响度的连锁反应：[响度归一](../loudness-normalization/)。
:::

::: en
Mixing and mastering are two different jobs, though they get treated as one. **One line separates them: mixing is subtraction inside a balance; mastering is compromise inside constraints.**

## Mixing: turning N tracks into one whole

Mixing takes separate tracks in and delivers a finished piece. **It has three core moves:**

### 1. Placement (space)

Each track gets placed at "a position":

- **left/right** — who sits where;
- **front/back** — depth implied by reverb amount and high-frequency content;
- **room size** — reverb implying "hall" versus "small room".

The first example is the clearest case: **two pianos are not "two parts" but two positions inside one space** — which is nearer, which is further, whether they share a room.

### 2. Balance

Each element's share of the whole:

- lead vocal usually centred and forward;
- drums centred but not dominant;
- bass providing low end without masking;
- harmony parts filling the outer edge.

**Crucially, "the whole" is alive** — the balance may differ every second (buses push forward in loud passages, sit back in quiet ones).

### 3. Subtraction

The bulk of mixing work is **removing things**:

- congested frequency ranges are opened up;
- elements fighting each other are pushed down;
- unnecessary decoration is dropped.

**The reason for subtraction: multi-track layering naturally accumulates mud.** If every track is audible, nothing in the mix is.

The second example is a principled reminder: for a live recording, the mixer's job is **not to perfect it but to preserve "this happened"** — the small mistakes are evidence, not defects.

## Mastering: responsible for other people's devices

Mastering takes a finished piece and returns a finished piece, but **the audience changes.**

Its judgements come down to three:

### 1. Dynamics

The most direct effect of mastering is **dynamic range**:

- squashed too far → no sense of shape across sections;
- left too wide → unintelligible in a noisy environment.

This is a trade-off with **no optimal answer**, and it depends on the delivery channel (see the piece on loudness normalisation).

### 2. Overall level

Producing different level versions of the same piece for different channels is routine.

### 3. Making the top and bottom survive

Mastering addresses what breaks elsewhere:

- top end too harsh (especially obvious on a phone);
- bottom too muddy (turns to paste in earbuds).

The third example says exactly this: **for an old recording with wide dynamics, the first mastering decision is often not aesthetic but "make it playable anywhere".** That is compromise, not improvement.

## A usable dividing line

Beginners blur the two. **A practical distinction:**

- **Mixing** is a **creative decision** — it changes the music itself;
- **Mastering** is a **translation decision** — it turns a fixed piece into one that holds up under varying conditions.

**If after the mix you can still say "I'd like to try a different approach", that is mixing. If you can only say "it's harsh on my phone", that is mastering.**

## Listen: a demonstration of subtraction

Below are five notes. **Imagine first treating them as ten tracks stacked (everything sounding at once, masking each other), then subtracting: pushing the low end down, moving the middle notes back, keeping the landing note forward.** What you get after subtraction is far clearer than "everything at once".

```audiolab
{"type":"scale","notes":["C4","E4","A4","G4","E4"],"label":"Before and after subtraction — same material","label_en":"Before and after subtraction — same material","hint":"Imagine all notes at once (muddy), then imagine subtraction (clear) — the difference is layers, not notes","hint_en":"Imagine all notes at once (muddy), then imagine subtraction (clear) — the difference is layers, not notes"}
```

## Next

- The final stage: [[concept:dynamics|Dynamics]].
- What mixing adjusts: [[concept:sound|Timbre]].
- Who makes these decisions: [roles in the studio](../studio-roles/).
- The knock-on effect of level: [loudness normalisation](../loudness-normalization/).
:::


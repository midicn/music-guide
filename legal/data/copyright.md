---
id: legal/data/copyright
site: home
cat: LEGAL
title: 数据版权与来源
title_en: Data Copyright & Sources
summary: 我方不主张曲目权利；逐曲依原许可；含来源清单与剔除台账说明
summary_en: No rights claimed over the works; per-track source licences; sources and removal logs
level: page
tags: [法律, 版权, 数据]
tags_en: [legal, copyright, data]
alias: [数据集版权, Data Copyright, 来源清单]
order: 82
updated: 2026-09-23
sources:
  - 本站自订声明，据实描述数据集的来源与授权状况
  - midicn-lib 逐来源许可台账
---

::: zh
## 一、核心立场

**midicn-lib 是他人作品的聚合，我方不对其中的曲目主张任何权利。**

这一点与 [知识站](https://midicn.com/legal/copyright/)（我们有版权、可开 CC BY 4.0）根本不同。区别在于：

| | 知识站 | **本站（数据站）** |
|---|---|---|
| 内容 | 我们自己写的文字与自绘图表 | **他人以开放许可发布的作品** |
| 我们能否授权 | ✅ 能 | ❌ **不能** |
| 许可来源 | 我方统一授权 CC BY 4.0 | **逐曲依其来源的原有许可** |
| 商业化 | 可（含广告） | **不商业化** |

## 二、作品的许可来自哪里

数据集收录的每一个来源，都有明确的开放许可。主要类型：

| 许可类型 | 含义 | 典型来源 |
|---|---|---|
| **公有领域（PD）** | 著作权已过期或放弃 | 古典作品的老录音转谱、传统曲调 |
| **CC0** | 作者放弃全部权利 | 部分现代贡献者 |
| **CC BY** | 署名即可用 | 多个学术与爱好者项目 |
| **CC BY-SA** | 署名 + 相同方式共享 | 若干乐谱社区 |
| **CC BY-NC-SA** | 非商业 + 相同方式共享 | 特定钢琴数据集 |
| **OPEN / 自定义开放许可** | 各项目自订 | 若干民间音乐档案 |
| **传统音乐整理** | 仅限学习研究 | 民歌与民间音乐集成 |

**每首曲目的具体许可在页面上逐条标注**，并可在数据集的许可台账中查阅。

## 三、我们做的合规工作

"聚合开放内容"这件事本身需要谨慎，我们做了这些：

### 1. 逐来源的许可查证

每个来源在收录前都做了四要素核查：**许可类型 · 是否允许再分发 · 是否要求署名 · 是否限制商业使用**。不满足开放再分发条件的来源，不予收录。

### 2. 剔除疑似现代版权作品

对某个来源中**疑似现代流行/商业作品**的部分，我们做了专门审查并**下架**，留存了逐条台账（来源、曲名、剔除理由）。这类内容的判定依赖目录名与文件路径特征 —— 详见数据集内部的审查记录。

### 3. 逐曲标注与可追溯

- 每一条记录都带**来源标识**与**许可标识**
- 数据集的**来源与变更过程**留有记录
- 元数据"**留空不猜**" —— 不确定的信息宁可空着，不写猜测值

### 4. 不改变原许可

我们**不重新授权**这些作品，**不添加**额外限制，也**不声称**整理工作产生了新权利。

## 四、如果你认为某首作品的权利被侵犯

**我们愿意且会迅速处理。** 这类主张对数据集尤其重要 —— 因为我们无法为每一首作品担保来源合法性。

请提供：

1. **具体的曲目**（页面 URL 或数据集内的标识）
2. **你主张权利的作品**及你在其中的权利性质
3. **你的联系方式**
4. 一段说明：为什么你认为收录超出了其许可范围

提交渠道：[GitHub 仓库](https://github.com/midicn) 提交 issue。

**处理承诺**：

- 收到有效通知后，**先下架、后核实**
- 若核实为误判，说明原因并恢复
- 不要求超出必要范围的信息

## 五、关于整理工作本身

虽然我们不主张作品的著作权，但**数据集的整理成果**（结构化元数据、去重归并、来源标注、分区体系）是我们投入的工作。

我们**不为此设置额外限制** —— 你可以自由使用与再分发这套结构化数据，只需在适当处注明它来自 midicn-lib。这是请求，不是条件。

> 本页为通俗表述，**不构成法律意见**。
:::

::: en
## 1. Our position

**midicn-lib aggregates other people's work, and we claim no rights over the works in it.**

This differs fundamentally from the [knowledge sites](https://midicn.com/en/legal/copyright/), where we hold the copyright and can grant CC BY 4.0:

| | Knowledge sites | **These sites (data)** |
|---|---|---|
| Content | Text and diagrams we wrote/drew | **Works released by others under open licences** |
| Can we license it? | ✅ Yes | ❌ **No** |
| Licence source | Our CC BY 4.0 grant | **Each work's own source licence** |
| Commercial use | Possible (incl. advertising) | **Non-commercial** |

## 2. Where the licences come from

Every source in the dataset is published under an explicit open licence. Main categories:

| Licence | Meaning | Typical sources |
|---|---|---|
| **Public domain** | Copyright expired or waived | Transcriptions of old classical and traditional material |
| **CC0** | All rights waived by the author | Some modern contributors |
| **CC BY** | Attribution only | Various academic and hobbyist projects |
| **CC BY-SA** | Attribution + share-alike | Several score communities |
| **CC BY-NC-SA** | Non-commercial + share-alike | A particular piano dataset |
| **OPEN / custom open terms** | Defined per project | Several folk archives |
| **Traditional-music transcriptions** | Study and research only | Folk-song collections |

**The specific licence is stated per track on each page** and can be checked in the dataset's licence ledger.

## 3. Our compliance work

"Aggregating open content" warrants care. Here is what we do:

### 1. Per-source licence verification

Before inclusion, each source is checked on four points: **licence type · redistribution permitted · attribution required · commercial restrictions**. Sources that do not permit open redistribution are not included.

### 2. Removal of possibly in-copyright works

For material in one source that appeared to be **modern popular/commercial music**, we ran a dedicated review, **removed it**, and kept a line-by-line log (source, title, reason). Detection relies on directory-name and file-path features — see the dataset's internal review records.

### 3. Per-track labelling and traceability

- Every record carries a **source marker** and a **licence marker**
- The dataset's **sources and changes** are recorded
- Metadata follows "**leave blank rather than guess**" — uncertain values stay empty

### 4. Original licences unchanged

We **do not relicense** these works, **add no** extra restrictions, and **claim no** new rights arising from the curation.

## 4. If you believe a work's rights are infringed

**We will act promptly.** Such claims matter especially here, because we cannot vouch for the provenance of every work.

Please provide:

1. **The specific work** (page URL or dataset identifier)
2. **The work you claim**, and the nature of your rights in it
3. **How to reach you**
4. A short explanation of why inclusion exceeds its licence

Submit via an issue on our [GitHub repository](https://github.com/midicn).

**Our commitments:**

- On a valid notice, we **take it down first and verify after**
- If the claim proves mistaken, we explain why and restore it
- We will not ask for more information than necessary

## 5. About the curation itself

While we claim no copyright in the works, the **curation** (structured metadata, de-duplication, source labelling, the zoning system) is work we put in.

We place **no extra restrictions** on it — you may use and redistribute the structured data freely, and we ask only that you note it came from midicn-lib. That is a request, not a condition.

> This page is a plain-language summary, **not legal advice**.
:::

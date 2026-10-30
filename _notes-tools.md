# M0-3 · 互动工具区（`/tools/`）—— 18 条规划

> 内部规划文件，不同步公开仓。
> 规格：`cat: TOOLS` · `level: standard` · 双语（`::: zh` / `::: en`，**H2 对称**）
> 每条至少 1 个交互围栏（`audiolab` 或 `notation`）· 结尾「下一步」链 ≥1 个主题站
> URL 规则：`tools/<slug>.md` → `/tools/<slug>/`；索引页 `tools.md`（`cat: TOOLS`, `level: page`）

---

## 一 · 可用组件的**参数契约**（唯一真源 = `kb-core/kb/assets/kb.js`）

⚠️ **组件参数写错不会报错，会静默回退** → 构建门禁按下列白名单校验。
**动手前先看这张表，不要凭印象写参数。**

| 组件 | 必填 | 可选 | 白名单 / 取值 |
|---|---|---|---|
| `interval` | `a` `b`（音名） | `label` `label_en` `hint` `hint_en` `hint2` | 音名如 `G4` `B♭3` |
| `scale` | `notes`（音名数组） | `gap` `dur` + 四语言字段 | 同上 |
| `chord` | `root`（音名） | `quality` `inversion` + 四语言字段 | **21 个性质**：`maj` `min` `dim` `aug` `sus2` `sus4` `six` `m6` `add9` `madd9` `maj7` `min7` `dom7` `hdim7` `dim7` `dom9` `maj9` `min9` `dom11` `dom13` |
| `progression` | `key`（音名） `degrees`（数组） | `beat` + 四语言字段 | **12 个级数**：`I` `ii` `iii` `IV` `V` `vi` `vii` `i` `iv` `v` `VI` `VII` |
| `rhythm` | — | `sig` `pattern` `bpm` `cycles` + 四语言字段 | 记号：`h`(二分) `q`(四分) `e`(八分) `s`(十六分) `t` `T`(附点)；拍号如 `4/4` `3/4` `6/8` |
| `circle` | — | `label` `label_en` `hint` `hint_en` | 无参数（十二格固定） |
| `instrument` | — | `gm` `drum` `synth` `phrase` + 四语言字段 | ⚠️ `gm` 与 `drum` **互斥** · `gm` = 1–128 或 GM 名字 · `drum` = 27–87 · `synth` = **9 个模型**：`bowed` `plucked` `struck` `blown` `reed` `brass` `vocal` `metal` `perc` |

**四语言字段**：`label` / `label_en` / `hint` / `hint_en`
—— ⚠️ 中英区**共用同一份 JSON**（与 `notation`/`audiolab` 同规则），
英文靠 `*_en` 字段承载，**`hint` 也不能改写**（判据按 `sort_keys` 整段比对）。

**音色降级四级**（组件注释里的真源）：L1 GM 采样（lib 站托管，首载约 28 MB）
→ L2 Web Audio 合成（零素材）→ L3 库中真实曲目（走 `instances`）→ L4 只给谱例文字。
**红线**：只用 lib 站托管 soundfont + 本机实时合成，不嵌任何外部播放器。

---

## 二 · 18 条清单（按组件分组，order 201 起）

### A · 音程听辨（4 条 · `interval`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 1 | 201 | `interval-basics` | 音程是什么：从 1 到 8 度的距离感 | `interval` 逐一演示 8 度 |
| 2 | 202 | `interval-identification` | 音程听辨练习：先听得出，再说得出 | `interval` 多个对照 |
| 3 | 203 | `interval-quality` | 大三度和小三度：一字之差，听不出来就等于没有 | `interval` 对照 C-E / C-E♭ |
| 4 | 204 | `interval-compound` | 复合音程：八度之上那些「大跳」 | `interval` 跨八度对照 |

### B · 音阶与音型（3 条 · `scale`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 5 | 205 | `scale-compare` | 三种最常遇到的大调音阶：听同一首歌的三种色彩 | `scale` × 3（C / G / D） |
| 6 | 206 | `scale-pentatonic` | 五声音阶：为什么它到处都存在 | `scale` 中国五声 + 日本都节 + 印尼五声 |
| 7 | 207 | `scale-modes` | 调式：同一个骨架，七种落脚点 | `scale` × 多调式（用转调体现） |

### C · 和弦（4 条 · `chord`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 8 | 208 | `chord-quality` | 三和弦的三种性质：大、小、减 | `chord` maj / min / dim |
| 9 | 209 | `chord-seventh` | 七和弦：加一个音改变了什么 | `chord` maj7 / dom7 / min7 |
| 10 | 210 | `chord-inversion` | 转位：为什么 C 调不一定用 C 开始 | `chord` 同和弦 0/1/2 转位 |
| 11 | 211 | `chord-suspension` | 挂留与变化音：和弦「还没解决」的那一秒 | `chord` sus2 / sus4 |

### D · 和声进行（2 条 · `progression`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 12 | 212 | `progression-basic` | 三个最常见的进行：为什么它们「一听就熟」 | `progression` I-IV-V / I-V-vi-IV / I-V |
| 13 | 213 | `progression-cadence` | 终止式：一句「话说完」的感觉从哪来 | `progression` V-I / IV-I / V7-I 的对比 |

### E · 节奏（2 条 · `rhythm`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 14 | 214 | `rhythm-metre` | 拍号：3/4 与 4/4 听起来为什么不一样 | `rhythm` 3/4 与 4/4 同型对照 |
| 15 | 215 | `rhythm-patterns` | 常见节奏型：四分、八分、切分与附点 | `rhythm` 多组 pattern |

### F · 调（1 条 · `circle`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 16 | 216 | `circle-of-fifths` | 五度圈：十二个调的地图 | `circle`（点格听主和弦） |

### G · 音色（2 条 · `instrument`）
| # | order | slug | 选题 | 组件用法 |
|---|---|---|---|---|
| 17 | 217 | `timbre-families` | 音色家族：八类发声方式各是什么声音 | `instrument` × 多个 `synth` 模型 |
| 18 | 218 | `instrument-compare` | 同一段旋律换音色：换的是声音还是音乐 | `instrument` 同 `phrase` 换 `gm` |

---

## 三 · 分轮推进（✅ 全部完成 2026-10-03）

- [x] 子批 G1：A 组音程 4 条
- [x] 子批 G2：B 音阶 3 + C 和弦 4 = 7 条
- [x] 子批 G3：D 进行 2 + E 节奏 2 + F 五度圈 1 + G 音色 2 = 7 条
- [x] 索引页 `tools.md` 重写（六组分类 + 使用建议 + 边界说明）
- [x] 构建 + 七关 + 冒烟八套 + 9 站预检 → 推送 → 线上全量复核

**上线结果**：128 条目 · 52 个交互块 · 18 个工具页全 200 · `:::` 残留 0
内容仓 `016ad5e0` · 站点仓 `08d72cc7` · Actions `37083157640` success

---

## 五 · 写工具的实测教训（本批踩到的）

1. ⚠️ **工具条目也要求 ≥3 instances**（`level: standard` 的硬要求）——
   实例的定位是「用这个工具能去听的真实曲目」，对应四级降级的 L3 层。
   **检索思路**：按主题搜不到"音程/和声"类曲目，要按**曲目形态**搜
   （轮唱/赋格 → 音程；众赞歌 → 和声；jig/reel → 节奏）。
2. ⚠️ **`instrument` 组件没有 `label2` / `hint2` 参数** —— 写了会渲染出多余 span。
   组件的四个语言字段只有 `label` / `label_en` / `hint` / `hint_en`。
3. ⚠️ **JSON 值内部不能有任何裸双引号**（包括中文里用来表意的 `"` `"`）。
   本轮 12 处踩到，**正则的成对匹配在 JSON 上不可靠**（嵌套引号会让 `re.sub` 错位，
   贪心删引号也会因语义变化而失败）——最后靠「逐行定位 + 精确字符串替换」解决。
4. ⚠️ **`circle-of-fifths` 页起初没写 audiolab 围栏** → gate6 判红
   「level=standard 但没有任何听辨件」。**交互工具页本身就该有那个可点的组件**，
   别只写"上面有个圈"而不真的放围栏。
5. ⚠️ **`check_language.py` 的 `EN_BLOCK` 正则 `[a-z_]+` 漏了带数字的键**
   （`hint2` / `hint2_en`）→ JSON 里的英文被误判成"中文区英文串味"。已修为 `[a-z][a-z0-9_]*`。

---

## 六 · 内容设计上的一个可复用写法

C 组（和弦）与 D 组（进行）证明一件事：**工具页最有效的写法是「一个可操作的判断」而不是「概念综述」**。

具体做法：**每一页落在一句可执行的判断上**，然后用组件演示它。
例：
- 三和弦 →「区别只在中间那个音的距离」
- 七和弦 →「加的那个音不是装饰，它改变了功能」
- 终止式 →「不是停在主和弦，是两个音同时到达」
- 挂留 →「挂留音不是和弦音，这就是张力」

**每条都有一个"你要能做出的判断"，而不是"你要知道的知识点"。**


---

## 四 · 写作要点（承自批 2 的经验）

1. **每条只教一件事**，落点是一个可操作的判断，不是概念综述（批 2 C5 的写法）。
2. **实例优先取「可自验的实证」**：批 2 靠数据集里同曲名多版本证明了「稳定分歧」，
   工具区同理 —— 能让读者**点一下就看到差异**的实例最有效。
3. **`label` / `hint` 是纯文本位**：禁半角双引号（破坏 JSON），中文用「」不用 " "。
4. **`note` 类字段 ≤120 字**：长了另建段落，别往 JSON 里塞散文（K-34）。
5. **工具条目最容易犯的错是"组件行为说错"** —— 组件按钮的实际行为
   （如 `interval` 的"合起来"是同时发声而非先后）必须写对，
   **写完自己点一遍产物**（K-26）。
6. **索引页链接层级**：工具条目在 `/tools/<slug>/`，互相链接写 `../<slug>/`。

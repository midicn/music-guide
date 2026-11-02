---
id: tools/scale-pentatonic
site: home
cat: TOOLS
title: 五声音阶：为什么它到处都存在
title_en: Pentatonic — Why It Turns Up Everywhere
summary: 比较三组五声音列，按相邻音程判断是否包含半音
summary_en: Compare three five-note collections and check their intervals for semitones
level: standard
tags: [工具, 听辨, 音阶]
tags_en: [tools, ear training, scale]
alias: [五声音阶, 五声, 中国五声, pentatonic]
order: 206
instances:
  - thesession-003947 | 旋律观察素材；是否五声须逐音检查，不能由题名或地域判断 | Melody study material; count the actual pitches rather than inferring a pentatonic collection from title or region
  - giantmidi-003907 | 旋律观察素材；是否五声须逐音检查，不能由题名或地域判断 | Melody study material; count the actual pitches rather than inferring a pentatonic collection from title or region
  - essen-004468 | 旋律观察素材；是否五声须逐音检查，不能由题名或地域判断 | Melody study material; count the actual pitches rather than inferring a pentatonic collection from title or region
sources:
  - 这一条为五声音阶的对比练习说明；音阶结构依据通用乐理记法
  - 实例均标注来源与许可档位，可在线试听；练习用的合成音由浏览器实时生成，非录音
updated: 2026-11-03
---

::: zh
五声音阶的共同点是在一个八度内使用五个不同音级；它们不必具有相同的音程结构。下面用十二平均律合成音比较三组音列，不把这些近似演示当作某一地区调律的实测录音。

## 三组音列，逐步数距离

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"无半音五声：C–D–E–G–A","label_en":"Anhemitonic pentatonic: C–D–E–G–A","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

```audiolab
{"type":"scale","notes":["C4","Db4","F4","G4","Bb4","C5"],"label":"含半音五声：C–D♭–F–G–B♭","label_en":"Pentatonic with a semitone: C–D♭–F–G–B♭","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

```audiolab
{"type":"scale","notes":["C4","D4","F4","G4","Bb4","C5"],"label":"另一组无半音五声：C–D–F–G–B♭","label_en":"Another anhemitonic set: C–D–F–G–B♭","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

| 音列 | 从低音数到高八度的半音步数 | 有无相邻半音 |
|---|---|---|
| C–D–E–G–A–C | 2、2、3、2、3 | 无 |
| C–D♭–F–G–B♭–C | 1、4、2、3、2 | 有 |
| C–D–F–G–B♭–C | 2、3、2、3、2 | 无 |

第三组含全音和小三度，并非每一步都是全音。第二组也说明“五声”不等于“没有半音”。中国传统五声调式、不同日本音阶与印尼乐器的调律需要分别讨论，不能给这三组平均律音列随意贴同一个地域标签。

## 音少不等于没有张力

张力还受同时发声的和弦、低音、音区、重音与句法影响。无半音五声在某些和声环境里容易连接，但不是任何音都能无条件落在任何和弦上；它也不意味着旋律表现力较低。

## 可以自己做的比较

只把第二组的 D♭ 改为 D，其他音不动，比较头两音的距离。随后保持音列不变，只改变重复的中心音。这样分别检验“间距”和“落脚点”，比用“东方、神秘、明亮”等标签猜文化来源更可靠。

## 下一步

- [调式与落脚点](../scale-modes/)
- [音阶对比](../scale-compare/)
:::

::: en
Pentatonic means five distinct pitch classes per octave; it does not specify one interval pattern. These synthesized examples use twelve-tone equal temperament, not measured tunings from a particular regional tradition.

## Count the intervals

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"无半音五声：C–D–E–G–A","label_en":"Anhemitonic pentatonic: C–D–E–G–A","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

```audiolab
{"type":"scale","notes":["C4","Db4","F4","G4","Bb4","C5"],"label":"含半音五声：C–D♭–F–G–B♭","label_en":"Pentatonic with a semitone: C–D♭–F–G–B♭","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

```audiolab
{"type":"scale","notes":["C4","D4","F4","G4","Bb4","C5"],"label":"另一组无半音五声：C–D–F–G–B♭","label_en":"Another anhemitonic set: C–D–F–G–B♭","hint":"听相邻两音的距离，再数回到高八度的最后一步","hint_en":"Hear adjacent intervals, including the final step to the octave."}
```

| Collection | Semitone steps through the octave | Adjacent semitone? |
|---|---|---|
| C–D–E–G–A–C | 2, 2, 3, 2, 3 | No |
| C–D♭–F–G–B♭–C | 1, 4, 2, 3, 2 | Yes |
| C–D–F–G–B♭–C | 2, 3, 2, 3, 2 | No |

The third set mixes whole tones and minor thirds, not whole tones alone. The second disproves the claim that all pentatonics lack semitones. Chinese pentatonic modes, Japanese scales and Indonesian tunings need their own cultural and tuning context; these three equal-tempered sets do not establish regional identity.

## Fewer notes do not remove tension

Harmony, bass, register, accent and phrasing also affect tension. A collection without semitones is not automatically compatible with every chord, nor does it have less expressive potential.

## Compare one variable

Change only D♭ to D in the second set and compare the opening interval. Next keep the pitches but repeat a different centre. This separates spacing from tonal focus instead of guessing cultural origins from mood labels.

## Next

- [Modes and tonal focus](../scale-modes/)
- [Scale comparisons](../scale-compare/)
:::

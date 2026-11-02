---

id: culture/loudness-normalization
site: home
cat: C6
title: 流媒体时代的声音：响度归一是什么
title_en: Sound in the Streaming Era — What Loudness Normalisation Does
summary: 区分播放增益、动态压缩与响度测量，按实际平台和交付要求核对
summary_en: Distinguish playback gain, dynamic compression and loudness measurement against actual delivery requirements
level: standard
tags: [演出工业, 响度, 平台]
tags_en: [live industry, loudness, platforms]
alias: [响度归一, 响度, 音量标准化, LUFS, loudness normalisation]
order: 120
links:
  - "[[concept:dynamics]]"
  - "[[concept:sound]]"
example_mode: references
example_basis: 本文讨论录音响度或厅堂声场，MIDI 不含原录音的响度与房间脉冲响应，不能作为这些物理性质的实测证据。
sources:
  - https://support.spotify.com/au/artists/article/loudness-normalization/
  - https://tech.ebu.ch/docs/r/r128.pdf
updated: 2026-11-03

---



::: zh
响度归一用于减小节目之间的整体响度差异。它与压缩、限制和自动改变每一处音量不是同一个操作。

## 先区分两种处理

| 操作 | 改变什么 | 判断方法 |
|---|---|---|
| 整体增益调整 | 整段同时升高或降低 | 安静与响亮段落间的相对差异保留 |
| 动态压缩或限制 | 按阈值与时间参数改变部分信号 | 峰值、包络或局部相对电平可能改变 |

如果整段只增加相同的分贝数，高潮与弱段的分贝差不会因此变小。不能把“播放时整体变响”直接说成“动态被压平”。向上增益若碰到峰值上限，平台可能限制提升量或使用限制器；具体取决于服务、模式和播放条件。

## 平台目标不等于通用母带标准

节目响度与真峰值衡量的不是同一件事。广播建议、流媒体设置与交付规格也不应混成一个数字。Spotify 的官方说明可用于核对其当前行为，EBU R128 则说明节目响度与峰值控制的不同角色；不要把某个平台的设置当成所有作品的创作目标。

## 怎样比较才有意义

1. 使用同一个真实音频文件；关闭其他均衡、音效和自动音量功能。
2. 记录归一设置及播放模式，匹配比较时的听感响度，避免“更响就是更好”的偏差。
3. 对照同一处弱段与高潮；需要定量判断时，查看节目响度、真峰值和动态范围测量，而不是只凭年代或题名推断。

MIDI 记录音符、力度和控制事件，不是原演出录音。本站的 MIDI 试听不能证明某张老唱片的响度、母带处理或平台归一效果，因此本页使用资料说明，不附作此用途的 MIDI 实例。

## 下一步

- [[concept:dynamics|力度与动态]]
- [话筒与录音入口](../microphone-basics/)
:::

::: en
Loudness normalization reduces overall level differences between programmes. It is distinct from compression, limiting and continuous automatic volume control.

## Gain versus dynamics

A constant gain change moves quiet and loud passages together, preserving their relative level difference. Compression or limiting may change peaks and envelopes. Raising an entire recording does not, by itself, flatten its dynamics. When upward gain encounters a peak ceiling, a service may restrict the boost or apply limiting; behavior depends on its playback mode and implementation.

## Do not mix delivery targets

Programme loudness and true peak describe different properties. Broadcast recommendations, streaming settings and delivery specifications are not interchangeable. Spotify documents its current service behavior; EBU R128 distinguishes programme loudness from peak control. Neither should be turned into a universal artistic target.

## A useful comparison

Use the same real audio file. Disable unrelated processing, note the normalization mode and match listening loudness when comparing quality. Inspect corresponding quiet and loud passages. For quantitative claims, measure programme loudness, true peak and dynamic range rather than inferring them from recording dates or titles.

MIDI events are not the original audio recording. This site's MIDI playback cannot demonstrate an old recording's mastering or a platform's normalization behavior; this page therefore uses reference material rather than misleading MIDI examples.

## Next

- [[concept:dynamics|Dynamics]]
- [Microphone basics](../microphone-basics/)
:::

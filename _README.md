# home 站 · 内容目录

> 下划线前缀的文件不参与构建与校验。

## 结构（2026-09-28 更新）

```
content/
  start.md            新手入门索引页（/start/）
  start/<slug>.md     入门引导条目（30 条，/start/<slug>/）
  legal/**            法律页（7 条，/legal/**）
  tools.md            互动工具页（/tools/）
```

## 写作约定（本站特有）

- 入门引导（`start/**`）：`level: standard` · `cat: S1`–`S6`（内部键）·
  每条必须有「下一步 / Next」段落，**链向至少 2 个主题站**（优先 theo / inst 的已写实体）。
- 许可优先级 C1 > C2 > C3；C3 实例需在 why 里写明理由。
- 每条实例 ≥3 个（`track-id | 中文理由 | English reason` 三段式）。
- 规格见 `kb-core/kb/schema.md` 与 `plans/M0-门户与词典.md`。

构建：`py kb-core/kb/build_kb.py --site home`
预检：`py kb-core/kb/kb_preflight.py --site home`

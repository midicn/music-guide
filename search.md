---
id: search
site: home
cat: SEARCH
title: 站内检索
title_en: Search
summary: 在全部知识站里按标题、摘要与别名查找条目。
summary_en: Search every knowledge site by title, summary and alias.
level: page
tags: [检索, 搜索]
tags_en: [search]
alias: [搜索, 检索, search]
order: 2
sources:
  - 索引由构建脚本从各站 front-matter 生成，不收录曲目库数据
updated: 2026-10-30
---

::: zh
输入一个词，检索 7 个知识站的标题、摘要与别名。结果直接跳到条目页，不在本页展开。

<form class="v3-quiz" data-search data-index="../search-index.json">
  <label class="v3-opt" for="q"><input id="q" type="search" name="q" placeholder="例如：属七和弦、巴洛克、压缩器、Suno" autocomplete="off" style="flex:1;border:0;background:transparent;color:inherit;font:inherit;padding:.4rem"></label>
  <p><button class="v6-btn primary" type="submit">检索</button></p>
</form>

<ul class="kb-list" data-search-results aria-live="polite"></ul>

## 检索不到时

- 换更短的关键词，或换成英文别名（如 `counterpoint`）。
- 词典站按术语组织，概念类问题优先在那里找。
- 工具与模型档案在「音频与音乐制作」和「AI 做音乐」两站。
:::

::: en
Type a word to search titles, summaries and aliases across the seven knowledge sites. Results link straight to the entry page.

<form class="v3-quiz" data-search data-index="../search-index.json">
  <label class="v3-opt" for="q-en"><input id="q-en" type="search" name="q" placeholder="e.g. dominant seventh, baroque, compressor, Suno" autocomplete="off" style="flex:1;border:0;background:transparent;color:inherit;font:inherit;padding:.4rem"></label>
  <p><button class="v6-btn primary" type="submit">Search</button></p>
</form>

<ul class="kb-list" data-search-results aria-live="polite"></ul>

## When nothing matches

- Use a shorter word, or try the other language's term.
- Concept questions are usually answered best on the glossary site.
- Tool and model profiles live on the production and AI sites.
:::

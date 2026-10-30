---
id: diagnose
site: home
cat: QUIZ
title: 三题定位
title_en: Three Questions
summary: 三个问题，不收集任何数据，只在本机算出两条入口
summary_en: Three questions, no data collected, computed on your own device into two entry points
level: page
tags: [问诊, 导航]
tags_en: [quiz, navigation]
alias: [问诊, 测一测, 从哪开始, where to start, quiz]
order: 1
updated: 2026-10-30
---

::: zh
三题，不收集任何数据，只在本机计算：选完点按钮，页面直接给出两条入口。

<form class="v3-quiz" data-quiz data-empty="请先选第一题。">
  <fieldset>
    <legend>1 · 你现在最想做什么？</legend>
    <label class="v3-opt"><input type="radio" name="q1" value="听懂音乐" data-href="../path-listen/" data-title="听懂音乐：从结构和体裁开始">听懂音乐</label>
    <label class="v3-opt"><input type="radio" name="q1" value="学一件乐器" data-href="../path-instrument/" data-title="学一件乐器：从选琴到第一首完整的曲子">学一件乐器</label>
    <label class="v3-opt"><input type="radio" name="q1" value="写一首歌" data-href="../path-write/" data-title="写一首歌：从一句动机到能发的 Demo">写一首歌</label>
    <label class="v3-opt"><input type="radio" name="q1" value="给视频或游戏配乐" data-href="../path-score/" data-title="配乐：按画面和情绪曲线工作">给视频或游戏配乐</label>
    <label class="v3-opt"><input type="radio" name="q1" value="用 AI 做音乐" data-href="../path-ai/" data-title="用 AI 做音乐：从工具地图到交付">用 AI 做音乐</label>
    <label class="v3-opt"><input type="radio" name="q1" value="修复、混音与交付" data-href="../path-finish/" data-title="修复、混音与交付：最后一公里">修复、混音与交付</label>
  </fieldset>
  <fieldset>
    <legend>2 · 你现在会什么？</legend>
    <label class="v3-opt"><input type="radio" name="q2" value="零基础" data-href="../level-zero/" data-title="零基础：先建立听觉词汇">零基础：没有乐器经验，也读不懂谱</label>
    <label class="v3-opt"><input type="radio" name="q2" value="会一点乐器" data-href="../level-instrument/" data-title="会一点乐器：把手上的功夫接上乐理">会一点乐器：能弹几首，看得懂简单谱</label>
    <label class="v3-opt"><input type="radio" name="q2" value="能写歌或编曲" data-href="../level-writer/" data-title="能写歌或编曲：补混音判断与交付">能写歌或编曲：有作品，混音不稳</label>
    <label class="v3-opt"><input type="radio" name="q2" value="职业或半职业" data-href="../level-pro/" data-title="职业或半职业：把交付变成流程">职业或半职业：靠音乐接活</label>
  </fieldset>
  <fieldset>
    <legend>3 · 你每周能投入多少时间？</legend>
    <label class="v3-opt"><input type="radio" name="q3" value="1 小时以内">1 小时以内：每周两次，每次二十分钟</label>
    <label class="v3-opt"><input type="radio" name="q3" value="3–5 小时">3–5 小时：每周三四次</label>
    <label class="v3-opt"><input type="radio" name="q3" value="10 小时以上">10 小时以上：几乎每天</label>
  </fieldset>
  <p><button class="v6-btn primary" type="submit">看推荐路径</button></p>
  <div class="v3-result" aria-live="polite"></div>
</form>

第三题不改变推荐结果，只提醒你按自己的排期读：每周一小时的清单，不要照抄每周十小时的。
:::

::: en
Three questions, no data collected, computed on your own device: pick your answers, press the button, and the page gives you two entry points.

<form class="v3-quiz" data-quiz data-empty="Start with question one.">
  <fieldset>
    <legend>1 · What do you most want to do now?</legend>
    <label class="v3-opt"><input type="radio" name="q1" value="Understand music" data-href="../path-listen/" data-title="Understanding music: start from form and genre">Understand the music I hear</label>
    <label class="v3-opt"><input type="radio" name="q1" value="Learn an instrument" data-href="../path-instrument/" data-title="Learning an instrument: from choosing one to a first complete piece">Learn an instrument</label>
    <label class="v3-opt"><input type="radio" name="q1" value="Write a song" data-href="../path-write/" data-title="Writing a song: from one idea to a demo you can send">Write a song</label>
    <label class="v3-opt"><input type="radio" name="q1" value="Score video or games" data-href="../path-score/" data-title="Scoring: working to picture and emotional arc">Score for video or games</label>
    <label class="v3-opt"><input type="radio" name="q1" value="Make music with AI" data-href="../path-ai/" data-title="Making music with AI: from the tool map to delivery">Make music with AI</label>
    <label class="v3-opt"><input type="radio" name="q1" value="Repair, mix and deliver" data-href="../path-finish/" data-title="Repair, mix and deliver: the last mile">Repair, mix or deliver</label>
  </fieldset>
  <fieldset>
    <legend>2 · What can you do now?</legend>
    <label class="v3-opt"><input type="radio" name="q2" value="Starting from zero" data-href="../level-zero/" data-title="Starting from zero: build a listening vocabulary first">Starting from zero: no instrument, no notation</label>
    <label class="v3-opt"><input type="radio" name="q2" value="I play a little" data-href="../level-instrument/" data-title="I play a little: connect the hands to theory">I play a little: a few pieces, simple notation</label>
    <label class="v3-opt"><input type="radio" name="q2" value="I write or arrange" data-href="../level-writer/" data-title="I write or arrange: fix mixing judgement and delivery">I write or arrange: finished songs, unsteady mixes</label>
    <label class="v3-opt"><input type="radio" name="q2" value="Professional or semi-pro" data-href="../level-pro/" data-title="Professional or semi-pro: turn delivery into a process">Professional or semi-pro: I take paid work</label>
  </fieldset>
  <fieldset>
    <legend>3 · How much time can you give each week?</legend>
    <label class="v3-opt"><input type="radio" name="q3" value="Under 1 hour">Under 1 hour: twice a week, twenty minutes each</label>
    <label class="v3-opt"><input type="radio" name="q3" value="3–5 hours">3–5 hours: three or four sessions a week</label>
    <label class="v3-opt"><input type="radio" name="q3" value="Over 10 hours">Over 10 hours: nearly every day</label>
  </fieldset>
  <p><button class="v6-btn primary" type="submit">Show my path</button></p>
  <div class="v3-result" aria-live="polite"></div>
</form>

The third answer does not change the recommendation; it is a reminder to read at your own pace. Do not copy a ten-hour-a-week list onto a one-hour week.
:::

---
permalink: /recent-works/
title: "Blog"
title_zh: "随笔"
author_profile: true
---

<div class="en-only" markdown="1">

My research interest covers a wide range of fields, including rechargeable ion batteries, hydrogen, fuel cells and water electrolysis, the systematic design and modification of energy storage facilities, and AI4Energy. Besides scientific research, I also like to jot down my random thoughts from time to time.

You can find some of my formatted notes on my personal WeChat official account by scanning the following QR codes:

<div style="display: flex; flex-wrap: wrap; gap: 1.5em; align-items: center;">
  <img src="/images/wechat-qr-1.jpg" alt="WeChat official account QR code" style="width: 160px; max-width: 45%;" />
  <img src="/images/wechat-qr-2.jpg" alt="WeChat official account" style="width: 160px; max-width: 45%;" />
</div>

</div>

<div class="zh-only" markdown="1">

我的研究兴趣涵盖多个领域，包括可充电离子电池、氢燃料电池与电解水、储能器件与系统的设计与优化，以及AI4Energy。除了科研之外，我也喜欢偶尔写一些随笔。

你可以扫描以下二维码，在我的个人微信公众号上查看一些随笔和研究笔记：

<div style="display: flex; flex-wrap: wrap; gap: 1.5em; align-items: center;">
  <img src="/images/wechat-qr-1.jpg" alt="微信公众号二维码" style="width: 160px; max-width: 45%;" />
  <img src="/images/wechat-qr-2.jpg" alt="微信公众号" style="width: 160px; max-width: 45%;" />
</div>

</div>

<h2 class="en-only">Articles</h2>
<h2 class="zh-only">文章</h2>

<div class="news-grid">
{% for post in site.posts %}
  {% assign item = post %}
  {% include news-card.html %}
{% endfor %}
</div>

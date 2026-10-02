---
permalink: /resources/
title: "Resources"
title_zh: "资源"
author_profile: true
---

<div class="en-only" markdown="1">

I'll drop things here later — like my experiences of doing research, or software that has helped me a lot.

</div>

<div class="zh-only" markdown="1">

之后我会在这里分享一些科研经验，或是对我帮助很大的软件等工具。

</div>

<h2 class="en-only">Notes & Tutorials</h2>
<h2 class="zh-only">笔记与教程</h2>

<div class="news-grid">
{% for post in site.posts %}
  {% if post.type == 'Note' %}
    {% assign item = post %}
    {% include news-card.html %}
  {% endif %}
{% endfor %}
</div>

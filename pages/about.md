---
layout: page
title: About
description: 代码改变世界
keywords: Darren Chan, 陈驰
comments: true
menu: 关于
permalink: /about/
---

我是陈驰，「国防科技大学」计算机硕士。

喜欢刷题，喜欢折腾，仰慕「编码的艺术」。

坚信勤能补拙，信奉「技术改变世界」。

做人要有梦想，万一实现了呢？

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

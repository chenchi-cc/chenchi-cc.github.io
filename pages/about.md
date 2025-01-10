---
layout: page
title: About
description: 代码改变世界
keywords: Darren Chan, 陈驰
comments: true
menu: 关于
permalink: /about/
---

我是陈驰，计算机硕士研究生。

仰慕「优雅编码的艺术」。

坚信熟能生巧，坚信勤能补拙。

无人扶我青云志，我自踏雪至山巅。

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

---
layout: page
title: About
description: 代码改变世界
keywords: DarrenChan, 陈驰
comments: true
menu: 关于
permalink: /about/
---

我是陈驰，本科「东北大学」，硕士「国防科技大学」，双985计算机专业。

喜欢刷算法题，喜欢折腾技术，仰慕「编码的艺术」。

坚信勤能补拙，坚信和而不同，信奉「技术改变世界」。

做人要有梦想，万一实现了呢？

自勉的三句话：
- 自我价值清晰认知，你的核心卖点是什么？
- 你自己取得的成绩是平台成就的，还是通过能力得来的？
- 得有破圈心态，得成为复合型人才，要有敢于换工作换行业的底气和能力

目标：致力于成为精通大数据、后台开发和算法的全栈架构师

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

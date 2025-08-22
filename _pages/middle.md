---
layout: default
title: "중등 수학"
permalink: /middle/
---

# 중등 수학 공식 & 문제

## 7학년

<ul>
{% assign posts = site.categories.Middle | where:"categories.2","Grade7" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<!-- 8~9학년도 동일하게 추가 -->

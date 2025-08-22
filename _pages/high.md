---
layout: default
title: "고등 수학"
permalink: /high/
---

# 고등 수학 공식 & 문제

## 10학년

<ul>
{% assign posts = site.categories.High | where:"categories.2","Grade10" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<!-- 11~12학년도 동일하게 추가 -->

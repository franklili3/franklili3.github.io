---
layout: page
title: Lilibtc
tagline: 预测超准确 投资不亏损
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {{ post.content | strip_html | truncatewords:10}}
    <br>
    <br>
  {% endfor %}
</ul>


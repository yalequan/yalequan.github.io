---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% comment %} Items come from _data/news.yml (newest first). {% endcomment %}

<ul class="home-news">
{% for item in site.data.news %}
  <li><span class="home-news__date">{{ item.date }}</span><span class="home-news__text">{{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip }}</span></li>
{% endfor %}
</ul>

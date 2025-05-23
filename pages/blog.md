---
layout: page
title: GSC24 The meeting abstracts
cover-img: /assets/img/header.jpg
---

{% include header.html %}

This page will auto update with talk abstracts as they are provided by the speakers. <!-- to "_posts" folder, I think that should be happening below now.-->

## To find abstracts of interest you can use the Search tool by clicking the magnifying glass icon in the top right of this page.


<ui>
  {% for post in site.posts %}
  * {{ post.date | date: "%-d %B %Y" }} - <a href="{{ site.url }}/GigaDB-author-guide/{{ post.url }}">{{ post.title }}</a>
        <br>
  {% endfor %}
</ui>

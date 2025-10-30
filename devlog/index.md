---
layout: home
title: "Devlog"
---

## Welcome to the Devlog

This is where you will find updates on my work on **Book of Dave** and other projects.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

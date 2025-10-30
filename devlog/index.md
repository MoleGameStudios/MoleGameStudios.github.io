---
layout: home
title: "Mole Game Studios Devlog"
---

# Welcome to the Devlog

This is the development blog for Mole Game Studios.  
Here you'll find updates on *Book of Dave* and other projects.

## Latest posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

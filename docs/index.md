---
layout: home
title: Learn AI with Me
---

# Welcome to Learn AI with Me

A comprehensive resource for learning about AI and its applications.

## Latest News

{% for post in site.news limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Recent Blog Posts

{% for post in site.blog limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %} 
---
layout: home
title: Welcome to Learn AI with Me
---

A comprehensive resource for learning about AI and its applications.

## Latest News
{% for post in site.news limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## Recent Blog Posts
{% for post in site.blog limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## About This Project
This site serves as a hub for learning about artificial intelligence and its practical applications. Here you'll find:

* Latest news in AI development
* Blog posts about learning experiences
* Resources and tutorials
* Project documentation and examples 
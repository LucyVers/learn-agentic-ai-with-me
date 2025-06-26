---
layout: home
title: Welcome to Learn Agentic AI with Me
---

Discover the world of Agentic AI - autonomous artificial intelligence systems that can understand, decide, and act independently. This resource focuses on how AI agents can perform tasks, solve problems, and interact with their environment with increasing autonomy.

## Latest News
{% for post in site.news limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## Recent Blog Posts
{% for post in site.blog limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## About This Project
This site is dedicated to exploring and understanding Agentic AI - the next evolution in artificial intelligence. Here you'll find:

* Latest developments in autonomous AI agents
* Practical applications of Agentic AI
* Learning resources and tutorials about AI agents
* Documentation of agent-based AI projects
* Insights into AI autonomy and decision-making
* Real-world examples of AI agents in action 
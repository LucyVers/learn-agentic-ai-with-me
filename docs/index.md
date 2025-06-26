---
layout: home
title: Welcome to Learn Agentic AI with Me
---

<div class="hero-section">
# Discover Agentic AI

Explore the world of autonomous artificial intelligence systems that can understand, decide, and act independently. Learn how AI agents can perform tasks, solve problems, and interact with their environment with increasing autonomy.
</div>

<div class="project-features">
## What We Cover

* 🤖 **Autonomous Agents** - Understanding AI systems that can act independently
* 🧠 **Decision Making** - How AI agents process information and make choices
* 🔄 **Learning & Adaptation** - Systems that improve through experience
* 🤝 **Human-AI Collaboration** - Building effective partnerships with AI agents
* 🛠️ **Practical Applications** - Real-world implementations of Agentic AI
* 🔍 **Latest Research** - Cutting-edge developments in the field
</div>

## Latest News
{% for post in site.news limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## Recent Blog Posts
{% for post in site.blog limit:5 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

<div class="cta-section">
## Join Our Learning Journey

This site is dedicated to exploring and understanding Agentic AI - the next evolution in artificial intelligence. We focus on practical applications, real-world examples, and hands-on learning experiences.

[Learn More About Agentic AI](/about){: .button}</div> 
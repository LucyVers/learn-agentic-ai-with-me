---
layout: home
title: Learn Agentic AI with Me
---

<div class="hero-section">
# Discover the Future of AI

Explore the world of autonomous artificial intelligence systems that can understand, decide, and act independently. Learn how AI agents can perform tasks, solve problems, and interact with their environment with increasing autonomy.
</div>

<div class="project-features">
## What We Cover

* **🤖 Autonomous Agents** - Understanding AI systems that can act independently
* **🧠 Decision Making** - How AI agents process information and make choices
* **🔄 Learning & Adaptation** - Systems that improve through experience
* **🤝 Human-AI Collaboration** - Building effective partnerships with AI agents
* **🛠️ Practical Applications** - Real-world implementations of Agentic AI
* **🔍 Latest Research** - Cutting-edge developments in the field
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
## Start Your Journey

Ready to explore the world of Agentic AI? Join us in understanding and building the future of autonomous AI systems.

[Learn More About Agentic AI](/about){: .button}</div> 
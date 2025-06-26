---
layout: home
title: Learn Agentic AI with Me
---

<div class="hero-section">
# Discover Agentic AI
<div class="subtitle">Your guide to understanding and building autonomous AI systems</div>
</div>

<div class="course-grid">
  <div class="course-card">
    <div class="card-image" style="background-color: #5755A1;">
      <!-- Vi kan lägga till en illustration här senare -->
    </div>
    <div class="card-content">
      <h2>Foundations of Agentic AI</h2>
      <p>Start your journey into the world of autonomous AI agents. Learn the fundamental concepts, principles, and applications of AI systems that can act independently.</p>
      <a href="/about" class="button">Get Started</a>
    </div>
  </div>

  <div class="course-card">
    <div class="card-image" style="background-color: #7B78C7;">
      <!-- Vi kan lägga till en illustration här senare -->
    </div>
    <div class="card-content">
      <h2>Building AI Agents</h2>
      <p>Dive deep into practical implementation of AI agents. Learn how to create, train, and deploy autonomous systems that can interact with their environment.</p>
      <a href="/projects" class="button">Explore Projects</a>
    </div>
  </div>
</div>

<div class="features-section">
## What You'll Learn

* **🤖 Autonomous Agents** - Understanding AI systems that can act independently
* **🧠 Decision Making** - How AI agents process information and make choices
* **🔄 Learning & Adaptation** - Systems that improve through experience
* **🤝 Human-AI Collaboration** - Building effective partnerships with AI agents
* **🛠️ Practical Applications** - Real-world implementations of Agentic AI
* **🔍 Latest Research** - Cutting-edge developments in the field
</div>

<div class="news-section">
## Latest Updates

<div class="content-columns">
  <div class="column">
    <h3>Latest News</h3>
    {% for post in site.news limit:5 %}
    * [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
    {% endfor %}
  </div>

  <div class="column">
    <h3>Recent Blog Posts</h3>
    {% for post in site.blog limit:5 %}
    * [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
    {% endfor %}
  </div>
</div>
</div>

<div class="cta-section">
## Join Our Community

Ready to explore the world of Agentic AI? Start your journey into autonomous AI systems today.

[Get Started Now](/about){: .button .primary-button}
[Browse Resources](/resources){: .button .secondary-button}</div> 
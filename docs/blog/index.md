---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Welcome to our blog about Agentic AI! Here you'll find the latest insights, tutorials, and thoughts on autonomous AI systems.

## Recent Posts

{% for post in site.blog %}
  <article class="post-preview">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p class="post-meta">{{ post.date | date: site.minima.date_format }}</p>
    <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
  </article>
{% endfor %}

---

*Want to contribute to our blog? Check out our [community guidelines]({{ "/community/" | relative_url }}).* 
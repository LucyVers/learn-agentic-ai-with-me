---
layout: default
title: News
permalink: /news/
---

# Latest News

Stay updated with the latest developments in Agentic AI, research breakthroughs, and industry news.

## Recent News

{% for post in site.news %}
  <article class="news-item">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p class="post-meta">{{ post.date | date: site.minima.date_format }}</p>
    <p>{{ post.excerpt | strip_html | truncatewords: 25 }}</p>
  </article>
{% endfor %}

---

*Have news to share? [Contact us]({{ "/about/" | relative_url }}) or check our [community page]({{ "/community/" | relative_url }}).* 
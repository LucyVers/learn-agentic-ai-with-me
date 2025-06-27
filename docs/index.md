---
layout: default
---

<div class="hero-section">
  <div class="content">
    <h1>Explore Agentic AI</h1>
    <p class="subtitle">Your complete guide to understanding and building powerful autonomous AI systems that can act independently and effectively.</p>
    <div class="button-group">
      <a href="{{ site.baseurl }}/#get-started" class="button primary-button">Get Started</a>
      <a href="{{ site.baseurl }}/about" class="button secondary-button">Learn More</a>
    </div>
  </div>
</div>

<div class="course-grid">
  <div class="course-card">
    <div class="card-image">
      <img src="{{ site.baseurl }}/assets/images/ai-robot.svg" alt="AI Robot">
    </div>
    <div class="card-content">
      <h2>Foundations of Agentic AI</h2>
      <p>Start your journey into the world of autonomous AI agents. Learn the fundamental concepts, principles, and applications of AI systems that can act independently.</p>
      <a href="{{ site.baseurl }}/foundations" class="button primary-button">Start Learning</a>
    </div>
  </div>
  
  <div class="course-card">
    <div class="card-image">
      <img src="{{ site.baseurl }}/assets/images/network.svg" alt="Neural Network">
    </div>
    <div class="card-content">
      <h2>Building AI Agents</h2>
      <p>Dive deep into practical implementation of AI agents. Learn how to create, train, and deploy autonomous systems that can interact with their environment.</p>
      <a href="{{ site.baseurl }}/building" class="button primary-button">Explore Projects</a>
    </div>
  </div>
</div>

<div class="features-section">
  <h2>What You'll Learn</h2>
  <div class="features-grid">
    <div class="feature-item">
      <span class="feature-icon">🤖</span>
      <h3>Autonomous Agents</h3>
      <p>Understanding AI systems that can act independently</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🧠</span>
      <h3>Decision Making</h3>
      <p>How AI agents process information and make choices</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">📈</span>
      <h3>Learning & Adaptation</h3>
      <p>Systems that improve through experience</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🤝</span>
      <h3>Human-AI Collaboration</h3>
      <p>Building effective partnerships with AI agents</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🛠️</span>
      <h3>Practical Applications</h3>
      <p>Real-world implementations of Agentic AI</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🔍</span>
      <h3>Latest Research</h3>
      <p>Cutting-edge developments in the field</p>
    </div>
  </div>
</div>

<div class="news-section">
  <h2>Latest Updates</h2>
  <div class="content-columns">
    <div class="column">
      <h3>Latest News</h3>
      {% for post in site.categories.news limit:5 %}
        <div class="post-item">
          <a href="{{ post.url | relative_url }}" class="post-link">{{ post.title }}</a>
          <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
        </div>
      {% endfor %}
    </div>
    
    <div class="column">
      <h3>Recent Blog Posts</h3>
      {% for post in site.categories.blog limit:5 %}
        <div class="post-item">
          <a href="{{ post.url | relative_url }}" class="post-link">{{ post.title }}</a>
          <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
        </div>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cta-section">
  <h2>Join Our Community</h2>
  <p>Ready to explore the world of Agentic AI? Start your journey into autonomous AI systems today.</p>
  <div class="button-group">
    <a href="/get-started" class="button primary-button">Get Started Now</a>
    <a href="/resources" class="button secondary-button">Browse Resources</a>
  </div> 
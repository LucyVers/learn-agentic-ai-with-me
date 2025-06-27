---
layout: default
---

<div class="hero-section">
  <div class="content">
    <h1>Upptäck Agentic AI</h1>
    <p class="subtitle">Din guide till framtidens autonoma AI-system. Lär dig förstå och bygga intelligenta agenter som kan agera självständigt.</p>
    <div class="button-group">
      <a href="#get-started" class="button primary-button">Kom igång</a>
      <a href="/about" class="button secondary-button">Läs mer</a>
    </div>
  </div>
</div>

<div class="course-grid">
  <div class="course-card">
    <div class="card-image">
      <img src="/assets/images/ai-robot.svg" alt="AI Robot">
    </div>
    <div class="card-content">
      <h2>Grunderna i Agentic AI</h2>
      <p>Starta din resa in i världen av autonoma AI-agenter. Lär dig de grundläggande koncepten, principerna och tillämpningarna av AI-system som kan agera självständigt.</p>
      <a href="/foundations" class="button primary-button">Börja lära dig</a>
    </div>
  </div>
  
  <div class="course-card">
    <div class="card-image">
      <img src="/assets/images/network.svg" alt="Neural Network">
    </div>
    <div class="card-content">
      <h2>Bygga AI-agenter</h2>
      <p>Fördjupa dig i praktisk implementering av AI-agenter. Lär dig hur du skapar, tränar och distribuerar autonoma system som kan interagera med sin omgivning.</p>
      <a href="/building" class="button primary-button">Utforska projekt</a>
    </div>
  </div>
</div>

<div class="features-section">
  <h2>Vad du kommer att lära dig</h2>
  <div class="features-grid">
    <div class="feature-item">
      <span class="feature-icon">🤖</span>
      <h3>Autonoma Agenter</h3>
      <p>Förstå AI-system som kan agera självständigt</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🧠</span>
      <h3>Beslutsfattande</h3>
      <p>Hur AI-agenter bearbetar information och fattar beslut</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">📈</span>
      <h3>Lärande & Anpassning</h3>
      <p>System som förbättras genom erfarenhet</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🤝</span>
      <h3>Människa-AI Samarbete</h3>
      <p>Bygga effektiva partnerskap med AI-agenter</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🛠️</span>
      <h3>Praktiska Tillämpningar</h3>
      <p>Verkliga implementeringar av Agentic AI</p>
    </div>
    
    <div class="feature-item">
      <span class="feature-icon">🔍</span>
      <h3>Senaste Forskningen</h3>
      <p>Banbrytande utveckling inom området</p>
    </div>
  </div>
</div>

<div class="news-section">
  <h2>Senaste Uppdateringar</h2>
  <div class="content-columns">
    <div class="column">
      <h3>Senaste Nytt</h3>
      {% for post in site.categories.news limit:5 %}
        <div class="post-item">
          <a href="{{ post.url }}" class="post-link">{{ post.title }}</a>
          <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
        </div>
      {% endfor %}
    </div>
    
    <div class="column">
      <h3>Senaste Blogginläggen</h3>
      {% for post in site.categories.blog limit:5 %}
        <div class="post-item">
          <a href="{{ post.url }}" class="post-link">{{ post.title }}</a>
          <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
        </div>
      {% endfor %}
    </div>
  </div>
</div>

<div class="cta-section">
  <h2>Gå med i vår Community</h2>
  <p>Redo att utforska världen av Agentic AI? Börja din resa in i autonoma AI-system idag.</p>
  <div class="button-group">
    <a href="/get-started" class="button primary-button">Kom igång nu</a>
    <a href="/resources" class="button secondary-button">Utforska resurser</a>
  </div> 
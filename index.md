---
layout: default
title: Technical Writing Portfolio
---

<div class="hero-section">
  <div class="hero-background">
    <div class="hero-content">
      <h1 class="hero-title">Muhamed Javid Hussain</h1>
      <h2 class="hero-subtitle">Senior Technical Writer</h2>
      <p class="hero-description">
        Transforming complex technical concepts into clear, user-friendly documentation
      </p>
    </div>
  </div>
</div>

<div class="categories-section">
  <div class="container">
    <h2 class="section-title">Explore My Work</h2>
    <div class="categories-grid">
      <div class="category-card">
        <div class="category-icon">📖</div>
        <h3>User Guides</h3>
        <p>Step-by-step instructions that help users accomplish their goals with ease and confidence.</p>
        <a href="{{ site.baseurl }}/user-guides/" class="category-link">View User Guides</a>
      </div>
      
      <div class="category-card">
        <div class="category-icon">💻</div>
        <h3>Developer Guides</h3>
        <p>Technical documentation for developers, including API references and integration guides.</p>
        <a href="{{ site.baseurl }}/developer-guides/" class="category-link">View Developer Guides</a>
      </div>
      
      <div class="category-card">
        <div class="category-icon">🧠</div>
        <h3>Knowledge Base</h3>
        <p>Comprehensive articles covering troubleshooting, best practices, and technical insights.</p>
        <a href="{{ site.baseurl }}/knowledge-base/" class="category-link">View Knowledge Base</a>
      </div>
    </div>
  </div>
</div>

<div class="expertise-section">
  <div class="container">
    <h2 class="section-title">Areas of Expertise</h2>
    <div class="expertise-list">
      <div class="expertise-item">
        <h4>User Documentation</h4>
        <p>Creating intuitive guides that make complex software accessible to all users</p>
      </div>
      <div class="expertise-item">
        <h4>API Documentation</h4>
        <p>Comprehensive references that help developers integrate and use APIs effectively</p>
      </div>
      <div class="expertise-item">
        <h4>Software Testing</h4>
        <p>Pre-release testing and functional validation to ensure quality documentation</p>
      </div>
      <div class="expertise-item">
        <h4>Release Notes</h4>
        <p>Clear communication of new features, improvements, and changes in software releases</p>
      </div>
    </div>
  </div>
</div>

<style>
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 80px 0;
  margin-bottom: 60px;
  position: relative;
  overflow: hidden;
}

.hero-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="1"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>');
  opacity: 0.5;
}

.hero-content {
  text-align: center;
  position: relative;
  z-index: 2;
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
}

.hero-title {
  font-size: 3.5rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
}

.hero-subtitle {
  font-size: 1.8rem;
  font-weight: 300;
  margin-bottom: 1rem;
  opacity: 0.9;
}

.hero-description {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  opacity: 0.8;
  line-height: 1.6;
}

.hero-stats {
  display: flex;
  justify-content: center;
  gap: 3rem;
  margin-top: 2rem;
}

.stat {
  text-align: center;
}

.stat-number {
  display: block;
  font-size: 2.5rem;
  font-weight: 700;
  line-height: 1;
}

.stat-label {
  display: block;
  font-size: 0.9rem;
  opacity: 0.8;
  margin-top: 0.5rem;
}

.categories-section {
  padding: 60px 0;
  background: #f8f9fa;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.section-title {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
  color: #333;
}

.categories-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
}

.category-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.category-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.15);
}

.category-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
  display: block;
}

.category-card h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.category-card p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.category-link {
  display: inline-block;
  padding: 0.8rem 1.5rem;
  background: #667eea;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  transition: background 0.3s ease;
}

.category-link:hover {
  background: #5a6fd8;
}

.expertise-section {
  padding: 60px 0;
}

.expertise-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.expertise-item {
  padding: 1.5rem;
  border-left: 4px solid #667eea;
  background: #f8f9fa;
  border-radius: 0 8px 8px 0;
}

.expertise-item h4 {
  color: #333;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}

.expertise-item p {
  color: #666;
  line-height: 1.5;
  margin: 0;
}

@media (max-width: 768px) {
  .hero-title {
    font-size: 2.5rem;
  }
  
  .hero-subtitle {
    font-size: 1.5rem;
  }
  
  .hero-stats {
    flex-direction: column;
    gap: 1.5rem;
  }
  
  .categories-grid {
    grid-template-columns: 1fr;
  }
  
  .section-title {
    font-size: 2rem;
  }
}
</style>

---
layout: page
title: Portfolio
permalink: /portfolio/
---

<div class="portfolio-hero">
  <h1>My Portfolio</h1>
  <p>Explore my collection of technical documentation across different categories</p>
</div>

<div class="portfolio-navigation">
  <button class="nav-btn active" onclick="showCategory('all')">All Work</button>
  <button class="nav-btn" onclick="showCategory('user-guides')">User Guides</button>
  <button class="nav-btn" onclick="showCategory('developer-guides')">Developer Guides</button>
  <button class="nav-btn" onclick="showCategory('knowledge-base')">Knowledge Base</button>
</div>

<div class="portfolio-grid" id="portfolioGrid">
  
  <!-- User Guides Section -->
  <div class="category-section" data-category="user-guides">
    <h2 class="category-title">📖 User Guides</h2>
    <div class="work-grid">
      
      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">📋</div>
        </div>
        <div class="work-info">
          <h3>Getting Started Guide</h3>
          <p>Comprehensive onboarding guide that helps new users understand the platform basics and complete their first tasks successfully.</p>
          <div class="work-tags">
            <span class="tag">User Experience</span>
            <span class="tag">Onboarding</span>
          </div>
          <a href="#" class="work-link">View Guide</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">⚙️</div>
        </div>
        <div class="work-info">
          <h3>Account Setup Tutorial</h3>
          <p>Step-by-step instructions for setting up user accounts, configuring preferences, and managing security settings.</p>
          <div class="work-tags">
            <span class="tag">Setup</span>
            <span class="tag">Security</span>
          </div>
          <a href="#" class="work-link">View Tutorial</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">📊</div>
        </div>
        <div class="work-info">
          <h3>Dashboard User Manual</h3>
          <p>Complete guide to understanding and using dashboard features, including data visualization and reporting tools.</p>
          <div class="work-tags">
            <span class="tag">Dashboard</span>
            <span class="tag">Analytics</span>
          </div>
          <a href="#" class="work-link">View Manual</a>
        </div>
      </div>

    </div>
  </div>

  <!-- Developer Guides Section -->
  <div class="category-section" data-category="developer-guides">
    <h2 class="category-title">💻 Developer Guides</h2>
    <div class="work-grid">
      
      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">🔌</div>
        </div>
        <div class="work-info">
          <h3>REST API Documentation</h3>
          <p>Complete API reference with endpoints, authentication methods, request/response examples, and error handling guidelines.</p>
          <div class="work-tags">
            <span class="tag">API</span>
            <span class="tag">REST</span>
          </div>
          <a href="#" class="work-link">View Documentation</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">📦</div>
        </div>
        <div class="work-info">
          <h3>SDK Integration Guide</h3>
          <p>Comprehensive guide for integrating Software Development Kits, including setup instructions and code examples.</p>
          <div class="work-tags">
            <span class="tag">SDK</span>
            <span class="tag">Integration</span>
          </div>
          <a href="#" class="work-link">View Guide</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">🏗️</div>
        </div>
        <div class="work-info">
          <h3>Architecture Overview</h3>
          <p>Technical documentation explaining system architecture, data flow, and integration patterns for development teams.</p>
          <div class="work-tags">
            <span class="tag">Architecture</span>
            <span class="tag">System Design</span>
          </div>
          <a href="#" class="work-link">View Overview</a>
        </div>
      </div>

    </div>
  </div>

  <!-- Knowledge Base Section -->
  <div class="category-section" data-category="knowledge-base">
    <h2 class="category-title">🧠 Knowledge Base</h2>
    <div class="work-grid">
      
      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">🔧</div>
        </div>
        <div class="work-info">
          <h3>Troubleshooting Guide</h3>
          <p>Common issues and solutions organized by category, with step-by-step resolution procedures and preventive measures.</p>
          <div class="work-tags">
            <span class="tag">Troubleshooting</span>
            <span class="tag">Support</span>
          </div>
          <a href="#" class="work-link">View Guide</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">💡</div>
        </div>
        <div class="work-info">
          <h3>Best Practices Article</h3>
          <p>Collection of industry best practices and recommendations for optimal system performance and user experience.</p>
          <div class="work-tags">
            <span class="tag">Best Practices</span>
            <span class="tag">Performance</span>
          </div>
          <a href="#" class="work-link">View Article</a>
        </div>
      </div>

      <div class="work-item">
        <div class="work-preview">
          <div class="preview-placeholder">❓</div>
        </div>
        <div class="work-info">
          <h3>Frequently Asked Questions</h3>
          <p>Comprehensive FAQ covering the most common user questions with clear, actionable answers and helpful links.</p>
          <div class="work-tags">
            <span class="tag">FAQ</span>
            <span class="tag">Support</span>
          </div>
          <a href="#" class="work-link">View FAQ</a>
        </div>
      </div>

    </div>
  </div>

</div>

<div class="portfolio-footer">
  <h3>Want to See More?</h3>
  <p>These samples represent just a portion of my work. I'd be happy to discuss specific projects or provide additional examples tailored to your needs.</p>
  <a href="{{ site.baseurl }}/contact/" class="contact-btn">Get In Touch</a>
</div>

<script>
function showCategory(category) {
  const sections = document.querySelectorAll('.category-section');
  const buttons = document.querySelectorAll('.nav-btn');
  
  // Remove active class from all buttons
  buttons.forEach(btn => btn.classList.remove('active'));
  
  // Add active class to clicked button
  event.target.classList.add('active');
  
  if (category === 'all') {
    sections.forEach(section => {
      section.style.display = 'block';
    });
  } else {
    sections.forEach(section => {
      if (section.dataset.category === category) {
        section.style.display = 'block';
      } else {
        section.style.display = 'none';
      }
    });
  }
}

// Initialize on page load
document.addEventListener('DOMContentLoaded', function() {
  showCategory('all');
});
</script>

<style>
.portfolio-hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
  padding: 60px 0;
  margin: -20px -20px 40px -20px;
  border-radius: 0 0 20px 20px;
}

.portfolio-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.portfolio-hero p {
  font-size: 1.2rem;
  opacity: 0.9;
}

.portfolio-navigation {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-bottom: 3rem;
  flex-wrap: wrap;
}

.nav-btn {
  background: #f8f9fa;
  border: 2px solid #e9ecef;
  padding: 0.8rem 1.5rem;
  border-radius: 8px;
  cursor: pointer;
  transition: all 0.3s ease;
  font-size: 1rem;
  font-weight: 500;
}

.nav-btn:hover {
  background: #e9ecef;
}

.nav-btn.active {
  background: #667eea;
  color: white;
  border-color: #667eea;
}

.category-section {
  margin-bottom: 4rem;
}

.category-title {
  font-size: 2rem;
  color: #333;
  margin-bottom: 2rem;
  text-align: center;
}

.work-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
}

.work-item {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.work-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.15);
}

.work-preview {
  height: 150px;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  display: flex;
  align-items: center;
  justify-content: center;
}

.preview-placeholder {
  font-size: 3rem;
  opacity: 0.7;
}

.work-info {
  padding: 1.5rem;
}

.work-info h3 {
  color: #333;
  font-size: 1.3rem;
  margin-bottom: 0.8rem;
}

.work-info p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.work-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
}

.tag {
  background: #e3f2fd;
  color: #1976d2;
  padding: 0.3rem 0.8rem;
  border-radius: 15px;
  font-size: 0.8rem;
  font-weight: 500;
}

.work-link {
  display: inline-block;
  background: #667eea;
  color: white;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: background 0.3s ease;
}

.work-link:hover {
  background: #5a6fd8;
}

.portfolio-footer {
  background: #f8f9fa;
  padding: 3rem 2rem;
  text-align: center;
  border-radius: 12px;
  margin-top: 3rem;
}

.portfolio-footer h3 {
  color: #333;
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

.portfolio-footer p {
  color: #666;
  font-size: 1.1rem;
  max-width: 600px;
  margin: 0 auto 2rem auto;
  line-height: 1.6;
}

.contact-btn {
  display: inline-block;
  background: #667eea;
  color: white;
  padding: 1rem 2rem;
  text-decoration: none;
  border-radius: 8px;
  font-size: 1.1rem;
  font-weight: 600;
  transition: all 0.3s ease;
}

.contact-btn:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .portfolio-hero h1 {
    font-size: 2.5rem;
  }
  
  .portfolio-navigation {
    flex-direction: column;
    align-items: center;
  }
  
  .nav-btn {
    width: 200px;
  }
  
  .work-grid {
    grid-template-columns: 1fr;
  }
  
  .category-title {
    font-size: 1.8rem;
  }
}
</style>

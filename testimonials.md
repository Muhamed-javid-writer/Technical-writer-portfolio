---
layout: page
title: Testimonials
permalink: /testimonials/
---

<div class="testimonials-hero">
  <h1>What People Say</h1>
  <p>Feedback from colleagues, clients, and team members I've had the pleasure to work with</p>
</div>

<div class="testimonials-grid">
  
  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        Muhamed's documentation transformed how our users interact with our platform. 
        His clear, step-by-step guides reduced our support tickets by 40% and significantly 
        improved user satisfaction scores. His ability to make complex features accessible 
        is truly exceptional.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">PM</div>
      <div class="author-info">
        <h4>Sarah Johnson</h4>
        <span>Product Manager</span>
        <span class="company">TechCorp Solutions</span>
      </div>
    </div>
  </div>

  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        Working with Muhamed on API documentation was a game-changer. He didn't just 
        document our endpoints—he understood our developers' needs and created examples 
        that actually helped people succeed. Our developer adoption rate increased 
        dramatically after his documentation went live.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">DL</div>
      <div class="author-info">
        <h4>David Lee</h4>
        <span>Development Lead</span>
        <span class="company">API Innovations Inc.</span>
      </div>
    </div>
  </div>

  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        Muhamed has an incredible talent for taking technical jargon and making it 
        understandable for everyone. His user guides are so clear that even our 
        least tech-savvy customers can follow them easily. He's also great at 
        meeting deadlines and collaborating with our team.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">RG</div>
      <div class="author-info">
        <h4>Rachel Garcia</h4>
        <span>Customer Success Manager</span>
        <span class="company">UserFirst Platform</span>
      </div>
    </div>
  </div>

  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        As a fellow technical writer, I have huge respect for Muhamed's work. 
        His approach to information architecture and user experience in documentation 
        is thoughtful and effective. He consistently delivers high-quality content 
        that serves both technical and non-technical audiences.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">MK</div>
      <div class="author-info">
        <h4>Michael Kim</h4>
        <span>Senior Technical Writer</span>
        <span class="company">DocuTech Solutions</span>
      </div>
    </div>
  </div>

  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        Muhamed's pre-release testing and documentation validation saved us countless 
        hours of post-launch support. His attention to detail and ability to think 
        from the user's perspective helped us catch issues before they became problems. 
        He's an invaluable asset to any product team.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">JP</div>
      <div class="author-info">
        <h4>James Patterson</h4>
        <span>QA Director</span>
        <span class="company">Software Systems Ltd.</span>
      </div>
    </div>
  </div>

  <div class="testimonial-card">
    <div class="testimonial-content">
      <div class="quote-icon">"</div>
      <p>
        The knowledge base articles Muhamed created became our most visited help 
        pages. His ability to anticipate user questions and provide comprehensive 
        yet concise answers is remarkable. Our customer satisfaction scores improved 
        significantly after implementing his documentation.
      </p>
    </div>
    <div class="testimonial-author">
      <div class="author-avatar">AS</div>
      <div class="author-info">
        <h4>Amanda Smith</h4>
        <span>Support Team Lead</span>
        <span class="company">HelpDesk Pro</span>
      </div>
    </div>
  </div>

</div>

<div class="testimonials-stats">
  <div class="stat-item">
    <span class="stat-number">40%</span>
    <span class="stat-label">Average Reduction in Support Tickets</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">95%</span>
    <span class="stat-label">Client Satisfaction Rate</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">50+</span>
    <span class="stat-label">Successful Projects Delivered</span>
  </div>
</div>

<div class="testimonials-cta">
  <h3>Ready to Work Together?</h3>
  <p>
    I'd love to help improve your documentation and user experience. 
    Let's discuss how we can make your content more effective and user-friendly.
  </p>
  <div class="cta-buttons">
    <a href="{{ site.baseurl }}/contact/" class="primary-btn">Start a Conversation</a>
    <a href="{{ site.baseurl }}/portfolio/" class="secondary-btn">View My Work</a>
  </div>
</div>

<style>
.testimonials-hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
  padding: 60px 0;
  margin: -20px -20px 40px -20px;
  border-radius: 0 0 20px 20px;
}

.testimonials-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.testimonials-hero p {
  font-size: 1.2rem;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto;
  line-height: 1.6;
}

.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.testimonial-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  position: relative;
}

.testimonial-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 30px rgba(0,0,0,0.15);
}

.testimonial-content {
  margin-bottom: 1.5rem;
  position: relative;
}

.quote-icon {
  font-size: 4rem;
  color: #667eea;
  opacity: 0.3;
  position: absolute;
  top: -1rem;
  left: -0.5rem;
  font-family: serif;
  line-height: 1;
}

.testimonial-content p {
  color: #555;
  line-height: 1.7;
  font-size: 1.1rem;
  margin: 0;
  padding-left: 1rem;
  font-style: italic;
}

.testimonial-author {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding-top: 1rem;
  border-top: 1px solid #eee;
}

.author-avatar {
  width: 50px;
  height: 50px;
  background: #667eea;
  color: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 1.1rem;
}

.author-info h4 {
  margin: 0 0 0.2rem 0;
  color: #333;
  font-size: 1.1rem;
}

.author-info span {
  display: block;
  color: #666;
  font-size: 0.9rem;
}

.company {
  font-weight: 600;
  color: #667eea !important;
}

.testimonials-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  margin: 4rem 0;
  padding: 2rem;
  background: #f8f9fa;
  border-radius: 12px;
}

.stat-item {
  text-align: center;
}

.stat-number {
  display: block;
  font-size: 2.5rem;
  font-weight: 700;
  color: #667eea;
  margin-bottom: 0.5rem;
}

.stat-label {
  color: #666;
  font-size: 0.9rem;
  line-height: 1.4;
}

.testimonials-cta {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  padding: 3rem 2rem;
  text-align: center;
  border-radius: 12px;
  margin-top: 3rem;
}

.testimonials-cta h3 {
  color: #333;
  font-size: 2rem;
  margin-bottom: 1rem;
}

.testimonials-cta p {
  color: #666;
  font-size: 1.1rem;
  max-width: 600px;
  margin: 0 auto 2rem auto;
  line-height: 1.6;
}

.cta-buttons {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.primary-btn, .secondary-btn {
  display: inline-block;
  padding: 1rem 2rem;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 600;
  transition: all 0.3s ease;
  font-size: 1rem;
}

.primary-btn {
  background: #667eea;
  color: white;
}

.primary-btn:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
}

.secondary-btn {
  background: white;
  color: #667eea;
  border: 2px solid #667eea;
}

.secondary-btn:hover {
  background: #667eea;
  color: white;
}

@media (max-width: 768px) {
  .testimonials-hero h1 {
    font-size: 2.5rem;
  }
  
  .testimonials-grid {
    grid-template-columns: 1fr;
  }
  
  .testimonials-stats {
    grid-template-columns: 1fr;
  }
  
  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .primary-btn, .secondary-btn {
    width: 250px;
    text-align: center;
  }
}

@media (max-width: 480px) {
  .testimonial-card {
    padding: 1.5rem;
  }
  
  .testimonial-content p {
    font-size: 1rem;
  }
  
  .quote-icon {
    font-size: 3rem;
    top: -0.5rem;
  }
}
</style>

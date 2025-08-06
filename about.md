---
layout: page
title: About
permalink: /about/
---

<div class="about-hero">
  <div class="about-content">
    <div class="about-text">
      <h1>About Me</h1>
      <p class="lead">
        I'm Muhamed Javid Hussain, a senior technical writer with 9 years of experience creating clear, user-focused documentation that bridges the gap between complex technology and user understanding.
      </p>
    </div>
    <div class="about-image">
      <div class="profile-placeholder">
        <span>📝</span>
      </div>
    </div>
  </div>
</div>

## My Approach

I believe that great documentation doesn't just explain how something works—it empowers users to accomplish their goals efficiently and confidently. My writing philosophy centers on:

**Clarity Over Complexity**  
I transform technical jargon into plain language that anyone can understand, without losing accuracy or important details.

**User-Centered Design**  
Every piece of documentation I create starts with understanding what users need to accomplish and the challenges they face.

**Continuous Improvement**  
I regularly test and refine documentation based on user feedback and real-world usage patterns.

## Specializations

### User Documentation
Creating step-by-step guides, tutorials, and help articles that make complex software accessible to users of all technical levels.

### Developer Documentation  
Writing comprehensive API references, SDK guides, and technical specifications that help developers integrate and build with confidence.

### Quality Assurance
Conducting pre-release software testing and functional validation to ensure documentation accuracy and completeness.

### Content Strategy
Developing documentation frameworks and style guides that maintain consistency across large documentation projects.

## Professional Background

With nearly a decade in technical writing, I've worked across various industries and technologies, from enterprise software to developer tools. My experience includes:

- **9 years** of professional technical writing experience
- **100+** documentation projects completed
- Expertise in **API documentation**, **user guides**, and **knowledge bases**
- Strong background in **pre-release testing** and **functional validation**
- Proven track record in creating **release notes** and **feature announcements**

## Tools & Technologies

I'm proficient with modern documentation tools and technologies:

- **Documentation Platforms**: GitBook, Confluence, Notion, Jekyll, MkDocs
- **Version Control**: Git, GitHub, GitLab
- **Design Tools**: Figma, Sketch, Canva
- **Content Management**: WordPress, Drupal, Static Site Generators
- **Analytics**: Google Analytics, Hotjar, user feedback tools

## Beyond Writing

When I'm not crafting documentation, I enjoy staying current with emerging technologies and contributing to the technical writing community. I believe in continuous learning and regularly participate in industry discussions and workshops.

---

<div class="contact-cta">
  <h3>Let's Work Together</h3>
  <p>Interested in collaborating or learning more about my work? I'd love to hear from you.</p>
  <a href="{{ site.baseurl }}/contact/" class="cta-button">Get In Touch</a>
</div>

<style>
.about-hero {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  padding: 60px 0;
  margin: -20px -20px 40px -20px;
  border-radius: 0 0 20px 20px;
}

.about-content {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 3rem;
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 20px;
  align-items: center;
}

.about-text h1 {
  font-size: 3rem;
  color: #333;
  margin-bottom: 1rem;
}

.lead {
  font-size: 1.3rem;
  line-height: 1.6;
  color: #555;
  margin: 0;
}

.about-image {
  display: flex;
  justify-content: center;
}

.profile-placeholder {
  width: 200px;
  height: 200px;
  background: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 4rem;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

.about-content + h2 {
  margin-top: 3rem;
  font-size: 2rem;
  color: #333;
  border-bottom: 3px solid #667eea;
  padding-bottom: 0.5rem;
}

h3 {
  color: #667eea;
  margin-top: 2rem;
  margin-bottom: 1rem;
}

.contact-cta {
  background: #667eea;
  color: white;
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
  margin-top: 3rem;
}

.contact-cta h3 {
  color: white;
  margin-top: 0;
  margin-bottom: 1rem;
}

.contact-cta p {
  margin-bottom: 1.5rem;
  opacity: 0.9;
}

.cta-button {
  display: inline-block;
  background: white;
  color: #667eea;
  padding: 0.8rem 2rem;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 600;
  transition: transform 0.3s ease;
}

.cta-button:hover {
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .about-content {
    grid-template-columns: 1fr;
    text-align: center;
  }
  
  .about-text h1 {
    font-size: 2.5rem;
  }
  
  .lead {
    font-size: 1.1rem;
  }
  
  .profile-placeholder {
    width: 150px;
    height: 150px;
    font-size: 3rem;
  }
}
</style>

---
layout: home
title: Welcome
---

<div class="hero">
    <div class="container">
        <h1>Welcome to My Portfolio</h1>
        <p>I'm a passionate developer creating innovative solutions and beautiful digital experiences.</p>
        <div class="button-group">
            <a href="/projects" class="button">View Projects</a>
            <a href="/contact" class="button button-outline">Contact Me</a>
        </div>
    </div>
</div>

<div class="container">
    <h2 class="section-title">Featured Projects</h2>

    <div class="project-grid">
        <div class="project-card">
            <div class="project-image"></div>
            <h3>Web Project</h3>
            <p>A modern web application built with React and Node.js.</p>
            <div class="tags">
                <span>React</span>
                <span>Node.js</span>
            </div>
            <a href="/projects" class="button">Learn More</a>
        </div>

        <div class="project-card">
            <div class="project-image"></div>
            <h3>Mobile App</h3>
            <p>Cross-platform mobile app developed with React Native.</p>
            <div class="tags">
                <span>React Native</span>
                <span>Firebase</span>
            </div>
            <a href="/projects" class="button">Learn More</a>
        </div>

        <div class="project-card">
            <div class="project-image"></div>
            <h3>UI Design</h3>
            <p>Beautiful and intuitive user interface designs.</p>
            <div class="tags">
                <span>Figma</span>
                <span>UI/UX</span>
            </div>
            <a href="/projects" class="button">Learn More</a>
        </div>
    </div>

    <h2 class="section-title">My Expertise</h2>
    
    <div class="service-grid">
        <div class="service-section">
            <div class="service-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M20 4L12 12L4 4M4 4H20V20H4V4Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </div>
            <h3>Web Development</h3>
            <p>Creating responsive and modern web applications using the latest technologies.</p>
        </div>

        <div class="service-section">
            <div class="service-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </div>
            <h3>UI/UX Design</h3>
            <p>Crafting intuitive and engaging user experiences with modern design principles.</p>
        </div>

        <div class="service-section">
            <div class="service-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 2L2 7L12 12L22 7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </div>
            <h3>Mobile Development</h3>
            <p>Building cross-platform mobile applications that users love.</p>
        </div>
    </div>
</div>

<div class="contact-section">
    <div class="container">
        <h2>Let's Work Together</h2>
        <p>Have a project in mind? I'd love to hear about it.</p>
        <a href="/contact" class="button">Get in Touch</a>
    </div>
</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

@media (max-width: 768px) {
  .project-grid, .service-grid {
    grid-template-columns: 1fr;
  }
}
</style> 
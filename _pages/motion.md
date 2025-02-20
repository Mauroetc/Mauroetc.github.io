---
layout: page
title: Motion
permalink: /motion/
image: 03.jpg
---

<div class="motion-hero">
  <div class="hero-content">
    <h1>Motion Design</h1>
    <p class="hero-text">Transformando ideias em movimento através de técnicas avançadas de animação e design.</p>
  </div>
</div>

<div class="project-showcase">
  <div class="showcase-grid">
    <div class="showcase-card">
      <div class="card-media">
        <video class="preview-video" poster="/images/motion/project1-thumb.jpg" loop muted>
          <source src="/videos/motion/project1.mp4" type="video/mp4">
        </video>
        <div class="hover-play">
          <i class="icon-play"></i>
        </div>
      </div>
      <div class="card-info">
        <h3>Vinhetas Corporativas</h3>
        <p>Motion graphics e animações para marcas renomadas</p>
        <div class="tech-pills">
          <span>After Effects</span>
          <span>Cinema 4D</span>
          <span>Design</span>
        </div>
      </div>
    </div>

    <div class="showcase-card large">
      <div class="card-media">
        <video class="preview-video" poster="/images/motion/project2-thumb.jpg" loop muted>
          <source src="/videos/motion/project2.mp4" type="video/mp4">
        </video>
        <div class="hover-play">
          <i class="icon-play"></i>
        </div>
      </div>
      <div class="card-info">
        <h3>Séries Animadas</h3>
        <p>Produção de conteúdo educativo e entretenimento</p>
        <div class="tech-pills">
          <span>Character Animation</span>
          <span>Storyboard</span>
          <span>Compositing</span>
        </div>
      </div>
    </div>

    <div class="showcase-card">
      <div class="card-media">
        <video class="preview-video" poster="/images/motion/project3-thumb.jpg" loop muted>
          <source src="/videos/motion/project3.mp4" type="video/mp4">
        </video>
        <div class="hover-play">
          <i class="icon-play"></i>
        </div>
      </div>
      <div class="card-info">
        <h3>Motion Graphics</h3>
        <p>Efeitos visuais e animações para mídias digitais</p>
        <div class="tech-pills">
          <span>Motion Design</span>
          <span>Visual Effects</span>
          <span>3D</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="workflow-section">
  <h2>Workflow & Expertise</h2>
  <div class="workflow-grid">
    <div class="workflow-card">
      <i class="icon-concept"></i>
      <h3>Conceito</h3>
      <ul>
        <li>Storyboard</li>
        <li>Design de Personagens</li>
        <li>Direção de Arte</li>
      </ul>
    </div>
    
    <div class="workflow-card">
      <i class="icon-animation"></i>
      <h3>Animação</h3>
      <ul>
        <li>Character Animation</li>
        <li>Motion Graphics</li>
        <li>Efeitos Visuais</li>
      </ul>
    </div>
    
    <div class="workflow-card">
      <i class="icon-production"></i>
      <h3>Produção</h3>
      <ul>
        <li>Compositing</li>
        <li>Color Grading</li>
        <li>Render Final</li>
      </ul>
    </div>
  </div>
</div>

<style>
.motion-hero {
  height: 300px;
  background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  margin-bottom: 3rem;
  padding: 2rem;
}

.hero-text {
  font-size: 1.2rem;
  max-width: 600px;
  margin: 1rem auto 0;
}

.project-showcase {
  margin: 3rem 0;
}

.showcase-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.showcase-card {
  background: var(--background-color);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.showcase-card:hover {
  transform: translateY(-5px);
}

.showcase-card.large {
  grid-column: 1 / -1;
}

.card-media {
  position: relative;
  padding-top: 56.25%;
  cursor: pointer;
}

.preview-video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hover-play {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background: rgba(0, 0, 0, 0.5);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.card-media:hover .hover-play {
  opacity: 1;
}

.hover-play i {
  color: white;
  font-size: 3rem;
}

.card-info {
  padding: 1.5rem;
}

.tech-pills {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
  margin-top: 1rem;
}

.tech-pills span {
  background: var(--primary-color);
  color: white;
  padding: 0.2rem 0.8rem;
  border-radius: 15px;
  font-size: 0.9rem;
}

.workflow-section {
  margin-top: 4rem;
}

.workflow-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.workflow-card {
  background: var(--background-color);
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.workflow-card i {
  font-size: 3rem;
  color: var(--primary-color);
  margin-bottom: 1rem;
}

.workflow-card ul {
  list-style: none;
  padding: 0;
  margin-top: 1rem;
}

.workflow-card li {
  margin: 0.5rem 0;
}

@media (max-width: 768px) {
  .motion-hero {
    height: auto;
    min-height: 200px;
  }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const videos = document.querySelectorAll('.preview-video');
  
  videos.forEach(video => {
    const container = video.closest('.card-media');
    
    container.addEventListener('mouseenter', () => {
      video.play();
    });
    
    container.addEventListener('mouseleave', () => {
      video.pause();
      video.currentTime = 0;
    });
  });
});
</script>
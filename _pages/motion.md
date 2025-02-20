---
layout: page
title: Motion
permalink: /motion/
image: 03.jpg
---

<div class="page-hero">
  <div class="hero-content">
    <h1>Motion Design</h1>
    <p class="hero-text">Transformando ideias em movimento através de técnicas avançadas de animação e design.</p>
  </div>
</div>

<div class="card-grid">
  <div class="base-card">
    <div class="media-container">
      <video class="preview-video" poster="/images/motion/project1-thumb.jpg" loop muted>
        <source src="/videos/motion/project1.mp4" type="video/mp4">
      </video>
      <div class="play-overlay">
        <i class="icon-play"></i>
      </div>
    </div>
    <div class="card-content">
      <h3>Vinhetas Corporativas</h3>
      <p>Motion graphics e animações para marcas renomadas</p>
      <div class="tags">
        <span class="tag">After Effects</span>
        <span class="tag">Cinema 4D</span>
        <span class="tag">Design</span>
      </div>
    </div>
  </div>

  <div class="base-card featured">
    <div class="media-container">
      <video class="preview-video" poster="/images/motion/project2-thumb.jpg" loop muted>
        <source src="/videos/motion/project2.mp4" type="video/mp4">
      </video>
      <div class="play-overlay">
        <i class="icon-play"></i>
      </div>
    </div>
    <div class="card-content">
      <h3>Séries Animadas</h3>
      <p>Produção de conteúdo educativo e entretenimento</p>
      <div class="tags">
        <span class="tag">Character Animation</span>
        <span class="tag">Storyboard</span>
        <span class="tag">Compositing</span>
      </div>
    </div>
  </div>

  <div class="base-card">
    <div class="media-container">
      <video class="preview-video" poster="/images/motion/project3-thumb.jpg" loop muted>
        <source src="/videos/motion/project3.mp4" type="video/mp4">
      </video>
      <div class="play-overlay">
        <i class="icon-play"></i>
      </div>
    </div>
    <div class="card-content">
      <h3>Motion Graphics</h3>
      <p>Efeitos visuais e animações para mídias digitais</p>
      <div class="tags">
        <span class="tag">Motion Design</span>
        <span class="tag">Visual Effects</span>
        <span class="tag">3D</span>
      </div>
    </div>
  </div>
</div>

<div class="expertise-grid">
  <div class="expertise-card">
    <i class="icon-concept"></i>
    <h3>Conceito</h3>
    <ul>
      <li>Storyboard</li>
      <li>Design de Personagens</li>
      <li>Direção de Arte</li>
    </ul>
  </div>
  
  <div class="expertise-card">
    <i class="icon-animation"></i>
    <h3>Animação</h3>
    <ul>
      <li>Character Animation</li>
      <li>Motion Graphics</li>
      <li>Efeitos Visuais</li>
    </ul>
  </div>
  
  <div class="expertise-card">
    <i class="icon-production"></i>
    <h3>Produção</h3>
    <ul>
      <li>Compositing</li>
      <li>Color Grading</li>
      <li>Render Final</li>
    </ul>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const videos = document.querySelectorAll('.preview-video');
  
  videos.forEach(video => {
    const container = video.closest('.media-container');
    
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
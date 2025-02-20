---
layout: page
title: Animação
permalink: /animation/
image: 02.jpg
---

<div class="filter-buttons">
  <button class="filter-btn active" data-filter="all">Todos</button>
  <button class="filter-btn" data-filter="2d">Animação 2D</button>
  <button class="filter-btn" data-filter="motion">Motion</button>
  <button class="filter-btn" data-filter="stop-motion">Stop Motion</button>
</div>

<div class="card-grid">
  <div class="base-card" data-category="2d motion">
    <div class="media-container">
      <img src="/images/cultura-inglesa-thumb.jpg" alt="Cultura Inglesa Project">
      <div class="play-overlay">
        <a href="#" class="view-project">Ver Projeto</a>
      </div>
    </div>
    <div class="card-content">
      <h3>Cultura Inglesa</h3>
      <div class="tags">
        <span class="tag">Motion Graphics</span>
        <span class="tag">2D Animation</span>
      </div>
      <p>Desenvolvimento de vinhetas animadas e vídeos institucionais com identidade visual própria.</p>
    </div>
  </div>

  <div class="base-card" data-category="2d">
    <div class="media-container">
      <img src="/images/mega-curioso-thumb.jpg" alt="Mega Curioso">
      <div class="play-overlay">
        <a href="#" class="view-project">Ver Projeto</a>
      </div>
    </div>
    <div class="card-content">
      <h3>Mega Curioso</h3>
      <div class="tags">
        <span class="tag">Educational</span>
        <span class="tag">Character Animation</span>
      </div>
      <p>Série de animações educativas com estilo visual próprio para público infantil.</p>
    </div>
  </div>

  <div class="base-card featured" data-category="2d motion">
    <div class="media-container">
      <img src="/images/gato-galactico-thumb.jpg" alt="Gato Galáctico">
      <div class="play-overlay">
        <a href="#" class="view-project">Ver Projeto</a>
      </div>
    </div>
    <div class="card-content">
      <h3>Projeto Gato Galáctico</h3>
      <div class="tags">
        <span class="tag">Interactive</span>
        <span class="tag">Cut-out</span>
        <span class="tag">Adobe Featured</span>
      </div>
      <p>Animação interativa com técnica cut-out em colaboração com ilustradores renomados.</p>
    </div>
  </div>
</div>

<div class="expertise-grid">
  <div class="expertise-card">
    <h2>🎨 Técnicas</h2>
    <div class="skill-bars">
      <div class="skill-bar">
        <span class="skill-name">Character Animation</span>
        <div class="bar-container">
          <div class="bar" style="--level: 90%"></div>
        </div>
      </div>
      <div class="skill-bar">
        <span class="skill-name">Cut-out Animation</span>
        <div class="bar-container">
          <div class="bar" style="--level: 95%"></div>
        </div>
      </div>
      <div class="skill-bar">
        <span class="skill-name">Frame by Frame</span>
        <div class="bar-container">
          <div class="bar" style="--level: 85%"></div>
        </div>
      </div>
      <div class="skill-bar">
        <span class="skill-name">Motion Graphics</span>
        <div class="bar-container">
          <div class="bar" style="--level: 88%"></div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="expertise-card">
    <h2>💻 Software</h2>
    <div class="tool-grid">
      <div class="tool-item">
        <i class="icon-adobe"></i>
        <span>Adobe Animate</span>
      </div>
      <div class="tool-item">
        <i class="icon-toonboom"></i>
        <span>ToonBoom</span>
      </div>
      <div class="tool-item">
        <i class="icon-aftereffects"></i>
        <span>After Effects</span>
      </div>
      <div class="tool-item">
        <i class="icon-cinema4d"></i>
        <span>Cinema 4D</span>
      </div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const filterBtns = document.querySelectorAll('.filter-btn');
  const portfolioItems = document.querySelectorAll('.base-card[data-category]');

  filterBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      filterBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      
      const filter = btn.dataset.filter;
      portfolioItems.forEach(item => {
        if (filter === 'all' || item.dataset.category.includes(filter)) {
          item.style.display = 'block';
        } else {
          item.style.display = 'none';
        }
      });
    });
  });
});
</script>
---
layout: page
title: Video
permalink: /video/
image: 05.jpg
---

<div class="page-hero">
  <div class="hero-content">
    <h1>Produção Audiovisual</h1>
    <p class="hero-text">Criando narrativas visuais impactantes através da produção cinematográfica e documentários.</p>
  </div>
</div>

<div class="filter-buttons">
  <button class="filter-btn active" data-filter="all">Todos</button>
  <button class="filter-btn" data-filter="documentary">Documentários</button>
  <button class="filter-btn" data-filter="shortfilm">Curtas</button>
  <button class="filter-btn" data-filter="commercial">Comercial</button>
</div>

<div class="card-grid">
  <div class="base-card featured" data-category="shortfilm">
    <div class="media-container">
      <div class="video-thumbnail" style="background-image: url('/images/video/mis-experimento.jpg')">
        <a href="https://www.youtube.com/watch?v=hdm5Hw-vIO8" class="play-overlay">
          <i class="icon-play"></i>
        </a>
      </div>
    </div>
    <div class="card-content">
      <h2>MIS - O Experimento</h2>
      <div class="meta-info">
        <span class="year">2016</span>
        <span class="duration">15 min</span>
      </div>
      <p>Curta-metragem selecionado pelo Edital "Núcleo Experimental de Cinema" do MIS e premiado internacionalmente.</p>
      <div class="tags">
        <span class="tag">Direção</span>
        <span class="tag">Roteiro</span>
        <span class="tag">Edição</span>
      </div>
    </div>
  </div>

  <div class="base-card" data-category="documentary">
    <div class="media-container">
      <div class="video-thumbnail" style="background-image: url('/images/video/tinkus.jpg')">
        <a href="https://www.youtube.com/watch?v=PaVpzwjYBic" class="play-overlay">
          <i class="icon-play"></i>
        </a>
      </div>
    </div>
    <div class="card-content">
      <h2>TINKUS</h2>
      <div class="meta-info">
        <span class="year">2014</span>
        <span class="duration">25 min</span>
      </div>
      <p>Documentário sobre as raízes bolivianas no Brasil, exibido em mostras culturais internacionais.</p>
      <div class="tags">
        <span class="tag">Documentário</span>
        <span class="tag">Direção</span>
        <span class="tag">Roteiro</span>
      </div>
    </div>
  </div>

  <div class="base-card" data-category="shortfilm commercial">
    <div class="media-container">
      <div class="video-thumbnail" style="background-image: url('/images/video/mcdont.jpg')">
        <a href="https://youtu.be/5Bxp1hlmC88" class="play-overlay">
          <i class="icon-play"></i>
        </a>
      </div>
    </div>
    <div class="card-content">
      <h2>Mc Don't</h2>
      <div class="meta-info">
        <span class="year">2015</span>
        <span class="duration">5 min</span>
      </div>
      <p>Premiado no Festival Internacional Entretodos em duas categorias.</p>
      <div class="tags">
        <span class="tag">Curta</span>
        <span class="tag">Direção</span>
        <span class="tag">Produção</span>
      </div>
    </div>
  </div>
</div>

<div class="expertise-grid">
  <div class="expertise-card">
    <i class="icon-camera"></i>
    <h3>Direção</h3>
    <ul>
      <li>Direção Cinematográfica</li>
      <li>Direção de Fotografia</li>
      <li>Direção de Arte</li>
    </ul>
  </div>
  
  <div class="expertise-card">
    <i class="icon-edit"></i>
    <h3>Pós-Produção</h3>
    <ul>
      <li>Edição</li>
      <li>Color Grading</li>
      <li>Sound Design</li>
    </ul>
  </div>
  
  <div class="expertise-card">
    <i class="icon-production"></i>
    <h3>Produção</h3>
    <ul>
      <li>Roteiro</li>
      <li>Produção Executiva</li>
      <li>Gestão de Equipe</li>
    </ul>
  </div>
</div>

<style>
/* Page-specific styles */
.video-thumbnail {
  position: relative;
  padding-top: 56.25%;
  background-size: cover;
  background-position: center;
}

.meta-info {
  display: flex;
  gap: 1rem;
  color: var(--secondary-color);
  margin: 0.5rem 0;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const filterBtns = document.querySelectorAll('.filter-btn');
  const videoCards = document.querySelectorAll('.base-card[data-category]');

  filterBtns.forEach(btn => {
    btn.addEventListener('click', () => {
      filterBtns.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
      
      const filter = btn.dataset.filter;
      videoCards.forEach(card => {
        if (filter === 'all' || card.dataset.category.includes(filter)) {
          card.style.display = 'block';
        } else {
          card.style.display = 'none';
        }
      });
    });
  });
});
</script>
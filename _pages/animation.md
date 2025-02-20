---
layout: page
title: Animação
permalink: /animation/
image: 02.jpg
---

<div class="portfolio-nav">
  <button class="filter-btn active" data-filter="all">Todos</button>
  <button class="filter-btn" data-filter="2d">Animação 2D</button>
  <button class="filter-btn" data-filter="motion">Motion</button>
  <button class="filter-btn" data-filter="stop-motion">Stop Motion</button>
</div>

<div class="portfolio-grid">
  <div class="portfolio-card" data-category="2d motion">
    <div class="card-image">
      <img src="/images/cultura-inglesa-thumb.jpg" alt="Cultura Inglesa Project">
      <div class="card-overlay">
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

  <div class="portfolio-card" data-category="2d">
    <div class="card-image">
      <img src="/images/mega-curioso-thumb.jpg" alt="Mega Curioso">
      <div class="card-overlay">
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

  <div class="portfolio-card featured" data-category="2d motion">
    <div class="card-image">
      <img src="/images/gato-galactico-thumb.jpg" alt="Gato Galáctico">
      <div class="card-overlay">
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

<div class="skills-section">
  <div class="skills-card">
    <h2>🎨 Técnicas</h2>
    <div class="skills-grid">
      <div class="skill-item">
        <span class="skill-name">Character Animation</span>
        <div class="skill-bar" style="--progress: 90%"></div>
      </div>
      <div class="skill-item">
        <span class="skill-name">Cut-out Animation</span>
        <div class="skill-bar" style="--progress: 95%"></div>
      </div>
      <div class="skill-item">
        <span class="skill-name">Frame by Frame</span>
        <div class="skill-bar" style="--progress: 85%"></div>
      </div>
      <div class="skill-item">
        <span class="skill-name">Motion Graphics</span>
        <div class="skill-bar" style="--progress: 88%"></div>
      </div>
    </div>
  </div>
  
  <div class="skills-card">
    <h2>💻 Software</h2>
    <div class="tools-grid">
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

<style>
.portfolio-nav {
  display: flex;
  gap: 1rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.filter-btn {
  padding: 0.5rem 1rem;
  border: 2px solid var(--primary-color);
  border-radius: 25px;
  background: transparent;
  color: var(--text-color);
  cursor: pointer;
  transition: all 0.3s ease;
}

.filter-btn.active,
.filter-btn:hover {
  background: var(--primary-color);
  color: white;
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.portfolio-card {
  background: var(--background-color);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.portfolio-card:hover {
  transform: translateY(-5px);
}

.portfolio-card.featured {
  grid-column: 1 / -1;
}

.card-image {
  position: relative;
  padding-top: 56.25%;
  overflow: hidden;
}

.card-image img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.card-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.7);
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.portfolio-card:hover .card-overlay {
  opacity: 1;
}

.portfolio-card:hover .card-image img {
  transform: scale(1.1);
}

.view-project {
  color: white;
  text-decoration: none;
  padding: 0.8rem 1.5rem;
  border: 2px solid white;
  border-radius: 25px;
  transition: all 0.3s ease;
}

.view-project:hover {
  background: white;
  color: var(--primary-color);
}

.card-content {
  padding: 1.5rem;
}

.tags {
  display: flex;
  gap: 0.5rem;
  margin: 0.5rem 0;
  flex-wrap: wrap;
}

.tag {
  background: var(--primary-color);
  color: white;
  padding: 0.2rem 0.8rem;
  border-radius: 15px;
  font-size: 0.9rem;
}

.skills-section {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
}

.skills-card {
  background: var(--background-color);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.skills-grid {
  display: grid;
  gap: 1rem;
  margin-top: 1rem;
}

.skill-item {
  display: grid;
  gap: 0.5rem;
}

.skill-bar {
  height: 8px;
  background: #eee;
  border-radius: 4px;
  overflow: hidden;
}

.skill-bar::after {
  content: '';
  display: block;
  height: 100%;
  width: var(--progress);
  background: var(--primary-color);
  border-radius: 4px;
}

.tools-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.tool-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
  text-align: center;
}

.tool-item i {
  font-size: 2rem;
  color: var(--primary-color);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const filterBtns = document.querySelectorAll('.filter-btn');
  const portfolioItems = document.querySelectorAll('.portfolio-card');

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
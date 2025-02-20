---
layout: page
title: Conquistas
permalink: /achievements/
image: 01.jpg
---

<div class="achievements-grid">
  <div class="achievement-card featured">
    <div class="card-content">
      <span class="project-year">2016</span>
      <h2>MIS - O Experimento</h2>
      <div class="achievements-list">
        <span class="achievement-item">🏆 Selecionado pelo Edital "Núcleo Experimental de Cinema" do MIS</span>
        <span class="achievement-item">⭐ Melhores de 2016 - Semana Paulistana de Curta-Metragem</span>
        <span class="achievement-item">🌎 Exibição internacional em Portugal e Estados Unidos</span>
      </div>
      <a href="https://www.youtube.com/watch?v=hdm5Hw-vIO8" class="watch-button">
        <i class="icon-play"></i> Assistir Trailer
      </a>
    </div>
  </div>

  <div class="achievement-card">
    <div class="card-content">
      <span class="project-year">2015</span>
      <h2>Mc Don't</h2>
      <div class="achievements-list">
        <span class="achievement-item">🏆 Segundo lugar em duas categorias - Festival Entretodos</span>
        <span class="achievement-item">👥 Premiação pelo Júri Popular e Júri Online</span>
      </div>
      <a href="https://youtu.be/5Bxp1hlmC88" class="watch-button">
        <i class="icon-play"></i> Assistir Curta
      </a>
    </div>
  </div>

  <div class="achievement-card">
    <div class="card-content">
      <span class="project-year">2014</span>
      <h2>TINKUS</h2>
      <div class="achievements-list">
        <span class="achievement-item">🎬 Documentário sobre raízes bolivianas no Brasil</span>
        <span class="achievement-item">👥 Direção em parceria com Marcelo Ferraro</span>
        <span class="achievement-item">🌎 Exibido em mostras culturais internacionais</span>
      </div>
      <a href="https://www.youtube.com/watch?v=PaVpzwjYBic" class="watch-button">
        <i class="icon-play"></i> Assistir Documentário
      </a>
    </div>
  </div>

  <div class="achievement-card">
    <div class="card-content">
      <span class="project-year">2023</span>
      <h2>Street Fighter Stopmotion</h2>
      <div class="achievements-list">
        <span class="achievement-item">🎨 Técnicas tradicionais e digitais combinadas</span>
        <span class="achievement-item">🎬 Co-direção e Animação</span>
      </div>
      <a href="https://www.youtube.com/watch?v=Pa2F18nurnM" class="watch-button">
        <i class="icon-play"></i> Assistir Projeto
      </a>
    </div>
  </div>

  <div class="achievement-card">
    <div class="card-content">
      <span class="project-year">2023-2024</span>
      <h2>EasyRPG Player</h2>
      <div class="achievements-list">
        <span class="achievement-item">💻 Implementação de recursos críticos</span>
        <span class="achievement-item">⚡ Otimização de performance</span>
        <span class="achievement-item">🔄 Migração do sistema JSON</span>
      </div>
      <a href="https://github.com/EasyRPG/Player" class="watch-button">
        <i class="icon-github"></i> Ver Repositório
      </a>
    </div>
  </div>
</div>

<style>
.achievements-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.achievement-card {
  background: var(--background-color);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease;
}

.achievement-card:hover {
  transform: translateY(-5px);
}

.achievement-card.featured {
  grid-column: 1 / -1;
  background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
  color: white;
}

.card-content {
  padding: 1.5rem;
}

.project-year {
  background: var(--primary-color);
  color: white;
  padding: 0.2rem 0.8rem;
  border-radius: 20px;
  font-size: 0.9rem;
  display: inline-block;
  margin-bottom: 1rem;
}

.featured .project-year {
  background: rgba(255, 255, 255, 0.2);
}

.achievements-list {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
  margin: 1rem 0;
}

.achievement-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.95rem;
}

.watch-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: var(--primary-color);
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 500;
  margin-top: 1rem;
  transition: background 0.2s ease;
}

.watch-button:hover {
  background: var(--secondary-color);
}

.featured .watch-button {
  background: white;
  color: var(--primary-color);
}

.featured .watch-button:hover {
  background: rgba(255, 255, 255, 0.9);
}
</style>
---
layout: page
title: Programação
permalink: /programming/
image: 04.jpg
---

<div class="tech-stack-banner">
  <div class="tech-icon">
    <i class="icon-javascript"></i>
    <span>JavaScript</span>
  </div>
  <div class="tech-icon">
    <i class="icon-cpp"></i>
    <span>C++</span>
  </div>
  <div class="tech-icon">
    <i class="icon-python"></i>
    <span>Python</span>
  </div>
  <div class="tech-icon">
    <i class="icon-web"></i>
    <span>Web</span>
  </div>
</div>

<div class="project-grid">
  <div class="project-card featured">
    <div class="card-header">
      <h2>EasyRPG Player</h2>
      <div class="project-meta">
        <span class="date">2023-2024</span>
        <a href="https://github.com/EasyRPG/Player" class="github-link">
          <i class="icon-github"></i> View Source
        </a>
      </div>
    </div>
    <div class="card-body">
      <div class="tech-tags">
        <span class="tech-tag">C++</span>
        <span class="tech-tag">JSON</span>
        <span class="tech-tag">Performance</span>
      </div>
      <ul class="feature-list">
        <li>Migração do sistema JSON (picoJSON para Nlohmann's JSON)</li>
        <li>Implementação de configurações locais</li>
        <li>Otimização de performance</li>
        <li>Contribuições ativas no repositório principal</li>
      </ul>
    </div>
  </div>

  <div class="project-card">
    <div class="card-header">
      <h2>SVG-2-PIXELART</h2>
      <div class="project-meta">
        <span class="date">2023</span>
        <a href="#" class="github-link">
          <i class="icon-github"></i> View Source
        </a>
      </div>
    </div>
    <div class="card-body">
      <div class="tech-tags">
        <span class="tech-tag">JavaScript</span>
        <span class="tech-tag">SVGO</span>
        <span class="tech-tag">Web API</span>
      </div>
      <ul class="feature-list">
        <li>Ferramenta web para conversão vetor-pixel</li>
        <li>Integração com API SVGO</li>
        <li>Interface intuitiva no GitHub Pages</li>
      </ul>
    </div>
  </div>

  <div class="project-card">
    <div class="card-header">
      <h2>After-Effects-Smooth-Path</h2>
      <div class="project-meta">
        <span class="date">2022</span>
        <a href="#" class="github-link">
          <i class="icon-github"></i> View Source
        </a>
      </div>
    </div>
    <div class="card-body">
      <div class="tech-tags">
        <span class="tech-tag">ExtendScript</span>
        <span class="tech-tag">After Effects</span>
      </div>
      <ul class="feature-list">
        <li>Expressões otimizadas para After Effects</li>
        <li>Suavização de movimento aprimorada</li>
        <li>Código aberto e documentado</li>
      </ul>
    </div>
  </div>
</div>

<div class="skills-matrix">
  <div class="matrix-card">
    <h3>Desenvolvimento Web</h3>
    <div class="skill-bars">
      <div class="skill-bar">
        <span class="skill-name">JavaScript</span>
        <div class="bar-container">
          <div class="bar" style="--level: 90%"></div>
        </div>
      </div>
      <div class="skill-bar">
        <span class="skill-name">HTML/CSS</span>
        <div class="bar-container">
          <div class="bar" style="--level: 85%"></div>
        </div>
      </div>
      <div class="skill-bar">
        <span class="skill-name">Node.js</span>
        <div class="bar-container">
          <div class="bar" style="--level: 75%"></div>
        </div>
      </div>
    </div>
  </div>

  <div class="matrix-card">
    <h3>Ferramentas & DevOps</h3>
    <div class="tool-grid">
      <div class="tool-item">
        <i class="icon-git"></i>
        <span>Git</span>
      </div>
      <div class="tool-item">
        <i class="icon-docker"></i>
        <span>Docker</span>
      </div>
      <div class="tool-item">
        <i class="icon-vscode"></i>
        <span>VS Code</span>
      </div>
      <div class="tool-item">
        <i class="icon-npm"></i>
        <span>npm</span>
      </div>
    </div>
  </div>
</div>

<style>
.tech-stack-banner {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin: 2rem 0;
  flex-wrap: wrap;
}

.tech-icon {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
}

.tech-icon i {
  font-size: 2.5rem;
  color: var(--primary-color);
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.project-card {
  background: var(--background-color);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease;
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-card.featured {
  grid-column: 1 / -1;
  background: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
  color: white;
}

.card-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1rem;
}

.project-meta {
  display: flex;
  gap: 1rem;
  align-items: center;
}

.date {
  font-size: 0.9rem;
  opacity: 0.8;
}

.github-link {
  display: flex;
  align-items: center;
  gap: 0.3rem;
  text-decoration: none;
  color: inherit;
}

.tech-tags {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
  margin-bottom: 1rem;
}

.tech-tag {
  background: rgba(var(--primary-color-rgb), 0.1);
  padding: 0.2rem 0.8rem;
  border-radius: 15px;
  font-size: 0.9rem;
}

.featured .tech-tag {
  background: rgba(255, 255, 255, 0.2);
}

.feature-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.feature-list li {
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.feature-list li::before {
  content: '→';
  color: var(--primary-color);
}

.featured .feature-list li::before {
  color: white;
}

.skills-matrix {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 3rem;
}

.matrix-card {
  background: var(--background-color);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.skill-bars {
  display: grid;
  gap: 1rem;
}

.skill-bar {
  display: grid;
  gap: 0.5rem;
}

.bar-container {
  height: 8px;
  background: #eee;
  border-radius: 4px;
  overflow: hidden;
}

.bar {
  height: 100%;
  width: var(--level);
  background: var(--primary-color);
  border-radius: 4px;
}

.tool-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
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
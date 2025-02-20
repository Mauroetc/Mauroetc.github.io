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

<div class="card-grid">
  <div class="base-card featured">
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
      <div class="tags">
        <span class="tag">C++</span>
        <span class="tag">JSON</span>
        <span class="tag">Performance</span>
      </div>
      <ul class="feature-list">
        <li>Migração do sistema JSON (picoJSON para Nlohmann's JSON)</li>
        <li>Implementação de configurações locais</li>
        <li>Otimização de performance</li>
        <li>Contribuições ativas no repositório principal</li>
      </ul>
    </div>
  </div>

  <div class="base-card">
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
      <div class="tags">
        <span class="tag">JavaScript</span>
        <span class="tag">SVGO</span>
        <span class="tag">Web API</span>
      </div>
      <ul class="feature-list">
        <li>Ferramenta web para conversão vetor-pixel</li>
        <li>Integração com API SVGO</li>
        <li>Interface intuitiva no GitHub Pages</li>
      </ul>
    </div>
  </div>

  <div class="base-card">
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
      <div class="tags">
        <span class="tag">ExtendScript</span>
        <span class="tag">After Effects</span>
      </div>
      <ul class="feature-list">
        <li>Expressões otimizadas para After Effects</li>
        <li>Suavização de movimento aprimorada</li>
        <li>Código aberto e documentado</li>
      </ul>
    </div>
  </div>
</div>

<div class="expertise-grid">
  <div class="expertise-card">
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

  <div class="expertise-card">
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
/* Keep only page-specific styles */
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
</style>
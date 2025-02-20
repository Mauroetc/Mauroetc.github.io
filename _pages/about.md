---
layout: page
title: Sobre
permalink: /about/
image: profile.jpg
---

<div class="profile-header">
  <img src="/images/profile.jpg" alt="Mauro Junior" class="profile-image">
  <div class="profile-intro">
    <h1>Mauro Junior</h1>
    <p class="lead">Profissional multidisciplinar com mais de 7 anos de experiência em produção audiovisual, animação e desenvolvimento.</p>
  </div>
</div>

<div class="cards-container">
  <div class="card">
    <h2>🎓 Formação</h2>
    <ul class="clean-list">
      <li><span class="highlight">Animação</span><br>CAV Centro de Audiovisual (860hs - Em andamento)</li>
      <li><span class="highlight">Cinema e Televisão</span><br>CAV Centro de Audiovisual (810hs)</li>
      <li><span class="highlight">Design Digital</span><br>SAGA School (433hs)</li>
      <li><span class="highlight">Web Design</span><br>ETEC Lauro Gomes (96hs)</li>
    </ul>
  </div>

  <div class="card">
    <h2>💻 Desenvolvimento</h2>
    <div class="skills-grid">
      <span class="skill-tag">JavaScript</span>
      <span class="skill-tag">HTML/CSS</span>
      <span class="skill-tag">Python</span>
      <span class="skill-tag">ActionScript 3</span>
      <span class="skill-tag">Web Dev</span>
      <span class="skill-tag">Automação</span>
    </div>
  </div>

  <div class="card">
    <h2>🎨 Animação & Motion</h2>
    <div class="skills-grid">
      <span class="skill-tag">After Effects</span>
      <span class="skill-tag">Premiere</span>
      <span class="skill-tag">Animate</span>
      <span class="skill-tag">Cinema 4D</span>
      <span class="skill-tag">Animação 2D</span>
      <span class="skill-tag">Motion Graphics</span>
    </div>
  </div>

  <div class="card">
    <h2>🎯 Design</h2>
    <div class="skills-grid">
      <span class="skill-tag">Photoshop</span>
      <span class="skill-tag">Illustrator</span>
      <span class="skill-tag">UI/UX</span>
      <span class="skill-tag">Pixel Art</span>
      <span class="skill-tag">Vetorização</span>
    </div>
  </div>

  <div class="card contact-card">
    <h2>📫 Contato</h2>
    <div class="contact-grid">
      <a href="mailto:mauro.etc@live.com" class="contact-item">
        <i class="icon-mail"></i> mauro.etc@live.com
      </a>
      <a href="tel:+551145182231" class="contact-item">
        <i class="icon-phone"></i> (11) 4518-2231
      </a>
      <a href="tel:+5511985149731" class="contact-item">
        <i class="icon-mobile"></i> (11) 98514-9731
      </a>
      <a href="https://github.com/Mauroetc" class="contact-item">
        <i class="icon-github"></i> GitHub
      </a>
      <a href="https://www.behance.net/gallery/65727549/Portifolio-2018-Mauro-Junior" class="contact-item">
        <i class="icon-behance"></i> Behance
      </a>
    </div>
  </div>
</div>

<style>
.profile-header {
  display: flex;
  align-items: center;
  margin-bottom: 2rem;
  gap: 2rem;
}

.profile-image {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
}

.profile-intro {
  flex: 1;
}

.cards-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.card {
  background: var(--background-color);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.clean-list {
  list-style: none;
  padding: 0;
}

.clean-list li {
  margin-bottom: 1rem;
}

.highlight {
  font-weight: bold;
  color: var(--primary-color);
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill-tag {
  background: var(--primary-color);
  color: white;
  padding: 0.3rem 0.8rem;
  border-radius: 20px;
  font-size: 0.9rem;
}

.contact-grid {
  display: grid;
  gap: 1rem;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  text-decoration: none;
  color: var(--text-color);
}

.contact-item:hover {
  color: var(--primary-color);
}
</style>
---
layout: post
title: Group Portfolio
permalink: /
hide: true
show_reading_time: false
---

<style>
.team-home {
  --panel: #151b27;
  --border: rgba(255, 255, 255, 0.12);
  --text: #f7f9fc;
  --muted: #aeb9cb;
  --accent: #73e0c1;
  --accent-2: #8eb8ff;
  max-width: 1080px;
  margin: 0 auto;
  color: var(--text);
}
.team-hero {
  padding: clamp(2rem, 6vw, 4.5rem) 0 2.5rem;
}
.team-eyebrow {
  margin: 0 0 0.8rem;
  color: var(--accent);
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}
.team-hero h1 {
  max-width: 780px;
  margin: 0;
  font-size: clamp(2.4rem, 7vw, 4.6rem);
  line-height: 1;
  letter-spacing: -0.045em;
}
.team-lede {
  max-width: 720px;
  margin: 1.35rem 0 0;
  color: var(--muted);
  font-size: 1.05rem;
  line-height: 1.7;
}
.team-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.7rem;
}
.team-button {
  display: inline-flex;
  align-items: center;
  min-height: 42px;
  padding: 0.45rem 1rem;
  border: 1px solid var(--border);
  border-radius: 999px;
  color: var(--text) !important;
  background: rgba(255, 255, 255, 0.04);
  text-decoration: none !important;
  font-weight: 750;
}
.team-button.primary {
  border-color: transparent;
  color: #07140f !important;
  background: var(--accent);
}
.team-grid,
.status-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
  margin: 1rem 0 3rem;
}
.team-card,
.status-card {
  padding: 1.25rem;
  border: 1px solid var(--border);
  border-radius: 16px;
  background: var(--panel);
}
.team-card h3,
.status-card h3 {
  margin: 0 0 0.45rem;
}
.team-role,
.status-label {
  color: var(--accent);
  font-weight: 700;
}
.team-card p,
.status-card p {
  color: var(--muted);
  line-height: 1.55;
}
.team-card a {
  color: var(--accent-2);
}
.team-home h2 {
  margin-top: 2.5rem;
}
.team-agreements {
  padding: 1.3rem 1.5rem;
  border-left: 4px solid var(--accent);
  border-radius: 0 14px 14px 0;
  background: var(--panel);
}
.team-agreements li {
  margin: 0.55rem 0;
  color: var(--muted);
}
@media (max-width: 760px) {
  .team-grid,
  .status-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="team-home">
  <section class="team-hero">
    <p class="team-eyebrow">AP CSP · Shared Workspace</p>
    <h1>Three developers, one documented process.</h1>
    <p class="team-lede">
      This portfolio records our planning, collaboration, implementation evidence,
      testing, and reflections. Project direction will be added only after the team
      has reviewed and approved it.
    </p>
    <div class="team-actions">
      <a class="team-button primary" href="{{ '/about/' | relative_url }}">Meet the team</a>
      <a class="team-button" href="{{ '/collaboration/' | relative_url }}">Collaboration history</a>
      <a class="team-button" href="https://github.com/ruhaanb622/group-portfolio">GitHub repository</a>
    </div>
  </section>

  <h2>Team</h2>
  <div class="team-grid">
    <article class="team-card">
      <p class="team-role">Scrum Master / Developer</p>
      <h3>Ruhaan Bansal</h3>
      <p>Coordinates the board, supports integration, and contributes development work.</p>
      <a href="https://ruhaanb622.github.io/portfolio/">Personal portfolio →</a>
    </article>
    <article class="team-card">
      <p class="team-role">Technologist / Developer</p>
      <h3>Arya Taghavi Zargar</h3>
      <p>Owns assigned technical tasks and documents implementation evidence.</p>
      <a href="https://arya622-y.github.io/portfolio/">Personal portfolio →</a>
    </article>
    <article class="team-card">
      <p class="team-role">Technologist / Developer</p>
      <h3>Deyar Raissadat</h3>
      <p>Owns assigned technical tasks and documents testing and implementation evidence.</p>
      <a href="https://drdeyar.github.io/portfolio/">Personal portfolio →</a>
    </article>
  </div>

  <h2>Workspace status</h2>
  <div class="status-grid">
    <article class="status-card">
      <p class="status-label">Repository</p>
      <h3>Foundation ready</h3>
      <p>Team details, navigation, contribution guidance, and evidence pages are in place.</p>
    </article>
    <article class="status-card">
      <p class="status-label">Project direction</p>
      <h3>Not selected</h3>
      <p>No product or inherited-project work is represented in this setup.</p>
    </article>
    <article class="status-card">
      <p class="status-label">Evidence</p>
      <h3>Ready to record</h3>
      <p>The collaboration page is prepared for issues, artifacts, tests, and reflections.</p>
    </article>
  </div>

  <h2>Working agreements</h2>
  <ul class="team-agreements">
    <li>Every issue has one clear owner and one verifiable done condition.</li>
    <li>Each member keeps no more than one card in <strong>Doing</strong>.</li>
    <li>Blocked work is labeled and includes a comment explaining the blocker.</li>
    <li>Implementation changes use a branch and pull request before merging.</li>
  </ul>
</div>

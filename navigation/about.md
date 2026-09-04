---
layout: post
title: Team
permalink: /about/
comments: true
show_reading_time: false
---

<style>
.team-page {
  --team-bg: #0f1623;
  --team-panel: #151e2d;
  --team-panel-soft: #111a28;
  --team-line: rgba(255, 255, 255, 0.12);
  --team-text: #f7f9fc;
  --team-muted: #b5c0d2;
  --team-accent: #73e0c1;
  --team-accent-2: #8eb8ff;
  max-width: 1120px;
  margin: 0 auto;
  color: var(--team-text);
}
.team-page * {
  box-sizing: border-box;
}
.team-header {
  position: relative;
  overflow: hidden;
  padding: clamp(2rem, 7vw, 4.75rem);
  border: 1px solid var(--team-line);
  border-radius: 24px;
  background:
    radial-gradient(circle at 92% 12%, rgba(115, 224, 193, 0.2), transparent 32%),
    radial-gradient(circle at 8% 100%, rgba(142, 184, 255, 0.12), transparent 35%),
    linear-gradient(145deg, #172235, var(--team-bg));
}
.team-kicker,
.team-label {
  margin: 0 0 0.7rem;
  color: var(--team-accent);
  font-size: 0.78rem;
  font-weight: 850;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}
.team-header h1 {
  max-width: 760px;
  margin: 0;
  font-size: clamp(2.35rem, 7vw, 4.8rem);
  line-height: 1;
  letter-spacing: -0.05em;
}
.team-intro {
  max-width: 760px;
  margin: 1.25rem 0 0;
  color: var(--team-muted);
  font-size: 1.07rem;
  line-height: 1.72;
}
.team-links,
.member-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.7rem;
}
.team-links {
  margin-top: 1.55rem;
}
.team-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 42px;
  padding: 0.55rem 1rem;
  border: 1px solid var(--team-line);
  border-radius: 999px;
  color: var(--team-text) !important;
  background: rgba(255, 255, 255, 0.04);
  font-weight: 800;
  text-decoration: none !important;
  transition: transform 160ms ease, border-color 160ms ease, background 160ms ease;
}
.team-link.primary {
  border-color: transparent;
  color: #071611 !important;
  background: var(--team-accent);
}
.team-link:hover {
  transform: translateY(-2px);
  border-color: rgba(115, 224, 193, 0.65);
  background: rgba(115, 224, 193, 0.08);
}
.team-link.primary:hover {
  background: #8aebcf;
}
.team-link:focus-visible,
.member-link:focus-visible {
  outline: 3px solid var(--team-accent-2);
  outline-offset: 3px;
}
.team-section {
  margin: clamp(2.8rem, 7vw, 5rem) 0;
}
.team-section-head {
  max-width: 760px;
  margin-bottom: 1.35rem;
}
.team-section h2 {
  margin: 0 0 0.65rem;
  font-size: clamp(1.7rem, 4vw, 2.5rem);
  letter-spacing: -0.03em;
}
.team-section-head p,
.member-card p,
.team-note p,
.team-agreement p,
.team-agreement li,
.team-done li,
.team-table td {
  color: var(--team-muted);
  line-height: 1.62;
}
.member-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}
.member-card {
  display: flex;
  min-height: 100%;
  flex-direction: column;
  padding: 1.3rem;
  border: 1px solid var(--team-line);
  border-radius: 20px;
  background: linear-gradient(155deg, var(--team-panel), var(--team-panel-soft));
}
.member-top {
  display: flex;
  gap: 0.95rem;
  align-items: center;
  margin-bottom: 1rem;
}
.member-avatar {
  width: 68px;
  height: 68px;
  flex: 0 0 68px;
  border: 2px solid rgba(115, 224, 193, 0.65);
  border-radius: 18px;
  object-fit: cover;
  background: #0b1220;
}
.member-role {
  margin: 0 0 0.28rem !important;
  color: var(--team-accent) !important;
  font-size: 0.78rem;
  font-weight: 850;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}
.member-card h3 {
  margin: 0;
  font-size: 1.35rem;
  line-height: 1.2;
}
.member-focus {
  flex: 1;
  margin: 0 0 1.2rem;
}
.member-focus strong {
  color: var(--team-text);
}
.member-link {
  display: inline-flex;
  align-items: center;
  min-height: 38px;
  padding: 0.35rem 0.75rem;
  border: 1px solid var(--team-line);
  border-radius: 10px;
  color: var(--team-accent-2) !important;
  font-weight: 800;
  text-decoration: none !important;
}
.member-link:hover {
  border-color: var(--team-accent-2);
  background: rgba(142, 184, 255, 0.08);
}
.team-split {
  display: grid;
  grid-template-columns: 1.08fr 0.92fr;
  gap: 1rem;
}
.team-note,
.team-agreement,
.team-done {
  padding: 1.35rem;
  border: 1px solid var(--team-line);
  border-radius: 18px;
  background: var(--team-panel);
}
.team-note h3,
.team-agreement h3,
.team-done h3 {
  margin: 0 0 0.65rem;
}
.team-agreement {
  border-left: 4px solid var(--team-accent);
  border-radius: 0 18px 18px 0;
}
.team-agreement ol,
.team-done ul {
  margin-bottom: 0;
  padding-left: 1.25rem;
}
.team-agreement li,
.team-done li {
  margin: 0.5rem 0;
}
.team-table-wrap {
  overflow-x: auto;
  border: 1px solid var(--team-line);
  border-radius: 18px;
}
.team-table {
  width: 100%;
  min-width: 720px;
  margin: 0;
  border-collapse: collapse;
  background: var(--team-panel-soft);
}
.team-table th,
.team-table td {
  padding: 0.9rem;
  border-bottom: 1px solid var(--team-line);
  text-align: left;
  vertical-align: top;
}
.team-table th {
  color: var(--team-accent);
  font-size: 0.78rem;
  letter-spacing: 0.07em;
  text-transform: uppercase;
}
.team-table tr:last-child td {
  border-bottom: 0;
}
.team-status {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}
.team-status strong {
  display: block;
  margin-bottom: 0.35rem;
  color: var(--team-text);
}
@media (max-width: 820px) {
  .member-grid,
  .team-split,
  .team-status {
    grid-template-columns: 1fr;
  }
  .team-header {
    padding: 1.6rem;
  }
}
@media (prefers-reduced-motion: reduce) {
  .team-link {
    transition: none;
  }
  .team-link:hover {
    transform: none;
  }
}
</style>

<div class="team-page">
  <header class="team-header">
    <p class="team-kicker">AP CSP · 2026–2027</p>
    <h1>Three teammates. One shared standard for the work.</h1>
    <p class="team-intro">
      We are documenting our SFI Foundation capstone planning in public: who owns
      each task, how decisions are made, and what evidence shows that work is complete.
      Every member develops, researches, tests, and reviews.
    </p>
    <nav class="team-links" aria-label="Team workspace links">
      <a class="team-link primary" href="https://github.com/users/ruhaanb622/projects/1/views/1">Open Kanban board</a>
      <a class="team-link" href="{{ '/sfi-ideation/' | relative_url }}">View SFI ideation</a>
      <a class="team-link" href="{{ '/collaboration/' | relative_url }}">Collaboration evidence</a>
      <a class="team-link" href="https://github.com/ruhaanb622/group-portfolio">GitHub repository</a>
    </nav>
  </header>

  <section class="team-section" aria-labelledby="members-title">
    <div class="team-section-head">
      <p class="team-label">Team members</p>
      <h2 id="members-title">Clear roles without separate silos</h2>
      <p>
        Roles describe each person's current focus, not a limit on participation.
        All three members contribute technical work and review one another's evidence.
      </p>
    </div>

    <div class="member-grid">
      <article class="member-card">
        <div class="member-top">
          <img class="member-avatar" src="https://github.com/ruhaanb622.png?size=160" alt="Ruhaan Bansal's GitHub avatar" loading="lazy">
          <div>
            <p class="member-role">Scrum Master · Developer</p>
            <h3>Ruhaan Bansal</h3>
          </div>
        </div>
        <p class="member-focus">
          <strong>Current focus:</strong> Ideas 1 and 4, board coordination,
          issue quality, integration planning, and peer review.
        </p>
        <div class="member-links">
          <a class="member-link" href="https://github.com/ruhaanb622">GitHub</a>
          <a class="member-link" href="https://ruhaanb622.github.io/portfolio/">Portfolio</a>
        </div>
      </article>

      <article class="member-card">
        <div class="member-top">
          <img class="member-avatar" src="https://github.com/aRYA622-y.png?size=160" alt="Arya Taghavi Zargar's GitHub avatar" loading="lazy">
          <div>
            <p class="member-role">Technologist · Developer</p>
            <h3>Arya Taghavi Zargar</h3>
          </div>
        </div>
        <p class="member-focus">
          <strong>Current focus:</strong> Ideas 2 and 5, verification language,
          manufacturer workflow research, and implementation evidence.
        </p>
        <div class="member-links">
          <a class="member-link" href="https://github.com/aRYA622-y">GitHub</a>
          <a class="member-link" href="https://arya622-y.github.io/portfolio/">Portfolio</a>
        </div>
      </article>

      <article class="member-card">
        <div class="member-top">
          <img class="member-avatar" src="https://github.com/DrDeyar.png?size=160" alt="Deyar Raissadat's GitHub avatar" loading="lazy">
          <div>
            <p class="member-role">Technologist · Developer</p>
            <h3>Deyar Raissadat</h3>
          </div>
        </div>
        <p class="member-focus">
          <strong>Current focus:</strong> Ideas 3 and 6, mobile accessibility,
          learning-flow research, storyboard testing, and implementation evidence.
        </p>
        <div class="member-links">
          <a class="member-link" href="https://github.com/DrDeyar">GitHub</a>
          <a class="member-link" href="https://drdeyar.github.io/portfolio/">Portfolio</a>
        </div>
      </article>
    </div>
  </section>

  <section class="team-section" aria-labelledby="ownership-title">
    <div class="team-section-head">
      <p class="team-label">Shared responsibility</p>
      <h2 id="ownership-title">How the team divides and verifies work</h2>
      <p>
        Each task has one owner, but important decisions and completion evidence
        are reviewed across the team.
      </p>
    </div>

    <div class="team-table-wrap">
      <table class="team-table">
        <thead>
          <tr>
            <th>Area</th>
            <th>Primary owner</th>
            <th>Team contribution</th>
            <th>Evidence</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Board and planning</td>
            <td>Ruhaan</td>
            <td>Arya and Deyar update their own active cards and blockers.</td>
            <td>Kanban status, issue ownership, and check-in comments</td>
          </tr>
          <tr>
            <td>Research and storyboards</td>
            <td>Assigned idea owner</td>
            <td>Another member reviews clarity, safety limits, and feasibility.</td>
            <td>Issue deliverable, sources, visual, and peer-feedback thread</td>
          </tr>
          <tr>
            <td>Testing</td>
            <td>Feature owner</td>
            <td>A teammate performs the walkthrough or reproduces the test.</td>
            <td>Expected-versus-observed results and documented revision</td>
          </tr>
          <tr>
            <td>Future implementation</td>
            <td>Assigned developer</td>
            <td>The team reviews integration, accessibility, and acceptance criteria.</td>
            <td>Issue-linked commits, tests, review, and demonstration</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <section class="team-section" aria-labelledby="workflow-title">
    <div class="team-section-head">
      <p class="team-label">Workflow</p>
      <h2 id="workflow-title">Simple rules that keep ownership visible</h2>
    </div>

    <div class="team-split">
      <article class="team-agreement">
        <h3>Working agreement</h3>
        <ol>
          <li>Every task has one owner and begins with an action verb.</li>
          <li>Every issue states one deliverable and a verifiable done condition.</li>
          <li>Each member keeps no more than one card in <strong>Doing</strong>.</li>
          <li>Blocked work receives a comment that names the blocker and next action.</li>
          <li>Research and ideation stay separate from product implementation.</li>
          <li>Members update their active card during each team check-in.</li>
          <li>Important work receives peer feedback before it is marked complete.</li>
        </ol>
      </article>

      <article class="team-done">
        <h3>Definition of done</h3>
        <ul>
          <li>The promised deliverable exists.</li>
          <li>The acceptance checklist is satisfied.</li>
          <li>Sources, screenshots, notes, or tests are linked.</li>
          <li>Another teammate can review or reproduce the result.</li>
          <li>Feedback and revisions are documented.</li>
          <li>The Kanban item is moved to <strong>Done</strong>.</li>
        </ul>
      </article>
    </div>
  </section>

  <section class="team-section" aria-labelledby="decisions-title">
    <div class="team-section-head">
      <p class="team-label">Decision record</p>
      <h2 id="decisions-title">What the team has—and has not—decided</h2>
    </div>

    <div class="team-status">
      <article class="team-note">
        <strong>Confirmed · September 2, 2026</strong>
        <h3>SFI Foundation capstone</h3>
        <p>
          The team confirmed SFI Foundation as its 2026–2027 nonprofit capstone
          context and began documenting six independent directions.
        </p>
      </article>
      <article class="team-note">
        <strong>Current boundary</strong>
        <h3>Evidence before implementation</h3>
        <p>
          The team is using research, storyboards, peer tests, and discussion to
          justify a direction before beginning product development.
        </p>
      </article>
    </div>
  </section>
</div>

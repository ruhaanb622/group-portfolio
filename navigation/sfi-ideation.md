---
layout: post
title: SFI Foundation Ideation — 2026–2027
permalink: /sfi-ideation/
comments: true
show_reading_time: false
---

<style>
.sfi-page {
  --ink: #f7f9fc;
  --muted: #b7c1d1;
  --panel: #141b27;
  --panel-2: #101722;
  --line: rgba(255, 255, 255, 0.12);
  --cyan: #6fe4e8;
  --lime: #b6ef72;
  --orange: #ffb66e;
  max-width: 1120px;
  margin: 0 auto;
  color: var(--ink);
}
.sfi-hero {
  position: relative;
  overflow: hidden;
  padding: clamp(2rem, 7vw, 4.8rem);
  border: 1px solid var(--line);
  border-radius: 24px;
  background:
    radial-gradient(circle at 92% 8%, rgba(111, 228, 232, 0.19), transparent 34%),
    linear-gradient(140deg, #141d2c 0%, #10151f 72%);
}
.sfi-kicker,
.idea-number,
.sfi-label {
  margin: 0 0 0.65rem;
  color: var(--cyan);
  font-size: 0.76rem;
  font-weight: 850;
  letter-spacing: 0.13em;
  text-transform: uppercase;
}
.sfi-hero h1 {
  max-width: 820px;
  margin: 0;
  font-size: clamp(2.25rem, 6vw, 4.6rem);
  line-height: 1.02;
  letter-spacing: -0.045em;
}
.sfi-hero-copy {
  max-width: 760px;
  margin: 1.25rem 0 0;
  color: var(--muted);
  font-size: 1.06rem;
  line-height: 1.72;
}
.sfi-status {
  display: inline-flex;
  gap: 0.55rem;
  align-items: center;
  margin-top: 1.4rem;
  padding: 0.55rem 0.85rem;
  border: 1px solid rgba(182, 239, 114, 0.38);
  border-radius: 999px;
  color: var(--lime);
  background: rgba(182, 239, 114, 0.08);
  font-weight: 800;
}
.sfi-status::before {
  width: 0.55rem;
  height: 0.55rem;
  border-radius: 50%;
  background: var(--lime);
  content: "";
}
.sfi-section {
  margin: clamp(2.7rem, 6vw, 5rem) 0;
}
.sfi-section-head {
  max-width: 760px;
  margin-bottom: 1.3rem;
}
.sfi-section h2 {
  margin: 0 0 0.65rem;
  font-size: clamp(1.65rem, 4vw, 2.4rem);
  letter-spacing: -0.025em;
}
.sfi-section-head p,
.sfi-note p,
.sfi-card p,
.sfi-card li,
.sfi-callout p,
.sfi-footer-note {
  color: var(--muted);
  line-height: 1.62;
}
.sfi-facts,
.sfi-team,
.sfi-grid {
  display: grid;
  gap: 1rem;
}
.sfi-facts,
.sfi-team {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}
.sfi-grid {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}
.sfi-card,
.sfi-note,
.sfi-callout {
  border: 1px solid var(--line);
  border-radius: 18px;
  background: var(--panel);
}
.sfi-card {
  padding: 1.3rem;
}
.sfi-card h3 {
  margin: 0 0 0.7rem;
  font-size: 1.28rem;
}
.sfi-card h4 {
  margin: 1.15rem 0 0.45rem;
  color: var(--ink);
  font-size: 0.92rem;
}
.sfi-card ul,
.sfi-card ol {
  padding-left: 1.2rem;
}
.sfi-card li {
  margin: 0.38rem 0;
}
.sfi-owner {
  display: inline-block;
  margin: 0 0 0.9rem;
  padding: 0.25rem 0.58rem;
  border-radius: 7px;
  color: var(--lime);
  background: rgba(182, 239, 114, 0.09);
  font-size: 0.8rem;
  font-weight: 800;
}
.sfi-link {
  display: inline-flex;
  margin-top: 0.8rem;
  color: var(--cyan) !important;
  font-weight: 800;
  text-decoration: none !important;
}
.sfi-note {
  padding: 1.2rem;
}
.sfi-note strong {
  color: var(--ink);
}
.sfi-callout {
  padding: 1.35rem 1.45rem;
  border-left: 4px solid var(--orange);
  border-radius: 0 18px 18px 0;
}
.sfi-callout h3 {
  margin-top: 0;
}
.sfi-table-wrap {
  overflow-x: auto;
  border: 1px solid var(--line);
  border-radius: 16px;
}
.sfi-table {
  width: 100%;
  min-width: 720px;
  margin: 0;
  border-collapse: collapse;
  background: var(--panel-2);
}
.sfi-table th,
.sfi-table td {
  padding: 0.85rem;
  border-bottom: 1px solid var(--line);
  text-align: left;
  vertical-align: top;
}
.sfi-table th {
  color: var(--cyan);
  font-size: 0.78rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
}
.sfi-table td {
  color: var(--muted);
}
.sfi-table tr:last-child td {
  border-bottom: 0;
}
.sfi-sources {
  columns: 2 280px;
  column-gap: 2rem;
}
.sfi-sources li {
  margin: 0 0 0.75rem;
  break-inside: avoid;
}
@media (max-width: 800px) {
  .sfi-facts,
  .sfi-team,
  .sfi-grid {
    grid-template-columns: 1fr;
  }
  .sfi-hero {
    padding: 1.5rem;
  }
}
</style>

<div class="sfi-page">
  <header class="sfi-hero">
    <p class="sfi-kicker">2026–2027 · Initial Ideation</p>
    <h1>Six directions for SFI Foundation web modernization</h1>
    <p class="sfi-hero-copy">
      We are exploring how people could find, understand, and verify motorsports
      safety information more easily. These are independent discussion directions,
      not promised features. Our next step is stakeholder conversation and comparison,
      not implementation.
    </p>
    <div class="sfi-status">Ideation only — nothing selected or built</div>
  </header>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Confirmed context</p>
      <h2>What we know now</h2>
      <p>
        Our organization is confirmed, but our exact user, problem statement, and
        product function are still open. The previous Greppers team provides a useful
        starting point that we must understand before choosing what to explore further.
      </p>
    </div>
    <div class="sfi-facts">
      <article class="sfi-note">
        <strong>Organization</strong>
        <p>SFI Foundation, a nonprofit focused on standards for motorsports safety equipment.</p>
      </article>
      <article class="sfi-note">
        <strong>Modernization themes</strong>
        <p>Specification discovery, manufacturer information, and a clearer mobile experience.</p>
      </article>
      <article class="sfi-note">
        <strong>Current boundary</strong>
        <p>Research, storyboards, questions, and discussion only. No product code or OCS changes.</p>
      </article>
    </div>
  </section>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Team</p>
      <h2>Ownership for the first ideation pass</h2>
    </div>
    <div class="sfi-team">
      <article class="sfi-card">
        <h3>Ruhaan Bansal</h3>
        <p>Scrum Master / Developer</p>
        <p>Ideas 1 and 4; board coordination and decision-record consistency.</p>
      </article>
      <article class="sfi-card">
        <h3>Arya Taghavi Zargar</h3>
        <p>Technologist / Developer</p>
        <p>Ideas 2 and 5; verification language and manufacturer workflow research.</p>
      </article>
      <article class="sfi-card">
        <h3>Deyar Raissadat</h3>
        <p>Technologist / Developer</p>
        <p>Ideas 3 and 6; mobile accessibility and learning-flow research.</p>
      </article>
    </div>
  </section>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Six independent directions</p>
      <h2>Storyboard starters</h2>
      <p>
        Each outline follows the plagiarism-storyboard guide: gain attention,
        overview, a sequence using text/visual/audio/interaction, a guiding question,
        and an application or feedback step.
      </p>
    </div>

    <div class="sfi-grid">
      <article class="sfi-card">
        <p class="idea-number">Idea 01 · Search</p>
        <h3>Plain-language SFI Spec Compass</h3>
        <span class="sfi-owner">Owner: Ruhaan</span>
        <p><strong>User and need:</strong> A racer or crew member has a practical question but does not know a specification number or formal term.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> “Which rule applies to my equipment?”</li>
          <li><strong>Overview:</strong> Explain that results guide discovery and link back to official source material.</li>
          <li><strong>Text + visual:</strong> A plain-language question becomes grouped result cards with spec number, topic, and source.</li>
          <li><strong>Audio:</strong> Optional read-aloud summary for trackside or accessibility use.</li>
          <li><strong>Interaction:</strong> Refine by equipment, racing category, or question intent.</li>
          <li><strong>Application:</strong> User saves the official reference and rates whether the result answered the question.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>How can search be useful without presenting an AI summary as an official interpretation?</p>
        <p><strong>Difference to investigate:</strong> More traceable answers and source-first result design than a general prototype search.</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/9">Discuss in issue #9 →</a>
      </article>

      <article class="sfi-card">
        <p class="idea-number">Idea 02 · Verification</p>
        <h3>SFI QR Participation Checker</h3>
        <span class="sfi-owner">Owner: Arya</span>
        <p><strong>User and need:</strong> A buyer, racer, or inspector wants quick access to manufacturer and program reference information.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> “What can this code reliably tell me?”</li>
          <li><strong>Overview:</strong> Set expectations about participation checks versus certification or endorsement.</li>
          <li><strong>Text + visual:</strong> A scan opens a high-contrast status page showing the manufacturer, relevant program, source, and last update.</li>
          <li><strong>Audio:</strong> Optional spoken status and warning language.</li>
          <li><strong>Interaction:</strong> Scan a QR code or enter its identifier manually.</li>
          <li><strong>Application:</strong> User opens the official reference or reports missing/inconsistent information.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>Which facts can SFI authorize the site to verify, and which claims must the interface avoid?</p>
        <p><strong>Safety boundary:</strong> A participation record does not authenticate the scanned item or show that it will pass inspection. The result repeats the matched manufacturer, specification, label date, source, and source-check date.</p>
        <p><strong>Peer update:</strong> The result now says “Participation record found” instead of the unclear word “Listed.”</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/10">Discuss in issue #10 →</a>
      </article>

      <article class="sfi-card">
        <p class="idea-number">Idea 03 · Mobile workflow</p>
        <h3>Trackside Inspector Mode</h3>
        <span class="sfi-owner">Owner: Deyar</span>
        <p><strong>User and need:</strong> An inspector needs fast, readable reference access while using a phone in a noisy, bright environment.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> A time-limited equipment check at the track.</li>
          <li><strong>Overview:</strong> Choose equipment type and the reference task to perform.</li>
          <li><strong>Text + visual:</strong> Large controls, short check steps, clear warnings, and direct links to full specifications.</li>
          <li><strong>Audio:</strong> Optional hands-free step reading with captions and mute control.</li>
          <li><strong>Interaction:</strong> Tap through a checklist, enlarge diagrams, and mark items for follow-up.</li>
          <li><strong>Application:</strong> Export personal notes without claiming an official pass/fail decision.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>What information do inspectors need in the first 30 seconds, and what must remain in the official document?</p>
        <p><strong>Difference to investigate:</strong> A constrained field workflow rather than a general responsive redesign.</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/11">Discuss in issue #11 →</a>
      </article>

      <article class="sfi-card">
        <p class="idea-number">Idea 04 · Lifecycle</p>
        <h3>Inspection and Recertification Timeline</h3>
        <span class="sfi-owner">Owner: Ruhaan</span>
        <p><strong>User and need:</strong> An equipment owner wants to understand time-based inspection or recertification information without missing an important step.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> “What should I check before my next event?”</li>
          <li><strong>Overview:</strong> Select the equipment category and locate its official requirements.</li>
          <li><strong>Text + visual:</strong> A timeline separates purchase, inspection, service, and reference dates.</li>
          <li><strong>Audio:</strong> Optional accessible explanation of each timeline milestone.</li>
          <li><strong>Interaction:</strong> Add a private reminder and open the relevant manufacturer or specification page.</li>
          <li><strong>Application:</strong> User confirms the next action and can correct an incorrect assumption.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>Can reliable date rules be sourced consistently enough to support reminders without giving unsafe advice?</p>
        <p><strong>Data question:</strong> Determine which schedules are public, stable, and appropriate for a non-authoritative reminder tool.</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/12">Discuss in issue #12 →</a>
      </article>

      <article class="sfi-card">
        <p class="idea-number">Idea 05 · Operations</p>
        <h3>Manufacturer Submission and Review Portal</h3>
        <span class="sfi-owner">Owner: Arya</span>
        <p><strong>User and need:</strong> A participating manufacturer or SFI reviewer wants a clearer, traceable exchange of information.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> A submission is delayed because a required item is unclear.</li>
          <li><strong>Overview:</strong> Show role, submission stage, and the next required action.</li>
          <li><strong>Text + visual:</strong> A simple status strip shows the submission, version, current step, and next person responsible.</li>
          <li><strong>Audio:</strong> Optional notification reading; no audio required for core use.</li>
          <li><strong>Interaction:</strong> One fake manufacturer uploads sample files and one reviewer requests changes or records a decision.</li>
          <li><strong>Application:</strong> Both parties confirm that the same record and next action are visible.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>What real workflow exists today, and would a student-built prototype address a meaningful bottleneck?</p>
        <p><strong>Classroom scope:</strong> Use one fake manufacturer, one reviewer, sample files, and three states: Draft, Changes Needed, and Decision Recorded. Real authentication, private storage, licensing, and retention rules stay outside the prototype.</p>
        <p><strong>Peer update:</strong> Screens 3–5 now repeat the record, version, status, and next owner. “Finished” was replaced with “Decision Recorded / Review Closed.”</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/13">Discuss in issue #13 →</a>
      </article>

      <article class="sfi-card">
        <p class="idea-number">Idea 06 · Learning</p>
        <h3>Motorsports Safety Learning Hub</h3>
        <span class="sfi-owner">Owner: Deyar</span>
        <p><strong>User and need:</strong> A new racer, student, or volunteer wants to learn how specifications, labels, manufacturers, and inspections relate.</p>
        <h4>Storyboard</h4>
        <ol>
          <li><strong>Gain attention:</strong> Compare two realistic equipment-information scenarios.</li>
          <li><strong>Overview:</strong> Introduce one concept at a time with a visible learning path.</li>
          <li><strong>Text + visual:</strong> Short cards, annotated diagrams, vocabulary, and source links.</li>
          <li><strong>Audio:</strong> Narration with transcript, speed, and mute controls.</li>
          <li><strong>Interaction:</strong> Make a choice, explain the reasoning, and receive source-based feedback.</li>
          <li><strong>Application:</strong> Complete a scenario and identify where to verify the answer officially.</li>
        </ol>
        <h4>Guiding question</h4>
        <p>Which misconceptions create the most risk for beginners, and how should SFI review educational wording?</p>
        <p><strong>Difference to investigate:</strong> Structured learning outcomes and scenario feedback rather than a general information page.</p>
        <a class="sfi-link" href="https://github.com/ruhaanb622/group-portfolio/issues/14">Discuss and test in issue #14 →</a>
      </article>
    </div>
  </section>

  <section class="sfi-section">
    <div class="sfi-callout">
      <h3>Important accuracy boundary</h3>
      <p>
        SFI states that participating manufacturers certify that their products
        comply with a program. A manufacturer listing or digital lookup must not be
        represented as SFI endorsement, recommendation, or an automatic certification
        decision. Any future wording and data flow would require stakeholder review.
      </p>
    </div>
  </section>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Inherited context</p>
      <h2>Questions for the previous Greppers team</h2>
      <p>
        Before narrowing the six ideas, we plan to talk with the creators of the
        previous page and prototype. Contact has not yet been recorded; the discussion checklist is tracked inside <a href="https://github.com/ruhaanb622/group-portfolio/issues/8">Big Issue #8</a>.
      </p>
    </div>
    <div class="sfi-grid">
      <article class="sfi-card">
        <h3>What already works?</h3>
        <ul>
          <li>Which search, photo-identification, account, and admin flows are functional?</li>
          <li>Which parts are demonstrations, mocked data, or incomplete?</li>
          <li>What setup, deployment, or data assumptions are undocumented?</li>
        </ul>
      </article>
      <article class="sfi-card">
        <h3>What did you learn?</h3>
        <ul>
          <li>Which users or SFI contacts gave feedback?</li>
          <li>What accuracy, permissions, or data-quality problems appeared?</li>
          <li>If you restarted, which problem would you prioritize and why?</li>
        </ul>
      </article>
    </div>
    <p class="sfi-footer-note">
      Starting references: <a href="https://pages.opencodingsociety.com/capstone/greppers/">current Greppers capstone page</a>
      and <a href="https://github.com/TheGreppers/greppers/issues/23">previous-team handoff issue</a>. Follow-up notes will be recorded in <a href="https://github.com/ruhaanb622/group-portfolio/issues/8">Big Issue #8</a>.
      We will ask before reusing code or assets and preserve attribution.
    </p>
  </section>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Decision process</p>
      <h2>How we will compare the six ideas</h2>
      <p>No scores have been invented. The team will add evidence and discuss each criterion before making a selection.</p>
    </div>
    <div class="sfi-table-wrap">
      <table class="sfi-table">
        <thead>
          <tr>
            <th>Criterion</th>
            <th>Question</th>
            <th>Evidence to collect</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Stakeholder value</td>
            <td>Does this solve a problem SFI and a specific user actually have?</td>
            <td>Stakeholder and previous-team feedback</td>
          </tr>
          <tr>
            <td>Safety + accuracy</td>
            <td>Can claims be sourced, limited, and reviewed responsibly?</td>
            <td>Official sources and content boundaries</td>
          </tr>
          <tr>
            <td>Data availability</td>
            <td>Is the necessary information accessible, current, and permitted?</td>
            <td>Sample fields, ownership, and update process</td>
          </tr>
          <tr>
            <td>Feasibility</td>
            <td>Can three developers create and test a focused version?</td>
            <td>Smallest useful scope and major dependencies</td>
          </tr>
          <tr>
            <td>Learning + originality</td>
            <td>Does it extend prior work and provide meaningful CSP challenges?</td>
            <td>Comparison with the inherited prototype</td>
          </tr>
          <tr>
            <td>Accessibility</td>
            <td>Will it work on mobile and for users with different access needs?</td>
            <td>WCAG-informed storyboard review</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <section class="sfi-section">
    <div class="sfi-section-head">
      <p class="sfi-label">Sources and tracking</p>
      <h2>Where this ideation is grounded</h2>
    </div>
    <ul class="sfi-sources">
      <li><a href="https://pages.opencodingsociety.com/capstone/greppers/">OCS SFI / Greppers capstone page</a></li>
      <li><a href="https://pages.opencodingsociety.com/capstone/">OCS capstone index</a></li>
      <li><a href="https://pages.opencodingsociety.com/english/plagiarism/storyboard/">OCS plagiarism storyboard guide</a></li>
      <li><a href="https://sfifoundation.com/about-sfi-foundation/">SFI Foundation overview</a></li>
      <li><a href="https://sfifoundation.com/specifications-participating-manufacturers/">SFI specifications and participating manufacturers</a></li>
      <li><a href="https://github.com/ruhaanb622/group-portfolio/issues/8">Team ideation tracker, issue #8</a></li>
    </ul>
  </section>
</div>


<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>S.Sujith for Vice Captain — Yellow House 2026</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Space+Grotesk:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  :root {
    --yellow: #FFCE00;
    --yellow-soft: #FFF3C4;
    --yellow-deep: #C99700;
    --ink: #2B2410;
    --cream: #FFFDF6;
    --white: #FFFFFF;
    --line: rgba(43, 36, 16, 0.14);
    --shadow-hard: 6px 6px 0 var(--ink);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }

  body {
    background: var(--cream);
    color: var(--ink);
    font-family: 'Space Grotesk', sans-serif;
    line-height: 1.5;
    overflow-x: hidden;
  }

  h1, h2, h3, .display {
    font-family: 'Times new roman', sans-serif;
    text-transform: uppercase;
    line-height: 1.02;
    letter-spacing: -0.01em;
  }

  .mono { font-family: 'JetBrains Mono', monospace; }
  a { color: inherit; }

  @media (prefers-reduced-motion: reduce) {
    * { animation: none !important; transition: none !important; }
  }

  /* ---------- Nav ---------- */
  nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background: var(--cream);
    border-bottom: 3px solid var(--ink);
    padding: 14px 28px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .nav-mark {
    font-family: 'Archivo Black', sans-serif;
    font-size: 1.1rem;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .nav-mark .box {
    width: 22px; height: 22px;
    background: var(--yellow);
    border: 2.5px solid var(--ink);
    display: inline-block;
  }
  nav ul { list-style: none; display: flex; gap: 26px; }
  nav a {
    text-decoration: none;
    font-weight: 600;
    font-size: 0.82rem;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    padding-bottom: 3px;
    border-bottom: 2px solid transparent;
    transition: border-color 0.15s ease;
  }
  nav a:hover, nav a:focus-visible { border-color: var(--ink); }
  .nav-cta {
    background: var(--ink);
    color: var(--yellow) !important;
    padding: 9px 18px;
    border: 2px solid var(--ink);
  }
  .nav-cta:hover { background: var(--yellow); color: var(--ink) !important; }
  @media (max-width: 860px) { nav ul { display: none; } }

  /* ---------- Hero ---------- */
  .hero {
    position: relative;
    padding: 70px 28px 60px;
    background: var(--yellow-soft);
    border-bottom: 4px solid var(--ink);
    overflow: hidden;
  }
  .hero-grid {
    max-width: 1160px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1.15fr 0.85fr;
    gap: 40px;
    align-items: center;
    position: relative;
    z-index: 2;
  }
  .date-tag {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: var(--white);
    color: var(--ink);
    border: 2px solid var(--ink);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    padding: 7px 14px;
    margin-bottom: 22px;
    letter-spacing: 0.04em;
  }
  .date-tag .dot {
    width: 8px; height: 8px; border-radius: 50%;
    background: var(--yellow-deep);
    animation: blink 1.6s infinite;
  }
  @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0.25; } }

  .hero h1 { font-size: clamp(2.6rem, 6vw, 4.6rem); margin-bottom: 6px; }
  .hero h1 span {
    -webkit-text-stroke: 2px var(--ink);
    color: var(--yellow);
  }
  .hero .role-line {
    font-size: clamp(1.1rem, 2.4vw, 1.5rem);
    font-weight: 700;
    margin-bottom: 18px;
  }
  .hero .slogan {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.95rem;
    font-weight: 700;
    background: var(--ink);
    color: var(--yellow);
    display: inline-block;
    padding: 10px 16px;
    margin-bottom: 22px;
  }
  .hero p.lede { font-size: 1.05rem; max-width: 48ch; margin-bottom: 30px; }
  .hero-actions { display: flex; gap: 14px; flex-wrap: wrap; }

  .btn {
    display: inline-block;
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 700;
    font-size: 0.95rem;
    text-decoration: none;
    padding: 15px 28px;
    border: 2.5px solid var(--ink);
    cursor: pointer;
    transition: transform 0.12s ease, box-shadow 0.12s ease;
  }
  .btn-primary { background: var(--ink); color: var(--yellow); box-shadow: var(--shadow-hard); }
  .btn-primary:hover { transform: translate(-3px, -3px); box-shadow: 9px 9px 0 var(--ink); }
  .btn-secondary { background: var(--white); color: var(--ink); }
  .btn-secondary:hover { background: var(--ink); color: var(--yellow); }

  /* Ballot card visual */
  .ballot-card {
    background: var(--white);
    border: 3px solid var(--ink);
    box-shadow: var(--shadow-hard);
    padding: 26px;
    transform: rotate(-2deg);
    font-family: 'JetBrains Mono', monospace;
  }
  .ballot-card .head {
    display: flex; justify-content: space-between;
    font-size: 0.7rem; text-transform: uppercase;
    border-bottom: 2px dashed var(--line);
    padding-bottom: 10px; margin-bottom: 14px;
    letter-spacing: 0.05em;
  }
  .ballot-row { display: flex; align-items: center; gap: 14px; padding: 12px 0; border-bottom: 1px solid var(--line); }
  .ballot-row:last-child { border: none; }
  .checkbox {
    width: 26px; height: 26px;
    border: 2.5px solid var(--ink);
    flex-shrink: 0;
    display: flex; align-items: center; justify-content: center;
    font-weight: 900;
  }
  .checkbox.checked { background: var(--yellow); }
  .ballot-row .name { font-family: 'Space Grotesk', sans-serif; font-weight: 700; font-size: 1rem; }
  .ballot-row .house-tag { font-size: 0.68rem; opacity: 0.65; }

  /* ---------- Section shell ---------- */
  section { padding: 80px 28px; }
  .wrap { max-width: 1160px; margin: 0 auto; }
  .eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: var(--yellow-deep);
    margin-bottom: 10px;
    display: block;
  }
  .section-title { font-size: clamp(1.9rem, 4vw, 2.8rem); margin-bottom: 18px; }
  .section-intro { max-width: 62ch; font-size: 1.05rem; color: var(--ink); opacity: 0.75; margin-bottom: 48px; }

  /* ---------- Promises (Unity / Initiative / Dedication) ---------- */
  .promise-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 24px;
  }
  .promise-card {
    background: var(--white);
    border: 3px solid var(--ink);
    padding: 30px;
    box-shadow: var(--shadow-hard);
  }
  .promise-card .tag {
    display: inline-block;
    background: var(--yellow);
    border: 2px solid var(--ink);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    text-transform: uppercase;
    padding: 4px 10px;
    margin-bottom: 16px;
  }
  .promise-card h3 { font-size: 1.3rem; margin-bottom: 12px; }
  .promise-card p { font-size: 0.95rem; opacity: 0.8; }

  /* ---------- Five Ways / Pillars ---------- */
  .pillar-list { display: flex; flex-direction: column; }
  .pillar-row {
    display: grid;
    grid-template-columns: 70px 200px 1fr;
    gap: 20px;
    align-items: center;
    padding: 26px 0;
    border-bottom: 2px solid var(--line);
  }
  .pillar-row:first-child { border-top: 2px solid var(--line); }
  .pillar-row .num {
    font-family: 'Archivo Black', sans-serif;
    font-size: 2rem;
    color: var(--yellow-deep);
    -webkit-text-stroke: 1.2px var(--ink);
  }
  .pillar-row h3 { font-size: 1.15rem; text-transform: uppercase; }
  .pillar-row p { font-size: 0.95rem; opacity: 0.8; }
  @media (max-width: 700px) {
    .pillar-row { grid-template-columns: 50px 1fr; }
    .pillar-row h3 { grid-column: 2; }
    .pillar-row p { grid-column: 1 / -1; }
  }

  /* ---------- Plan / steps ---------- */
  .plan-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 0;
    border-top: 3px solid var(--ink);
    border-left: 3px solid var(--ink);
  }
  .plan-step {
    background: var(--white);
    border-right: 3px solid var(--ink);
    border-bottom: 3px solid var(--ink);
    padding: 28px 22px;
    transition: background 0.15s ease;
  }
  .plan-step:hover { background: var(--yellow-soft); }
  .plan-step .step-no {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    color: var(--yellow-deep);
    margin-bottom: 10px;
    display: block;
  }
  .plan-step h4 { font-size: 1rem; font-family: 'Space Grotesk', sans-serif; font-weight: 700; margin-bottom: 8px; }
  .plan-step p { font-size: 0.88rem; opacity: 0.8; }

  /* ---------- Vote CTA ---------- */
  .vote-cta {
    background: var(--yellow);
    text-align: center;
    border-top: 4px solid var(--ink);
    border-bottom: 4px solid var(--ink);
  }
  .vote-cta p { max-width: 56ch; margin: 0 auto 30px; opacity: 0.85; }
  .grade-row { display: flex; justify-content: center; align-items: center; gap: 14px; margin-bottom: 30px; flex-wrap: wrap; }
  .grade-box {
    width: 52px; height: 52px;
    background: var(--white);
    border: 3px solid var(--ink);
    display: flex; align-items: center; justify-content: center;
    font-family: 'Archivo Black', sans-serif;
    font-size: 1.2rem;
  }
  .final-slogan {
    font-family: 'Archivo Black', sans-serif;
    text-transform: uppercase;
    font-size: clamp(1.3rem, 3vw, 2rem);
    margin: 30px auto 10px;
    max-width: 20ch;
  }

  /* ---------- Footer ---------- */
  footer {
    padding: 34px 28px;
    text-align: center;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    opacity: 0.7;
  }
</style>
</head>
<body>

<nav>
  <div class="nav-mark"><span class="box"></span> SUJITH · YELLOW HOUSE</div>
  <ul>
    <li><a href="#promises">Promises</a></li>
    <li><a href="#pillars">Five Ways</a></li>
    <li><a href="#plan">The Plan</a></li>
    <li><a href="#vote" class="nav-cta">Vote Now</a></li>
  </ul>
</nav>

<header class="hero">
  <div class="hero-grid">
    <div>
      <div class="date-tag"><span class="dot"></span> ELECTION DAY · 11 JULY · YELLOW HOUSE 2026</div>
      <h1>VOTE <span>SUJITH</span><br>FOR VICE&nbsp;CAPTAIN</h1>
      <p class="role-line">Grade 6–12 · Yellow House Council</p>
      <div class="slogan">"Together We Lead, Together We Win."</div>
      <p class="lede">11th of July is the day Yellow House decides its next leader. Here is exactly what I promise, in simple, doable steps — for every grade, from 6 to 12.</p>
      <div class="hero-actions">
        <a href="#promises" class="btn btn-primary">See My Promises</a>
        <a href="#vote" class="btn btn-secondary">How to Vote</a>
      </div>
    </div>
    <div class="ballot-card">
      <div class="head"><span>Ballot · 11 July</span><span>Vice Captain</span></div>
      <div class="ballot-row">
        <div class="checkbox checked">✓</div>
        <div>
          <div class="name">Sujith</div>
          <div class="house-tag">Yellow House</div>
        </div>
      </div>
      <div class="ballot-row" style="opacity:0.4">
        <div class="checkbox"></div>
        <div><div class="name">Candidate B</div><div class="house-tag">—</div></div>
      </div>
      <div class="ballot-row" style="opacity:0.4">
        <div class="checkbox"></div>
        <div><div class="name">Candidate C</div><div class="house-tag">—</div></div>
      </div>
    </div>
  </div>
</header>

<section id="promises">
  <div class="wrap">
    <span class="eyebrow">My Promise</span>
    <h2 class="section-title">Unity. Initiative. Dedication.</h2>
    <p class="section-intro">Three simple promises I will keep to every student in Yellow House, from Grade 6 to Grade 12.</p>
    <div class="promise-grid">
      <div class="promise-card">
        <span class="tag">Unity</span>
        <h3>A Strong Bond, Together</h3>
        <p>I will build a strong bond within our team, so every member of Yellow House — junior or senior — feels like they truly belong.</p>
      </div>
      <div class="promise-card">
        <span class="tag">Initiative</span>
        <h3>New Ideas, Real Action</h3>
        <p>I will bring new ideas and take action for our team's success, instead of waiting for problems to solve themselves.</p>
      </div>
      <div class="promise-card">
        <span class="tag">Dedication</span>
        <h3>Always Listening, Always There</h3>
        <p>I will listen, support, and give my best for our team, always — in every event, every practice, every day.</p>
      </div>
    </div>
  </div>
</section>

<section id="pillars" style="background: var(--yellow-soft); border-top: 4px solid var(--ink); border-bottom: 4px solid var(--ink);">
  <div class="wrap">
    <span class="eyebrow">The Five Ways</span>
    <h2 class="section-title">Simple Steps, In Order.</h2>
    <p class="section-intro">Five areas, five simple promises — things I can actually do, starting on day one.</p>
    <div class="pillar-list">
      <div class="pillar-row">
        <div class="num">01</div>
        <h3>Arokya</h3>
        <p>Check in on how members are feeling, encourage water and rest breaks, and make sure no one hesitates to ask for support.</p>
      </div>
      <div class="pillar-row">
        <div class="num">02</div>
        <h3>Attitude</h3>
        <p>Support every member with a positive attitude, respect everyone equally, and lead by setting a good example myself.</p>
      </div>
      <div class="pillar-row">
        <div class="num">03</div>
        <h3>Academic</h3>
        <p>Support each other in studies, encourage seniors to guide juniors, and build simple habits of helping one another before exams.</p>
      </div>
      <div class="pillar-row">
        <div class="num">04</div>
        <h3>Artistic</h3>
        <p>Encourage members to share their talents — art, music, dance — and support them with simple opportunities to be seen and appreciated.</p>
      </div>
      <div class="pillar-row">
        <div class="num">05</div>
        <h3>Athletic</h3>
        <p>Support fair practice time for everyone, encourage teamwork over competition within the house, and cheer on every member equally.</p>
      </div>
    </div>
  </div>
</section>

<section id="plan">
  <div class="wrap">
    <span class="eyebrow">The Plan</span>
    <h2 class="section-title">How This Actually Happens.</h2>
    <p class="section-intro">A simple, step-by-step plan built on better communication — nothing complicated, just consistent effort.</p>
    <div class="plan-grid">
      <div class="plan-step">
        <span class="step-no">Step 1</span>
        <h4>Listen First</h4>
        <p>Talk to members across grades 6–12 and understand what Yellow House actually needs.</p>
      </div>
      <div class="plan-step">
        <span class="step-no">Step 2</span>
        <h4>Open Communication</h4>
        <p>Keep a simple, regular way for members to share ideas or concerns with the house council.</p>
      </div>
      <div class="plan-step">
        <span class="step-no">Step 3</span>
        <h4>Support Each Pillar</h4>
        <p>Give steady, simple support across Arokya, Attitude, Academic, Artistic, and Athletic — every week.</p>
      </div>
      <div class="plan-step">
        <span class="step-no">Step 4</span>
        <h4>Show Up, Every Time</h4>
        <p>Be present and dependable at every practice, event, and meeting — not just during elections.</p>
      </div>
    </div>
  </div>
</section>

<section id="vote" class="vote-cta">
  <div class="wrap">
    <span class="eyebrow" style="color:var(--ink);">Election Day · 11 July</span>
    <h2 class="section-title">Grade 6 to 12 — This Is Your Decision.</h2>
    <p>On the 11th of July, every student in Yellow House — from the youngest in Grade 6 to the seniors in Grade 12 — gets one vote. Use it for a Vice Captain who has written down simple, real promises and will show up every day to keep them.</p>
    <div class="grade-row">
      <div class="grade-box">6</div><div class="grade-box">7</div><div class="grade-box">8</div>
      <div class="grade-box">9</div><div class="grade-box">10</div><div class="grade-box">11</div><div class="grade-box">12</div>
    </div>
    <a href="#" class="btn btn-primary">I'm Voting for Sujith on 11 July</a>
    <div class="final-slogan">Let's Lead. Let's Win.<br>Let's Make Our House Proud.</div>
  </div>
</section>

<footer>
  YELLOW HOUSE · VICE CAPTAIN ELECTION · 11 JULY 2026 · S.SUJITH FOR YELLOW HOUSE
</footer>

</body>
</html>

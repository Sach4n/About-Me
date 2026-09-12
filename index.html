<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sebastian Jay Victoria — Video Editor</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #14171B;
    --bg-raised: #1B1F24;
    --line: #2B3036;
    --text: #ECEDEE;
    --muted: #8A939E;
    --teal: #2FBFA6;
    --orange: #E8843B;
  }

  *{ box-sizing: border-box; margin:0; padding:0; }

  html{ scroll-behavior: smooth; }

  body{
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }

  a{ color: inherit; }

  .wrap{
    max-width: 880px;
    margin: 0 auto;
    padding: 0 28px;
  }

  .mono{
    font-family: 'IBM Plex Mono', monospace;
    letter-spacing: 0.02em;
  }

  /* ---- timeline ruler, used as a recurring motif ---- */
  .ruler{
    width: 100%;
    height: 22px;
    display: flex;
    align-items: flex-end;
    gap: 0;
    overflow: hidden;
    border-bottom: 1px solid var(--line);
  }
  .ruler span{
    flex: 1 0 auto;
    width: 1px;
    height: 8px;
    background: var(--line);
  }
  .ruler span:nth-child(5n+1){ height: 14px; background: var(--muted); }

  /* ---- header / nav ---- */
  header{
    padding-top: 20px;
  }
  .nav{
    display:flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 0;
    font-size: 0.85rem;
    color: var(--muted);
  }
  .nav .id{ color: var(--text); font-weight: 500; }
  .nav a{ text-decoration:none; color: var(--muted); margin-left: 24px; transition: color .15s ease; }
  .nav a:hover{ color: var(--teal); }

  /* ---- hero ---- */
  .hero{
    padding: 72px 0 64px;
    border-bottom: 1px solid var(--line);
  }
  .timecode{
    display:flex;
    align-items:center;
    gap: 10px;
    color: var(--teal);
    font-size: 0.8rem;
    margin-bottom: 22px;
  }
  .timecode .dot{
    width: 7px; height: 7px; border-radius: 50%;
    background: var(--orange);
    box-shadow: 0 0 0 3px rgba(232,132,59,0.15);
  }
  h1{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    font-size: clamp(2.4rem, 6vw, 3.6rem);
    line-height: 1.08;
    letter-spacing: -0.01em;
  }
  .role{
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.15rem;
    color: var(--orange);
    margin-top: 10px;
    font-weight: 500;
  }
  .bio{
    max-width: 60ch;
    color: var(--muted);
    font-size: 1.05rem;
    margin-top: 26px;
  }
  .hero-links{
    display:flex;
    gap: 14px;
    margin-top: 34px;
    flex-wrap: wrap;
  }
  .btn{
    display:inline-flex;
    align-items:center;
    gap: 8px;
    padding: 11px 20px;
    border-radius: 4px;
    text-decoration:none;
    font-size: 0.9rem;
    font-weight: 500;
    border: 1px solid var(--line);
    transition: border-color .15s ease, background .15s ease;
  }
  .btn.solid{
    background: var(--teal);
    color: #0D1512;
    border-color: var(--teal);
  }
  .btn.solid:hover{ background: #38D6BB; }
  .btn.ghost:hover{ border-color: var(--muted); background: var(--bg-raised); }

  /* ---- section scaffolding ---- */
  section{
    padding: 56px 0;
    border-bottom: 1px solid var(--line);
  }
  section:last-of-type{ border-bottom: none; }

  .label{
    font-size: 0.75rem;
    color: var(--muted);
    margin-bottom: 18px;
  }
  .label .n{ color: var(--orange); }

  h2{
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.5rem;
    font-weight: 600;
    margin-bottom: 20px;
  }

  /* ---- credit strip ---- */
  .credit{
    display:flex;
    align-items:center;
    gap: 14px;
    color: var(--muted);
    font-size: 0.92rem;
  }
  .credit strong{ color: var(--text); font-weight: 600; }
  .credit .bar{
    width: 30px; height: 1px; background: var(--line);
  }

  /* ---- skills ---- */
  .skills-grid{
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
  }
  .skill-col h3{
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.95rem;
    font-weight: 600;
    color: var(--teal);
    margin-bottom: 14px;
  }
  .skill-col ul{ list-style:none; }
  .skill-col li{
    padding: 10px 0;
    border-top: 1px solid var(--line);
    color: var(--muted);
    font-size: 0.95rem;
    display:flex;
    justify-content: space-between;
    align-items:center;
  }
  .skill-col li:last-child{ }
  .skill-col li span.tc{
    font-family:'IBM Plex Mono', monospace;
    font-size: 0.72rem;
    color: var(--line);
  }

  @media (max-width: 640px){
    .skills-grid{ grid-template-columns: 1fr; gap: 8px; }
  }

  /* ---- contact ---- */
  .contact-row{
    display:flex;
    flex-direction: column;
    gap: 2px;
  }
  .contact-link{
    display:flex;
    justify-content: space-between;
    align-items:center;
    padding: 18px 0;
    border-top: 1px solid var(--line);
    text-decoration:none;
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.1rem;
    font-weight: 500;
    color: var(--text);
    transition: color .15s ease;
  }
  .contact-row .contact-link:last-child{ border-bottom: 1px solid var(--line); }
  .contact-link:hover{ color: var(--teal); }
  .contact-link .arrow{
    font-family: 'IBM Plex Mono', monospace;
    color: var(--muted);
    font-size: 0.85rem;
    transition: transform .15s ease;
  }
  .contact-link:hover .arrow{ transform: translateX(3px); color: var(--teal); }

  footer{
    padding: 30px 0 50px;
    color: var(--line);
    font-size: 0.78rem;
    display:flex;
    justify-content: space-between;
  }

  @media (prefers-reduced-motion: reduce){
    html{ scroll-behavior: auto; }
    *{ transition: none !important; }
  }
</style>
</head>
<body>

<div class="ruler" id="ruler"></div>

<div class="wrap">
  <header>
    <div class="nav">
      <div class="id mono">SJV / REEL</div>
      <div>
        <a href="#work">About</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </header>

  <section class="hero">
    <div class="timecode mono"><span class="dot"></span>00:00:00:01 — NOW PLAYING</div>
    <h1>Sebastian Jay<br>Victoria</h1>
    <div class="role">Video Editor</div>
    <p class="bio">As an editor with over four years of experience — including cutting content for Bike Check PH — I craft high-retention short-form videos and product showcases that drive engagement. By blending a solid background in marketing strategy with precision editing, I transform raw footage into compelling digital narratives.</p>
    <div class="hero-links">
      <a class="btn solid" href="mailto:vsebastianjay@gmail.com">Email me</a>
      <a class="btn ghost" href="https://www.linkedin.com/in/sj-victoria/" target="_blank" rel="noopener">LinkedIn ↗</a>
    </div>
  </section>

  <section id="work">
    <div class="label mono"><span class="n">01</span> — CREDITS</div>
    <div class="credit">
      <strong>Bike Check PH</strong>
      <div class="bar"></div>
      <span>Ongoing editing work — short-form &amp; product showcase content</span>
    </div>
  </section>

  <section id="skills">
    <div class="label mono"><span class="n">02</span> — SKILLS</div>
    <div class="skills-grid">
      <div class="skill-col">
        <h3>Editing</h3>
        <ul>
          <li>Short-form &amp; long-form editing <span class="tc">A1</span></li>
          <li>Color grading &amp; correction <span class="tc">A2</span></li>
          <li>Sound design &amp; mixing <span class="tc">A3</span></li>
          <li>Motion graphics &amp; titling <span class="tc">A4</span></li>
          <li>Pacing &amp; story structure for retention <span class="tc">A5</span></li>
        </ul>
      </div>
      <div class="skill-col">
        <h3>Marketing</h3>
        <ul>
          <li>Content &amp; campaign strategy <span class="tc">B1</span></li>
          <li>Audience &amp; retention analytics <span class="tc">B2</span></li>
          <li>Brand storytelling <span class="tc">B3</span></li>
          <li>Platform-native content planning <span class="tc">B4</span></li>
        </ul>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="label mono"><span class="n">03</span> — CONTACT</div>
    <div class="contact-row">
      <a class="contact-link" href="mailto:vsebastianjay@gmail.com">
        vsebastianjay@gmail.com <span class="arrow mono">SEND →</span>
      </a>
      <a class="contact-link" href="https://www.linkedin.com/in/sj-victoria/" target="_blank" rel="noopener">
        LinkedIn / sj-victoria <span class="arrow mono">OPEN →</span>
      </a>
    </div>
  </section>

  <footer class="mono">
    <span>© 2026 Sebastian Jay Victoria</span>
    <span>END OF REEL</span>
  </footer>
</div>

<script>
  // build the ruler tick marks
  const ruler = document.getElementById('ruler');
  const count = 90;
  for(let i=0;i<count;i++){
    const s = document.createElement('span');
    ruler.appendChild(s);
  }
</script>

</body>
</html>

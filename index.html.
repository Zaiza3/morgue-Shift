
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MORGUE SHIFT | Can We Survive the Night?</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Orbitron:wght@500;600;700;800;900&display=swap" rel="stylesheet">

<style>
:root {
  --red: #c51f32;
  --bright: #f02b43;
  --dark: #080808;
  --panel: #111113;
  --muted: #a5a5a5;
  --white: #f5f5f5;
  --border: rgba(220, 40, 60, .3);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  background: var(--dark);
  color: var(--white);
  font-family: 'Inter', sans-serif;
  line-height: 1.6;
}

a {
  color: inherit;
  text-decoration: none;
}

button, a {
  -webkit-tap-highlight-color: transparent;
}

nav {
  position: sticky;
  top: 0;
  z-index: 1000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 17px 7%;
  background: rgba(5,5,5,.96);
  border-bottom: 1px solid var(--border);
  backdrop-filter: blur(12px);
}

.logo {
  font-family: 'Orbitron', sans-serif;
  font-size: 19px;
  font-weight: 900;
  letter-spacing: 2px;
}

.logo span {
  color: var(--bright);
}

.nav-links {
  display: flex;
  gap: 22px;
  align-items: center;
}

.nav-links a {
  font-size: 12px;
  color: #ccc;
  transition: .3s;
}

.nav-links a:hover {
  color: var(--bright);
}

.menu-button {
  display: none;
  background: none;
  border: 1px solid var(--border);
  color: white;
  padding: 8px 12px;
  font-size: 18px;
}

.ticker {
  background: #a91629;
  padding: 8px 12px;
  text-align: center;
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 2px;
}

.hero {
  min-height: 610px;
  padding: 100px 8%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(ellipse at center, rgba(150,15,30,.25), transparent 65%),
    linear-gradient(180deg, #10090b, #080808 90%);
}

.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(
    0deg,
    transparent,
    transparent 3px,
    rgba(255,255,255,.015) 4px
  );
  pointer-events: none;
}

.eyebrow {
  color: var(--bright);
  font-size: 11px;
  letter-spacing: 5px;
  font-weight: 800;
  margin-bottom: 18px;
}

.hero h1 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(45px, 9vw, 100px);
  font-weight: 900;
  letter-spacing: 5px;
  line-height: 1.1;
  text-shadow: 0 0 35px rgba(240,43,67,.3);
}

.hero h1 span {
  color: var(--bright);
}

.hero h2 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(13px, 2vw, 19px);
  letter-spacing: 5px;
  margin-top: 22px;
  color: #ddd;
}

.hero p {
  color: #aaa;
  max-width: 570px;
  margin-top: 22px;
  font-size: 14px;
}

.primary-button {
  display: inline-block;
  margin-top: 32px;
  padding: 13px 25px;
  background: var(--red);
  color: white;
  font-size: 11px;
  font-weight: 800;
  letter-spacing: 2px;
  border: 1px solid var(--bright);
  transition: .3s;
}

.primary-button:hover {
  background: var(--bright);
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(240,43,67,.2);
}

section {
  padding: 85px 8%;
  scroll-margin-top: 70px;
}

.section-heading {
  text-align: center;
  margin-bottom: 42px;
}

.section-heading .eyebrow {
  margin-bottom: 8px;
}

.section-heading h2 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(25px, 4vw, 38px);
  letter-spacing: 2px;
}

.section-heading p {
  color: var(--muted);
  font-size: 13px;
  max-width: 600px;
  margin: 12px auto 0;
}

.about-grid {
  display: grid;
  grid-template-columns: 1.2fr .8fr;
  gap: 25px;
  max-width: 1050px;
  margin: auto;
}

.panel {
  background: var(--panel);
  border: 1px solid var(--border);
  padding: 30px;
  position: relative;
}

.panel h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 16px;
  margin-bottom: 15px;
  color: var(--bright);
}

.panel p {
  font-size: 13px;
  color: #bbb;
}

.info-list {
  list-style: none;
  margin-top: 15px;
}

.info-list li {
  padding: 9px 0;
  font-size: 12px;
  border-bottom: 1px solid #292929;
  color: #ccc;
}

.info-list strong {
  color: white;
}

.players-panel {
  max-width: 850px;
  margin: auto;
  text-align: center;
  padding: 48px 25px;
  background:
    linear-gradient(135deg, rgba(130,15,30,.15), transparent),
    var(--panel);
  border: 1px solid var(--border);
}

.players-panel h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(20px, 4vw, 30px);
  letter-spacing: 2px;
}

.players-panel p {
  max-width: 540px;
  margin: 12px auto 0;
  color: #aaa;
  font-size: 13px;
}

.player-status {
  display: inline-block;
  margin-top: 22px;
  padding: 8px 15px;
  border: 1px solid var(--border);
  color: var(--bright);
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 2px;
}

.timeline {
  max-width: 850px;
  margin: auto;
}

.timeline-item {
  display: grid;
  grid-template-columns: 125px 1fr;
  gap: 20px;
  padding: 19px 22px;
  border-left: 2px solid var(--red);
  border-bottom: 1px solid #252525;
  background: rgba(255,255,255,.018);
  transition: .3s;
}

.timeline-item:hover {
  background: rgba(190,25,45,.09);
  transform: translateX(4px);
}

.time {
  font-family: 'Orbitron', sans-serif;
  color: var(--bright);
  font-size: 12px;
  font-weight: 700;
}

.timeline-item h3 {
  font-size: 14px;
  margin-bottom: 4px;
}

.timeline-item p {
  color: var(--muted);
  font-size: 11px;
}

.video-section {
  background: #0d0d0f;
}

.video-placeholder {
  max-width: 850px;
  width: 100%;
  aspect-ratio: 16 / 9;
  margin: 35px auto 0;
  background: #101010;
  border: 1px solid #87303a;
  overflow: hidden;
  position: relative;
  box-shadow: 0 0 35px rgba(180,20,40,.12);
}

.video-placeholder iframe {
  display: block;
  width: 100%;
  height: 100%;
  border: 0;
}

.video-caption {
  text-align: center;
  margin-top: 17px;
  font-size: 11px;
  color: #888;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
  max-width: 1100px;
  margin: auto;
}

.feature-card {
  background: var(--panel);
  border: 1px solid #292929;
  padding: 25px 18px;
  transition: .3s;
}

.feature-card:hover {
  border-color: var(--red);
  transform: translateY(-5px);
}

.feature-number {
  font-family: 'Orbitron', sans-serif;
  color: var(--bright);
  font-size: 23px;
  font-weight: 900;
}

.feature-card h3 {
  font-size: 13px;
  margin: 12px 0 7px;
}

.feature-card p {
  font-size: 11px;
  color: #999;
}

.safety-box {
  max-width: 900px;
  margin: auto;
  padding: 35px;
  border: 1px solid var(--border);
  background: linear-gradient(120deg, rgba(150,15,30,.12), #111);
}

.safety-box h3 {
  font-family: 'Orbitron', sans-serif;
  font-size: 19px;
  margin-bottom: 20px;
  color: var(--bright);
}

.safety-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
}

.safety-item {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  padding: 13px;
  background: rgba(255,255,255,.035);
}

.safety-item span {
  color: var(--bright);
  font-weight: 900;
}

.safety-item p {
  font-size: 12px;
  color: #ccc;
}

.download-section {
  text-align: center;
  background: #0d0d0f;
}

.download-section p {
  max-width: 560px;
  margin: 15px auto 0;
  color: #aaa;
  font-size: 13px;
}

.final-section {
  min-height: 390px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  background:
    radial-gradient(ellipse at center, rgba(160,15,35,.2), transparent 70%),
    #080808;
}

.final-section h2 {
  font-family: 'Orbitron', sans-serif;
  font-size: clamp(28px, 6vw, 58px);
  letter-spacing: 4px;
}

.final-section h2 span {
  color: var(--bright);
}

.final-section p {
  margin-top: 15px;
  color: #999;
  font-size: 12px;
  letter-spacing: 3px;
}

footer {
  padding: 25px 8%;
  border-top: 1px solid var(--border);
  text-align: center;
  color: #777;
  font-size: 10px;
  letter-spacing: 1px;
}

footer strong {
  color: var(--bright);
}

@media (max-width: 850px) {
  .nav-links {
    gap: 12px;
  }

  .nav-links a {
    font-size: 10px;
  }

  .feature-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 650px) {
  nav {
    padding: 14px 5%;
    flex-wrap: wrap;
  }

  .logo {
    font-size: 16px;
  }

  .menu-button {
    display: block;
  }

  .nav-links {
    display: none;
    width: 100%;
    flex-direction: column;
    align-items: flex-start;
    padding-top: 15px;
    gap: 0;
  }

  .nav-links.active {
    display: flex;
  }

  .nav-links a {
    width: 100%;
    padding: 11px 0;
    border-top: 1px solid #222;
    font-size: 12px;
  }

  .hero {
    min-height: 540px;
    padding: 80px 6%;
  }

  section {
    padding: 65px 6%;
  }

  .about-grid {
    grid-template-columns: 1fr;
  }

  .timeline-item {
    grid-template-columns: 1fr;
    gap: 6px;
    padding: 17px;
  }

  .safety-grid {
    grid-template-columns: 1fr;
  }

  .feature-grid {
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }

  .feature-card {
    padding: 20px 13px;
  }

  .safety-box {
    padding: 22px;
  }
}

@media (max-width: 380px) {
  .feature-grid {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<nav>
  <a href="#home" class="logo">MORGUE<span> SHIFT</span></a>

  <button class="menu-button" onclick="toggleMenu()" aria-label="Open navigation menu">☰</button>

  <div class="nav-links" id="navLinks">
    <a href="#about" onclick="closeMenu()">ABOUT</a>
    <a href="#players" onclick="closeMenu()">PLAYERS</a>
    <a href="#timeline" onclick="closeMenu()">STREAM FLOW</a>
    <a href="#promo" onclick="closeMenu()">PROMO VIDEO</a>
    <a href="#experience" onclick="closeMenu()">EXPERIENCE</a>
    <a href="#safety" onclick="closeMenu()">SAFETY</a>
  </div>
</nav>

<div class="ticker">
  ⚠ NIGHT SHIFT NOTICE — KEEP YOUR EYES OPEN. THE NIGHT IS NOT OVER. ⚠
</div>

<header class="hero" id="home">
  <div class="eyebrow">WELCOME TO THE NIGHT SHIFT</div>

  <h1>MORGUE<br><span>SHIFT</span></h1>

  <h2>CAN WE SURVIVE THE NIGHT?</h2>

  <p>
    The lights are on. The doors are locked.
    Something feels wrong tonight. Step into the shift and find out
    what happens when the night takes an unexpected turn.
  </p>

  <a href="#about" class="primary-button">ENTER THE EXPERIENCE</a>
</header>

<section id="about">
  <div class="section-heading">
    <div class="eyebrow">01 / THE BRIEFING</div>
    <h2>ABOUT THE SHIFT</h2>
    <p>Before the night begins, here's what you need to know.</p>
  </div>

  <div class="about-grid">
    <div class="panel">
      <h3>THE EXPERIENCE</h3>
      <p>
        MORGUE SHIFT is a Roblox horror gaming experience that follows
        a night filled with suspense, unexpected encounters, and
        challenging moments. Players must stay alert, work together,
        and respond to whatever the shift brings.
      </p>
      <br>
      <p>
        This experience brings together gameplay, teamwork, audience
        interaction, and entertainment in one recorded stream presentation.
      </p>
    </div>

    <div class="panel">
      <h3>SHIFT INFORMATION</h3>
      <ul class="info-list">
        <li><strong>Experience:</strong> Roblox Horror</li>
        <li><strong>Title:</strong> MORGUE SHIFT</li>
        <li><strong>Format:</strong> Recorded Livestream-Style Presentation</li>
        <li><strong>Duration:</strong> Approximately 13 minutes</li>
        <li><strong>Theme:</strong> Suspense, Survival & Teamwork</li>
      </ul>
    </div>
  </div>
</section>

<section id="players">
  <div class="section-heading">
    <div class="eyebrow">02 / THE CREW</div>
    <h2>JOIN THE PLAYERS</h2>
    <p>Every shift takes teamwork. Every decision matters.</p>
  </div>

  <div class="players-panel">
    <h3>YOUR NIGHT SHIFT STARTS HERE.</h3>
    <p>
      Get ready to follow the players as they enter the morgue,
      face unexpected situations, and work together throughout
      the night. Stay tuned for the experience.
    </p>
    <div class="player-status">PLAYER DETAILS COMING SOON</div>
  </div>
</section>

<section id="timeline">
  <div class="section-heading">
    <div class="eyebrow">03 / THE PROGRAM</div>
    <h2>THE NIGHT'S TIMELINE</h2>
    <p>A look at how the experience unfolds from beginning to end.</p>
  </div>

  <div class="timeline">

    <div class="timeline-item">
      <div class="time">00:00–00:30</div>
      <div>
        <h3>Online Safety Reminder</h3>
        <p>A quick reminder about responsible and respectful online behavior.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">00:30–01:30</div>
      <div>
        <h3>Starting Soon & Introduction</h3>
        <p>Set the atmosphere and introduce the MORGUE SHIFT experience.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">01:30–03:00</div>
      <div>
        <h3>Game Overview & Player Introduction</h3>
        <p>Explore the game premise and prepare for the night shift.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">03:00–05:00</div>
      <div>
        <h3>Gameplay Segment 1</h3>
        <p>Enter the game and experience the first set of challenges.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">05:00–06:30</div>
      <div>
        <h3>Morgue Shift Feature</h3>
        <p>A closer look at a featured part of the gaming experience.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">06:30–08:45</div>
      <div>
        <h3>Gameplay Segment 2</h3>
        <p>Continue the shift and face more unexpected moments.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">08:45–10:15</div>
      <div>
        <h3>Chat & Q&A</h3>
        <p>Respond to simulated audience questions and reactions.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">10:15–11:00</div>
      <div>
        <h3>Audio Adjustment</h3>
        <p>Address a simulated audio concern and make adjustments.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">11:00–12:30</div>
      <div>
        <h3>Final Gameplay & Recap</h3>
        <p>Return to the game and look back at the night's highlights.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="time">12:30–13:30</div>
      <div>
        <h3>Outro</h3>
        <p>Close the experience and thank the audience for joining the shift.</p>
      </div>
    </div>

  </div>
</section>

<section class="video-section" id="promo">
  <div class="section-heading">
    <div class="eyebrow">04 / THE FIRST LOOK</div>
    <h2>WATCH THE PROMO</h2>
    <p>Get a glimpse of what awaits inside MORGUE SHIFT.</p>
  </div>

  <div class="video-placeholder">
    <iframe
      src="https://www.youtube.com/embed/R9RKnezUAnA"
      title="MORGUE SHIFT Promotional Video"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen>
    </iframe>
  </div>

  <p class="video-caption">
    MORGUE SHIFT — OFFICIAL PROMOTIONAL VIDEO
  </p>
</section>

<section id="experience">
  <div class="section-heading">
    <div class="eyebrow">05 / WHAT AWAITS</div>
    <h2>WHAT TO EXPECT</h2>
    <p>More than just a night in the morgue.</p>
  </div>

  <div class="feature-grid">

    <div class="feature-card">
      <div class="feature-number">01</div>
      <h3>HORROR GAMEPLAY</h3>
      <p>Experience suspenseful moments and unexpected encounters.</p>
    </div>

    <div class="feature-card">
      <div class="feature-number">02</div>
      <h3>TEAMWORK</h3>
      <p>See how players communicate and cooperate throughout the shift.</p>
    </div>

    <div class="feature-card">
      <div class="feature-number">03</div>
      <h3>UNEXPECTED MOMENTS</h3>
      <p>Prepare for surprises that make every part of the experience different.</p>
    </div>

    <div class="feature-card">
      <div class="feature-number">04</div>
      <h3>AUDIENCE INTERACTION</h3>
      <p>Follow simulated chat reactions, questions, and responses.</p>
    </div>

  </div>
</section>

<section id="safety">
  <div class="section-heading">
    <div class="eyebrow">06 / RESPONSIBLE PLAY</div>
    <h2>STAY SAFE ONLINE</h2>
    <p>Enjoy the experience while remembering that online safety always matters.</p>
  </div>

  <div class="safety-box">
    <h3>PLAY SMART. STAY SAFE.</h3>

    <div class="safety-grid">
      <div class="safety-item">
        <span>01</span>
        <p><strong>RESPECT OTHERS</strong><br>Be respectful when communicating and playing with others.</p>
      </div>

      <div class="safety-item">
        <span>02</span>
        <p><strong>PROTECT YOUR PRIVACY</strong><br>Never share personal or sensitive information online.</p>
      </div>

      <div class="safety-item">
        <span>03</span>
        <p><strong>ASK BEFORE SHARING</strong><br>Respect consent before sharing someone's photos, videos, or information.</p>
      </div>

      <div class="safety-item">
        <span>04</span>
        <p><strong>REPORT INAPPROPRIATE BEHAVIOR</strong><br>Use the platform's reporting tools when something feels unsafe.</p>
      </div>
    </div>
  </div>
</section>

<section class="download-section">
  <div class="section-heading">
    <div class="eyebrow">READY TO ENTER?</div>
    <h2>GET ROBLOX</h2>
    <p>
      MORGUE SHIFT is experienced through Roblox.
      Visit the official Roblox website to learn more and download the platform.
    </p>

    <a
      href="https://www.roblox.com/download"
      target="_blank"
      rel="noopener noreferrer"
      class="primary-button">
      DOWNLOAD ROBLOX
    </a>
  </div>
</section>

<section class="final-section">
  <div class="eyebrow">THE SHIFT IS ALMOST HERE</div>
  <h2>MORGUE <span>SHIFT</span></h2>
  <p>CAN YOU SURVIVE THE NIGHT?</p>
  <div class="player-status">COMING SOON</div>
</section>

<footer>
  <p><strong>MORGUE SHIFT</strong> &nbsp; | &nbsp; CAN WE SURVIVE THE NIGHT?</p>
  <p style="margin-top:7px;">Stay alert. Stay together. See you on the night shift.</p>
</footer>

<script>
function toggleMenu() {
  document.getElementById("navLinks").classList.toggle("active");
}

function closeMenu() {
  document.getElementById("navLinks").classList.remove("active");
}
</script>

</body>
</html>


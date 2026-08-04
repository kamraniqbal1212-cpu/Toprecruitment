<!DOCTYPE html>
<html lang="en-GB">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Top Recruitment | Electricians, Gas Engineers &amp; HGV Drivers</title>
  <meta name="description" content="Top Recruitment places vetted electricians, gas engineers and HGV drivers with employers across the UK. Cards, tickets and licences checked at source.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Barlow:wght@500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
  <link rel="icon" href="img/favicon.svg" type="image/svg+xml">
  <style>
/* ==========================================================================
   TOP RECRUITMENT — stylesheet
   --------------------------------------------------------------------------
   BRAND COLOURS: change the five values below to match Top Boiler Care.
   Everything on the site is driven from them.
   ========================================================================== */

:root {
  --brand-dark:   #0a0a0a;   /* black — primary surface, header, hero, footer */
  --brand-card:   #1a1a1a;   /* raised black — cards on dark */
  --brand-mid:    #2d7ff9;   /* blue — links, focus, icons */
  --brand-accent: #f5c518;   /* safety yellow — CTAs, rules, numerals */
  --brand-accent-hover: #ffd740; /* yellow hover */
  --brand-light:  #f5f5f5;   /* app background, pale sections */
  --brand-line:   #e0e0e0;   /* borders and dividers */

  /* Neutrals */
  --ink:      #333333;   /* body text */
  --ink-soft: #6b6b6b;   /* muted text */
  --white:    #ffffff;

  /* Type */
  --font-display: 'Barlow', 'Helvetica Neue', Arial, sans-serif;
  --font-body: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;

  /* Layout */
  --wrap: 1140px;
  --radius: 6px;
}

/* ---------- Base ---------- */

*, *::before, *::after { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  font-family: var(--font-body);
  font-size: 17px;
  line-height: 1.65;
  color: var(--ink);
  background: var(--white);
  -webkit-font-smoothing: antialiased;
}

h1, h2, h3, h4 {
  font-family: var(--font-display);
  font-weight: 700;
  line-height: 1.15;
  color: var(--brand-dark);
  margin: 0 0 .6em;
  letter-spacing: -0.01em;
}

h1 { font-size: clamp(2.1rem, 4.6vw, 3.3rem); }
h2 { font-size: clamp(1.6rem, 3vw, 2.2rem); }
h3 { font-size: 1.2rem; }

p { margin: 0 0 1.1em; }
p:last-child { margin-bottom: 0; }

a { color: var(--brand-mid); }

img { max-width: 100%; display: block; }

.wrap {
  width: 100%;
  max-width: var(--wrap);
  margin: 0 auto;
  padding: 0 24px;
}

.section { padding: 76px 0; }
.section--tint { background: var(--brand-light); }
.section--tight { padding: 56px 0; }

.lead {
  font-size: 1.12rem;
  color: var(--ink-soft);
  max-width: 62ch;
}

.eyebrow {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: .82rem;
  letter-spacing: .16em;
  text-transform: uppercase;
  color: var(--ink-soft);
  margin: 0 0 .7em;
}
.eyebrow::before {
  content: "";
  display: inline-block;
  width: 22px;
  height: 3px;
  background: var(--brand-accent);
  vertical-align: middle;
  margin-right: 10px;
  margin-bottom: 3px;
}

.section-head { max-width: 62ch; margin-bottom: 40px; }

/* ---------- Buttons ---------- */

.btn {
  display: inline-block;
  font-family: var(--font-display);
  font-weight: 600;
  font-size: 1rem;
  letter-spacing: .01em;
  padding: 13px 26px;
  border-radius: var(--radius);
  text-decoration: none;
  border: 2px solid transparent;
  cursor: pointer;
  transition: background-color .15s ease, color .15s ease, border-color .15s ease;
}

.btn--primary { background: var(--brand-accent); color: #0a0a0a; }
.btn--primary:hover { background: var(--brand-accent-hover); }

.btn--dark { background: var(--brand-dark); color: var(--white); }
.btn--dark:hover { background: var(--brand-card); }

.btn--ghost { border-color: rgba(255,255,255,.5); color: var(--white); }
.btn--ghost:hover { border-color: var(--white); background: rgba(255,255,255,.08); }

.btn--outline { border-color: var(--brand-dark); color: var(--brand-dark); }
.btn--outline:hover { background: var(--brand-dark); color: var(--white); }

.btn-row { display: flex; flex-wrap: wrap; gap: 14px; margin-top: 28px; }

/* ---------- Header ---------- */

.site-header {
  background: var(--white);
  border-bottom: 1px solid var(--brand-line);
  position: sticky;
  top: 0;
  z-index: 50;
}

.header-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  min-height: 78px;
}

.logo { display: flex; align-items: center; text-decoration: none; }
.logo-mark {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 1.55rem;
  letter-spacing: -0.01em;
  color: var(--brand-dark);
  line-height: 1;
}
.logo-mark--light { color: var(--white); }
.logo-accent { color: var(--brand-accent); }

.nav { display: flex; align-items: center; gap: 28px; }

.nav a {
  font-family: var(--font-display);
  font-weight: 600;
  font-size: .97rem;
  color: var(--brand-dark);
  text-decoration: none;
  padding: 6px 0;
  border-bottom: 2px solid transparent;
}
.nav a:hover { color: var(--brand-mid); }
.nav a.is-active { border-bottom-color: var(--brand-accent); color: var(--brand-dark); }

.nav .btn { font-size: .95rem; padding: 10px 20px; }

.nav-toggle {
  display: none;
  background: none;
  border: 1px solid var(--brand-line);
  border-radius: var(--radius);
  padding: 9px 12px;
  cursor: pointer;
}
.nav-toggle span {
  display: block;
  width: 22px; height: 2px;
  background: var(--brand-dark);
  margin: 4px 0;
}

/* ---------- Hero ---------- */

.hero {
  background: var(--brand-dark);
  color: var(--white);
  padding: 92px 0 84px;
  border-bottom: 4px solid var(--brand-accent);
}
.hero h1 { color: var(--white); max-width: 16ch; }
.hero h1 em { color: var(--brand-accent); font-style: normal; }
.hero p { color: rgba(255,255,255,.78); max-width: 56ch; font-size: 1.15rem; }
.hero .eyebrow { color: rgba(255,255,255,.7); }
.crumb .eyebrow, .cta .eyebrow { color: rgba(255,255,255,.7); }

.hero--page { padding: 64px 0 58px; }
.hero--page h1 { max-width: 22ch; }

.crumb {
  font-size: .9rem;
  color: rgba(255,255,255,.65);
  margin-bottom: 18px;
}
.crumb a { color: rgba(255,255,255,.85); text-decoration: none; }
.crumb a:hover { text-decoration: underline; }

/* ---------- Grids and cards ---------- */

.grid { display: grid; gap: 24px; }
.grid--3 { grid-template-columns: repeat(3, 1fr); }
.grid--2 { grid-template-columns: repeat(2, 1fr); gap: 40px; }

.card {
  background: var(--white);
  border: 1px solid var(--brand-line);
  border-radius: var(--radius);
  padding: 30px 28px;
  display: flex;
  flex-direction: column;
}
.card h3 { margin-bottom: .5em; }
.card p { color: var(--ink-soft); font-size: .98rem; }

.card__icon {
  width: 46px; height: 46px;
  margin-bottom: 18px;
  color: var(--brand-mid);
}
.card__link {
  margin-top: auto;
  padding-top: 18px;
  font-family: var(--font-display);
  font-weight: 600;
  font-size: .97rem;
  color: var(--brand-mid);
  text-decoration: none;
}
.card__link:hover { color: var(--brand-dark); }

.card--flat { border: 0; padding: 0; background: none; }
.card--flat h3 {
  border-left: 3px solid var(--brand-accent);
  padding-left: 14px;
}

/* ---------- Lists ---------- */

.ticks { list-style: none; margin: 0; padding: 0; }
.ticks li {
  position: relative;
  padding-left: 30px;
  margin-bottom: 12px;
  color: var(--ink-soft);
}
.ticks li::before {
  content: "";
  position: absolute;
  left: 0; top: .52em;
  width: 12px; height: 7px;
  border-left: 2px solid var(--brand-accent);
  border-bottom: 2px solid var(--brand-accent);
  transform: rotate(-45deg);
}
.ticks strong { color: var(--ink); font-weight: 600; }

.roles {
  list-style: none;
  margin: 0; padding: 0;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0 32px;
}
.roles li {
  padding: 13px 0;
  border-bottom: 1px solid var(--brand-line);
  font-weight: 500;
}

.steps { counter-reset: step; list-style: none; margin: 0; padding: 0; }
.steps li {
  counter-increment: step;
  position: relative;
  padding-left: 52px;
  margin-bottom: 26px;
}
.steps li::before {
  content: counter(step);
  position: absolute;
  left: 0; top: 0;
  width: 34px; height: 34px;
  border-radius: 50%;
  background: var(--brand-accent);
  color: #0a0a0a;
  font-family: var(--font-display);
  font-weight: 700;
  font-size: .95rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.steps h4 { margin: 4px 0 .3em; font-size: 1.05rem; }
.steps p { color: var(--ink-soft); font-size: .98rem; }

/* ---------- Panels ---------- */

.panel {
  background: var(--white);
  border: 1px solid var(--brand-line);
  border-top: 4px solid var(--brand-accent);
  border-radius: var(--radius);
  padding: 34px 32px;
}
.panel--tint { background: var(--brand-light); }

/* ---------- CTA band ---------- */

.cta {
  background: var(--brand-dark);
  color: var(--white);
  padding: 64px 0;
}
.cta h2 { color: var(--white); }
.cta p { color: rgba(255,255,255,.82); max-width: 56ch; }

.cta-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 40px;
  flex-wrap: wrap;
}

/* ---------- Contact ---------- */

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 48px;
  align-items: start;
}

.contact-list { list-style: none; margin: 0; padding: 0; }
.contact-list li {
  display: flex;
  gap: 14px;
  align-items: flex-start;
  padding: 16px 0;
  border-bottom: 1px solid var(--brand-line);
}
.contact-list svg { width: 22px; height: 22px; color: var(--brand-mid); flex: none; margin-top: 3px; }
.contact-list span { display: block; font-size: .84rem; color: var(--ink-soft); text-transform: uppercase; letter-spacing: .08em; font-weight: 600; }
.contact-list a { font-family: var(--font-display); font-size: 1.15rem; font-weight: 600; color: var(--brand-dark); text-decoration: none; }
.contact-list a:hover { color: var(--brand-mid); }

.form-field { margin-bottom: 18px; }
.form-field label {
  display: block;
  font-size: .88rem;
  font-weight: 600;
  margin-bottom: 6px;
  color: var(--brand-dark);
}
.form-field input,
.form-field select,
.form-field textarea {
  width: 100%;
  font-family: var(--font-body);
  font-size: 1rem;
  padding: 12px 14px;
  border: 1px solid var(--brand-line);
  border-radius: var(--radius);
  background: var(--white);
  color: var(--ink);
}
.form-field textarea { min-height: 120px; resize: vertical; }
.form-field input:focus,
.form-field select:focus,
.form-field textarea:focus {
  outline: 2px solid var(--brand-mid);
  outline-offset: 1px;
  border-color: var(--brand-mid);
}
.form-note { font-size: .87rem; color: var(--ink-soft); margin-top: 14px; }

/* ---------- Footer ---------- */

.site-footer {
  background: var(--brand-dark);
  color: rgba(255,255,255,.72);
  padding: 56px 0 28px;
  font-size: .95rem;
}
.footer-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr 1fr;
  gap: 40px;
  padding-bottom: 34px;
}
.site-footer h4 {
  color: var(--white);
  font-size: .85rem;
  letter-spacing: .14em;
  text-transform: uppercase;
  margin-bottom: 16px;
}
.site-footer ul { list-style: none; margin: 0; padding: 0; }
.site-footer li { margin-bottom: 10px; }
.site-footer a { color: rgba(255,255,255,.78); text-decoration: none; }
.site-footer a:hover { color: var(--brand-accent); }
.footer-logo { margin-bottom: 18px; }
.footer-logo .logo-mark { font-size: 1.55rem; }

.footer-bottom {
  border-top: 1px solid rgba(255,255,255,.16);
  padding-top: 22px;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  font-size: .87rem;
  color: rgba(255,255,255,.55);
}

/* ---------- Responsive ---------- */

@media (max-width: 900px) {
  .grid--3 { grid-template-columns: 1fr; }
  .grid--2, .contact-grid { grid-template-columns: 1fr; gap: 32px; }
  .footer-grid { grid-template-columns: 1fr 1fr; }

  .nav-toggle { display: block; }
  .nav {
    display: none;
    position: absolute;
    top: 78px; left: 0; right: 0;
    flex-direction: column;
    align-items: flex-start;
    gap: 0;
    background: var(--white);
    border-bottom: 1px solid var(--brand-line);
    padding: 8px 24px 22px;
  }
  .nav.is-open { display: flex; }
  .nav a { width: 100%; padding: 13px 0; border-bottom: 1px solid var(--brand-line); }
  .nav a.is-active { border-bottom-color: var(--brand-accent); }
  .nav .btn { margin-top: 16px; border-bottom: 0; }
}

@media (max-width: 620px) {
  body { font-size: 16px; }
  .section { padding: 56px 0; }
  .hero { padding: 64px 0 58px; }
  .roles { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr; gap: 30px; }
}

@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  * { transition: none !important; }
}

/* Keyboard focus */
a:focus-visible, button:focus-visible {
  outline: 3px solid var(--brand-accent);
  outline-offset: 2px;
}

</style>
</head>
<body>

  <header class="site-header">
    <div class="wrap header-inner">
      <a class="logo" href="index.html">
        <span class="logo-mark">Top <span class="logo-accent">Recruitment</span></span>
      </a>

      <button class="nav-toggle" aria-label="Menu" aria-expanded="false" aria-controls="nav">
        <span></span><span></span><span></span>
      </button>

      <nav class="nav" id="nav">
          <a href="index.html" class="is-active">Home</a>
          <a href="electricians.html">Electricians</a>
          <a href="gas-engineers.html">Gas Engineers</a>
          <a href="hgv-drivers.html">HGV Drivers</a>
          <a class="btn btn--primary" href="tel:07301089914">07301 089914</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="wrap">
      <p class="eyebrow">Trades &amp; driving recruitment</p>
      <h1>The right trade, with the <em>right ticket.</em></h1>
      <p>We place electricians, gas engineers and HGV drivers with employers across the UK. Every card, certificate and licence is checked before a CV reaches you.</p>
      <div class="btn-row">
        <a class="btn btn--primary" href="#contact">Hire staff</a>
        <a class="btn btn--ghost" href="mailto:info@toprecruitment.uk?subject=CV%20registration">Send your CV</a>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="wrap">
      <div class="section-head">
        <p class="eyebrow">What we recruit</p>
        <h2>Three trades, done properly</h2>
        <p class="lead">We stay narrow on purpose. Knowing what an ACS ticket covers or why a CPC expiry matters is the difference between a placement that lasts and one that costs you a week.</p>
      </div>

      <div class="grid grid--3">
        <div class="card">
          <svg class="card__icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M26 6 14 26h9l-2 16 14-21h-9z"/></svg>
          <h3>Electricians</h3>
          <p>JIB-graded electricians, testing and inspection engineers, improvers and EV installers for contractors, facilities firms and housebuilders.</p>
          <a class="card__link" href="electricians.html">View electrical roles &rarr;</a>
        </div>

        <div class="card">
          <svg class="card__icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M24 6c4 6 9 9 9 16a9 9 0 0 1-18 0c0-4 2-6 4-9 1 2 2 3 4 3 1-4 1-7 1-10z"/><path d="M18 42h12"/></svg>
          <h3>Gas engineers</h3>
          <p>Gas Safe registered domestic and commercial engineers, boiler installers, service and breakdown engineers and heat pump specialists.</p>
          <a class="card__link" href="gas-engineers.html">View gas roles &rarr;</a>
        </div>

        <div class="card">
          <svg class="card__icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 12h22v20H4z"/><path d="M26 19h8l6 7v6h-14z"/><circle cx="14" cy="36" r="4"/><circle cx="33" cy="36" r="4"/></svg>
          <h3>HGV drivers</h3>
          <p>Class 1 and Class 2 drivers with valid CPC and tacho cards, including ADR, HIAB and tipper work for hauliers and distribution operators.</p>
          <a class="card__link" href="hgv-drivers.html">View driving roles &rarr;</a>
        </div>
      </div>
    </div>
  </section>

  <section class="section section--tint">
    <div class="wrap">
      <div class="section-head">
        <p class="eyebrow">Why employers use us</p>
        <h2>Fewer CVs. Better ones.</h2>
      </div>

      <div class="grid grid--2">
        <div>
          <div class="card card--flat" style="margin-bottom:30px">
            <h3>We check at source</h3>
            <p>Gas Safe numbers are checked on the register, licences through the DVLA share code, ECS cards against the ECS database. We do not take a photo of a card at face value.</p>
          </div>
          <div class="card card--flat">
            <h3>One point of contact</h3>
            <p>You speak to the person who took the brief, start to finish. No handover to an account team who never heard the original conversation.</p>
          </div>
        </div>
        <div>
          <div class="card card--flat" style="margin-bottom:30px">
            <h3>We understand how trades get paid</h3>
            <p>Top Recruitment is run from an accounting and tax background. CIS deductions, self-employed versus PAYE status and IR35 exposure are things we get right rather than guess at.</p>
          </div>
          <div class="card card--flat">
            <h3>A shortlist, not a mailshot</h3>
            <p>We send people who match the brief and have said yes to it. If we have nobody suitable, we will tell you that instead of filling your inbox.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="wrap">
      <div class="grid grid--2">
        <div>
          <p class="eyebrow">For employers</p>
          <h2>How hiring works</h2>
          <ol class="steps">
            <li>
              <h4>Take the brief</h4>
              <p>Role, site, qualifications needed, rate, start date. Ten minutes on the phone is usually enough.</p>
            </li>
            <li>
              <h4>Source and vet</h4>
              <p>We shortlist, check tickets and references, and confirm the candidate is genuinely available at your rate.</p>
            </li>
            <li>
              <h4>Interview and start</h4>
              <p>You interview a small shortlist. We handle scheduling, offer and start date, and check in after week one.</p>
            </li>
          </ol>
        </div>

        <div>
          <p class="eyebrow">For candidates</p>
          <h2>Looking for work</h2>
          <ol class="steps">
            <li>
              <h4>Send your CV</h4>
              <p>Email it to us with your cards and tickets, the areas you cover and the money you are after.</p>
            </li>
            <li>
              <h4>We match, then call</h4>
              <p>We only put you forward for roles you would actually take. Your CV does not go anywhere without your say so.</p>
            </li>
            <li>
              <h4>Interview and offer</h4>
              <p>We prep you on the client, chase feedback and negotiate the offer. Registering is free, always.</p>
            </li>
          </ol>
          <div class="btn-row">
            <a class="btn btn--outline" href="mailto:info@toprecruitment.uk?subject=CV%20registration">Send your CV</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section section--tint" id="contact">
    <div class="wrap">
      <div class="contact-grid">
        <div>
          <p class="eyebrow">Get in touch</p>
          <h2>Tell us what you need</h2>
          <p class="lead">Hiring, or looking for work. Either way you get a straight answer, usually the same day.</p>

          <ul class="contact-list">
            <li>
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M3 6.5A2.5 2.5 0 0 1 5.5 4h13A2.5 2.5 0 0 1 21 6.5v11a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 17.5z"/><path d="m3.5 7 8.5 6 8.5-6"/></svg>
              <div><span>Email</span><a href="mailto:info@toprecruitment.uk">info@toprecruitment.uk</a></div>
            </li>
            <li>
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M7 3h10a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z"/><path d="M11 18h2"/></svg>
              <div><span>Phone</span><a href="tel:07301089914">07301 089914</a></div>
            </li>
            <li>
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></svg>
              <div><span>Hours</span><a href="tel:07301089914">Mon to Sat, 8am to 7pm</a></div>
            </li>
          </ul>
        </div>

        <div class="panel">
          <form id="enquiry">
            <div class="form-field">
              <label for="name">Your name</label>
              <input type="text" id="name" name="name" required>
            </div>
            <div class="form-field">
              <label for="email">Email</label>
              <input type="email" id="email" name="email" required>
            </div>
            <div class="form-field">
              <label for="phone">Phone</label>
              <input type="tel" id="phone" name="phone">
            </div>
            <div class="form-field">
              <label for="type">I am</label>
              <select id="type" name="type">
                <option>An employer looking to hire</option>
                <option>A candidate looking for work</option>
              </select>
            </div>
            <div class="form-field">
              <label for="message">What do you need?</label>
              <textarea id="message" name="message" placeholder="Role, location, start date. Or your trade and where you are based."></textarea>
            </div>
            <button type="submit" class="btn btn--dark">Send enquiry</button>
            <p class="form-note">This opens your email app with the details filled in. You can also email info@toprecruitment.uk directly.</p>
          </form>
        </div>
      </div>
    </div>
  </section>

  <footer class="site-footer">
    <div class="wrap">
      <div class="footer-grid">
        <div>
          <div class="footer-logo"><span class="logo-mark logo-mark--light">Top <span class="logo-accent">Recruitment</span></span></div>
          <p>Specialist recruitment for electricians, gas engineers and HGV drivers across the UK.</p>
        </div>
        <div>
          <h4>Sectors</h4>
          <ul>
            <li><a href="electricians.html">Electricians</a></li>
            <li><a href="gas-engineers.html">Gas engineers</a></li>
            <li><a href="hgv-drivers.html">HGV drivers</a></li>
          </ul>
        </div>
        <div>
          <h4>Contact</h4>
          <ul>
            <li><a href="mailto:info@toprecruitment.uk">info@toprecruitment.uk</a></li>
            <li><a href="tel:07301089914">07301 089914</a></li>
            <li><a href="index.html#contact">Send an enquiry</a></li>
          </ul>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2026 Top Recruitment Ltd. All rights reserved.</p>
        <p>Registered in England &amp; Wales. Company no. [to be added]</p>
      </div>
    </div>
  </footer>

  <script>
    var toggle = document.querySelector('.nav-toggle');
    var nav = document.getElementById('nav');
    toggle.addEventListener('click', function () {
      var open = nav.classList.toggle('is-open');
      toggle.setAttribute('aria-expanded', open);
    });

    var form = document.getElementById('enquiry');
    if (form) {
      form.addEventListener('submit', function (e) {
        e.preventDefault();
        var d = new FormData(form);
        var body = 'Name: ' + (d.get('name') || '') +
          '\nEmail: ' + (d.get('email') || '') +
          '\nPhone: ' + (d.get('phone') || '') +
          '\nType: ' + (d.get('type') || '') +
          '\n\n' + (d.get('message') || '');
        window.location.href = 'mailto:info@toprecruitment.uk?subject=' +
          encodeURIComponent('Website enquiry from ' + (d.get('name') || 'website')) +
          '&body=' + encodeURIComponent(body);
      });
    }
  </script>

</body>
</html>

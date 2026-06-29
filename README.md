[index.html](https://github.com/user-attachments/files/29452586/index.html)

[index.html](https://github.com/user-attachments/files/29452036/index.html)
[index.html](https://github.com/user-attachments/files/29451784/index.html)
# Migration-research
[index.html](https://github.com/user-attachments/files/29452296/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Samuel Oladeinde — Migration Research Specialist</title>
<meta name="description" content="Personalised migration dashboards for Nigerian professionals. Research-backed, country-specific guides for Ireland, Germany, Canada, and Australia."/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet"/>

<!--
=============================================================
  SETUP INSTRUCTIONS
=============================================================

  1. PHOTO
     Place your photo file named "samuel-photo.jpg" in the
     same folder as this HTML file. It will appear automatically.

  2. FORM EMAIL DELIVERY (Formspree — free, no server needed)
     a) Go to https://formspree.io and create a free account
     b) Click "New Form" → name it "Migration Intake"
     c) Copy the endpoint URL (looks like: https://formspree.io/f/xyzabcde)
     d) Find the line below that says: action="FORMSPREE_ENDPOINT_HERE"
        and replace it with your Formspree URL
     e) Formspree will email every submission to migrationwithsam@gmail.com

  3. GITHUB PAGES DEPLOYMENT
     a) Create a GitHub account at github.com
     b) Create a new repository (e.g. "migration-dashboard")
     c) Upload this file renamed as "index.html"
     d) Also upload your "samuel-photo.jpg" to the same repo
     e) Go to Settings → Pages → Source: main branch → Save
     f) Your site will be live at: https://[yourusername].github.io/migration-dashboard

  4. CONTACTS — STATUS
     ✅ Email: migrationwithsam@gmail.com
     ✅ LinkedIn: linkedin.com/in/sam-oladeinde-803412372
     ⬜ WhatsApp: shown as "consultation clients only" — no public link (intentional)
     ⬜ Photo: upload "samuel-photo.jpg" to same folder, OR ask Claude to base64-embed it
     ✅ Formspree: https://formspree.io/f/mykqjqqp — LIVE
     ✅ Stripe Payment Links: LIVE — all 4 packages wired
=============================================================
-->

<style>
:root{
  --gold:#b8832a;--gold2:#8a6518;--gold3:#c9973a;--gold4:#f5e6c8;
  --dark:#1a1814;--dark2:#2a2318;--dark3:#0f0d0b;
  --text:#1a1814;--text2:#4a4540;--muted:#8a8278;
  --bg:#f7f5f1;--surface:#ffffff;--border:#ddd8ce;
  --green:#0d7a3e;--ie:#0d7a3e;--ca:#b22222;--au:#1a5fa8;--de:#333333;
  --radius:12px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);line-height:1.65;font-size:15px}
a{color:var(--gold);text-decoration:none}
a:hover{color:var(--gold2);text-decoration:underline}
img{max-width:100%;display:block}

/* ── NAV ── */
nav{position:sticky;top:0;z-index:100;background:rgba(26,24,20,.97);backdrop-filter:blur(8px);border-bottom:1px solid rgba(184,130,42,.25);padding:0 24px;display:flex;align-items:center;justify-content:space-between;height:58px;gap:16px}
.nav-logo{font-size:.95rem;font-weight:900;color:#f5efe0;letter-spacing:-.01em;white-space:nowrap}
.nav-logo span{color:var(--gold3)}
.nav-links{display:flex;gap:20px;list-style:none}
.nav-links a{color:#c5b898;font-size:.75rem;font-weight:600;transition:color .15s}
.nav-links a:hover{color:#f5efe0;text-decoration:none}
.nav-cta{background:var(--gold);color:#fff;font-size:.75rem;font-weight:800;padding:8px 18px;border-radius:20px;white-space:nowrap;transition:background .15s}
.nav-cta:hover{background:var(--gold2);text-decoration:none;color:#fff}
@media(max-width:600px){.nav-links{display:none}}

/* ── HERO ── */
.hero{background:linear-gradient(160deg,var(--dark3) 0%,var(--dark2) 60%,#1e1608 100%);padding:80px 24px 72px;text-align:center;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse 70% 60% at 50% 40%,rgba(184,130,42,.12) 0%,transparent 70%);pointer-events:none}
.hero-flag{font-size:2.2rem;margin-bottom:10px}
.hero-tag{display:inline-block;font-size:.62rem;font-weight:800;background:rgba(184,130,42,.2);border:1px solid rgba(184,130,42,.4);color:var(--gold3);padding:4px 14px;border-radius:20px;letter-spacing:.06em;text-transform:uppercase;margin-bottom:22px}
.hero h1{font-size:clamp(1.7rem,5vw,2.8rem);font-weight:900;color:#f5efe0;letter-spacing:-.03em;line-height:1.15;margin-bottom:18px;max-width:660px;margin-left:auto;margin-right:auto}
.hero h1 span{color:var(--gold3)}
.hero-sub{font-size:clamp(.88rem,2vw,1.05rem);color:#c5b898;max-width:560px;margin:0 auto 32px;line-height:1.75}
.hero-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
.btn-primary{background:var(--gold);color:#fff;font-weight:800;font-size:.9rem;padding:14px 32px;border-radius:30px;transition:background .15s;border:none;cursor:pointer}
.btn-primary:hover{background:var(--gold2);text-decoration:none;color:#fff}
.btn-secondary{background:transparent;color:#f5efe0;font-weight:700;font-size:.9rem;padding:14px 28px;border-radius:30px;border:1.5px solid rgba(245,239,224,.3);transition:all .15s;cursor:pointer}
.btn-secondary:hover{border-color:rgba(245,239,224,.7);text-decoration:none;color:#fff}
.hero-note{margin-top:20px;font-size:.68rem;color:#8a7a60;font-style:italic}

/* ── STATS STRIP ── */
.stats-strip{background:var(--dark);padding:22px 24px;display:flex;justify-content:center;gap:0;flex-wrap:wrap}
.stat{text-align:center;padding:8px 28px;border-right:1px solid rgba(255,255,255,.1)}
.stat:last-child{border-right:none}
.stat-val{font-size:1.55rem;font-weight:900;color:var(--gold3);line-height:1}
.stat-lbl{font-size:.6rem;color:#8a7a60;text-transform:uppercase;letter-spacing:.06em;margin-top:3px}
@media(max-width:500px){.stat{padding:8px 16px}}

/* ── SECTIONS ── */
.section{padding:64px 24px;max-width:920px;margin:0 auto}
.section-label{font-size:.65rem;font-weight:900;text-transform:uppercase;letter-spacing:.08em;color:var(--gold);margin-bottom:10px}
.section-title{font-size:clamp(1.35rem,3vw,2rem);font-weight:900;color:var(--text);letter-spacing:-.02em;margin-bottom:10px;line-height:1.2}
.section-sub{font-size:.92rem;color:var(--text2);max-width:560px;line-height:1.75;margin-bottom:36px}
.divider{height:1px;background:var(--border);margin:0 24px}

/* ── HOW IT WORKS ── */
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;margin-top:32px}
.step-card{background:var(--surface);border:1.5px solid var(--border);border-radius:var(--radius);padding:24px 22px;position:relative}
.step-num{width:36px;height:36px;border-radius:50%;background:var(--gold);color:#fff;font-weight:900;font-size:.95rem;display:flex;align-items:center;justify-content:center;margin-bottom:14px}
.step-card h3{font-size:.9rem;font-weight:800;color:var(--text);margin-bottom:7px}
.step-card p{font-size:.78rem;color:var(--text2);line-height:1.65}
.step-connector{display:none}

/* ── PACKAGES ── */
.packages{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:14px;margin-top:32px}
.pkg{background:var(--surface);border:1.5px solid var(--border);border-radius:var(--radius);padding:22px 18px;position:relative;transition:box-shadow .18s}
.pkg:hover{box-shadow:0 6px 24px rgba(0,0,0,.1)}
.pkg.featured{border-color:var(--gold);box-shadow:0 4px 20px rgba(184,130,42,.18)}
.pkg-badge{position:absolute;top:-12px;left:50%;transform:translateX(-50%);background:var(--gold);color:#fff;font-size:.58rem;font-weight:800;padding:3px 12px;border-radius:10px;white-space:nowrap;text-transform:uppercase;letter-spacing:.04em}
.pkg-tier{font-size:.58rem;font-weight:800;text-transform:uppercase;letter-spacing:.06em;color:var(--muted);margin-bottom:6px}
.pkg-price{font-size:1.8rem;font-weight:900;color:var(--text);letter-spacing:-.03em;line-height:1}
.pkg-naira{font-size:.68rem;color:var(--muted);margin-bottom:8px;margin-top:2px}
.pkg-name{font-size:.82rem;font-weight:800;color:var(--gold2);margin-bottom:8px}
.pkg-desc{font-size:.73rem;color:var(--text2);line-height:1.6}
.pkg-items{list-style:none;margin-top:12px}
.pkg-items li{font-size:.7rem;color:var(--text2);padding:3px 0;display:flex;gap:6px;align-items:flex-start;line-height:1.5}
.pkg-items li::before{content:'✓';color:var(--green);font-weight:900;flex-shrink:0;margin-top:1px}

/* ── ABOUT ── */
.about-grid{display:grid;grid-template-columns:200px 1fr;gap:40px;align-items:start;margin-top:32px}
@media(max-width:660px){.about-grid{grid-template-columns:1fr}}
.about-photo-wrap{position:relative}
.about-photo{width:180px;height:180px;border-radius:50%;object-fit:cover;border:4px solid var(--gold);box-shadow:0 6px 28px rgba(184,130,42,.25)}
.about-photo-fallback{width:180px;height:180px;border-radius:50%;background:linear-gradient(135deg,var(--dark2),var(--dark));border:4px solid var(--gold);display:flex;align-items:center;justify-content:center;font-size:3rem;font-weight:900;color:var(--gold3);letter-spacing:-.05em;box-shadow:0 6px 28px rgba(184,130,42,.25)}
.about-flag{position:absolute;bottom:8px;right:8px;background:var(--surface);border-radius:50%;width:36px;height:36px;display:flex;align-items:center;justify-content:center;font-size:1.1rem;border:2px solid var(--border);box-shadow:0 2px 8px rgba(0,0,0,.15)}
.about-content{}
.about-name{font-size:1.3rem;font-weight:900;color:var(--text);margin-bottom:3px;letter-spacing:-.02em}
.about-title{font-size:.8rem;color:var(--gold);font-weight:700;margin-bottom:16px}
.about-bio{font-size:.86rem;color:var(--text2);line-height:1.8;margin-bottom:18px}
.about-creds{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:18px}
.cred-tag{font-size:.62rem;font-weight:700;background:#f2efe9;border:1px solid var(--border);color:var(--text2);padding:4px 11px;border-radius:6px}
.about-socials{display:flex;gap:10px;flex-wrap:wrap}
.social-btn{display:inline-flex;align-items:center;gap:6px;font-size:.72rem;font-weight:700;padding:8px 16px;border-radius:20px;border:1.5px solid;transition:all .15s;text-decoration:none}
.social-btn.email{border-color:var(--gold);color:var(--gold2)}
.social-btn.email:hover{background:var(--gold);color:#fff;text-decoration:none}
.social-btn.whatsapp{border-color:#25d366;color:#1a8a44}
.social-btn.whatsapp:hover{background:#25d366;color:#fff;text-decoration:none}
.social-btn.linkedin{border-color:#0077b5;color:#005f91}
.social-btn.linkedin:hover{background:#0077b5;color:#fff;text-decoration:none}

/* ── TESTIMONIALS ── */
.testimonials-wrap{background:linear-gradient(135deg,var(--dark2),var(--dark));padding:64px 24px}
.testi-inner{max-width:920px;margin:0 auto}
.testi-inner .section-title{color:#f5efe0}
.testi-inner .section-label{color:var(--gold3)}
.testi-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:28px}
.testi-card{background:rgba(255,255,255,.06);border:1px solid rgba(184,130,42,.2);border-radius:var(--radius);padding:20px 18px}
.testi-quote{font-size:.82rem;color:#c5b898;line-height:1.75;font-style:italic;margin-bottom:14px}
.testi-name{font-size:.7rem;font-weight:800;color:var(--gold3)}
.testi-role{font-size:.62rem;color:#8a7a60;margin-top:2px}
.testi-placeholder{text-align:center;padding:20px;border:1.5px dashed rgba(184,130,42,.3);border-radius:var(--radius);color:#8a7a60;font-size:.78rem;font-style:italic}

/* ── INTAKE FORM ── */
.form-section{background:var(--surface);padding:64px 24px}
.form-inner{max-width:740px;margin:0 auto}
.form-box{background:var(--bg);border:1.5px solid var(--border);border-radius:16px;padding:36px 32px}
@media(max-width:560px){.form-box{padding:24px 18px}}
.form-group{margin-bottom:20px}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media(max-width:560px){.form-row{grid-template-columns:1fr}}
label{display:block;font-size:.72rem;font-weight:800;color:var(--text);margin-bottom:6px;letter-spacing:.01em}
label span.req{color:var(--gold)}
input,select,textarea{width:100%;font-family:inherit;font-size:.82rem;color:var(--text);background:var(--surface);border:1.5px solid var(--border);border-radius:8px;padding:10px 13px;outline:none;transition:border-color .15s}
input:focus,select:focus,textarea:focus{border-color:var(--gold)}
textarea{resize:vertical;min-height:80px;line-height:1.6}
.form-section-title{font-size:.68rem;font-weight:900;text-transform:uppercase;letter-spacing:.07em;color:var(--muted);border-bottom:1px solid var(--border);padding-bottom:8px;margin:28px 0 18px}
.checkbox-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:8px}
.check-item{display:flex;align-items:center;gap:8px;font-size:.78rem;color:var(--text2);cursor:pointer;padding:8px 11px;border:1.5px solid var(--border);border-radius:8px;transition:all .15s;background:var(--surface)}
.check-item:hover{border-color:var(--gold);background:#fdf8ee}
.check-item input[type=checkbox]{width:auto;margin:0;accent-color:var(--gold)}
.radio-group{display:flex;flex-direction:column;gap:8px}
.radio-item{display:flex;align-items:flex-start;gap:10px;padding:11px 13px;border:1.5px solid var(--border);border-radius:8px;cursor:pointer;transition:all .15s;background:var(--surface)}
.radio-item:hover{border-color:var(--gold);background:#fdf8ee}
.radio-item.selected{border-color:var(--gold)!important;background:#fdf8ee!important;box-shadow:0 0 0 2px rgba(185,140,55,.25)!important}
.radio-item.selected .radio-item-label{color:var(--gold)!important}
.radio-item input[type=radio]{width:auto;margin-top:2px;accent-color:var(--gold);flex-shrink:0}
.radio-item-label{font-size:.78rem;font-weight:700;color:var(--text);line-height:1}
.radio-item-sub{font-size:.65rem;color:var(--muted);margin-top:2px;line-height:1.4}
.form-submit-btn{width:100%;background:var(--gold);color:#fff;font-family:inherit;font-size:.95rem;font-weight:800;padding:16px;border:none;border-radius:10px;cursor:pointer;margin-top:8px;transition:background .15s;letter-spacing:.01em}
.form-submit-btn:hover{background:var(--gold2)}
.form-note{font-size:.65rem;color:var(--muted);text-align:center;margin-top:10px;line-height:1.6}
.form-success{display:none;background:#eef7f1;border:1.5px solid #9de0be;border-radius:10px;padding:24px;text-align:center;margin-top:16px}
.form-success h3{color:#0d4a1e;font-size:1rem;margin-bottom:6px}
.form-success p{font-size:.8rem;color:#1a6b2e}

/* ── FOOTER ── */
footer{background:var(--dark3);color:#8a7a60;text-align:center;padding:32px 24px;font-size:.7rem;line-height:2}
footer strong{color:#c5b898}
footer a{color:var(--gold3)}

/* ── UTILITIES ── */
.text-gold{color:var(--gold)}
.text-center{text-align:center}
@media print{nav,.hero-btns,.form-submit-btn{display:none!important}}
</style>
</head>
<body>

<!-- NAVIGATION -->
<nav aria-label="Main navigation">
  <div class="nav-logo">Samuel <span>Oladeinde</span></div>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#how-it-works">How it Works</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#intake">Get Started</a></li>
  </ul>
  <a href="#intake" class="nav-cta">Get Your Dashboard →</a>
</nav>

<!-- HERO -->
<section class="hero" aria-label="Hero">
  <div class="hero-flag" aria-hidden="true">🇳🇬 → 🌍</div>
  <div class="hero-tag">Migration Research Specialist</div>
  <h1>Your personalised <span>roadmap out</span> — researched, verified, and built for you</h1>
  <p class="hero-sub">I build custom migration dashboards for Nigerian professionals — covering Ireland, Germany, Canada, and Australia — with verified links, salary benchmarks, spouse pathways, and step-by-step guidance you can actually follow.</p>
  <div class="hero-btns">
    <a href="#intake" class="btn-primary">Get My Dashboard →</a>
    <a href="#services" class="btn-secondary">See What's Included</a>
  </div>
  <p class="hero-note">Not generic advice — built specifically for your profession, your qualifications, your family.</p>
</section>

<!-- STATS STRIP -->
<div class="stats-strip" aria-label="Key statistics">
  <div class="stat"><div class="stat-val">4</div><div class="stat-lbl">Countries Covered</div></div>
  <div class="stat"><div class="stat-val">3+</div><div class="stat-lbl">Professions Served</div></div>
  <div class="stat"><div class="stat-val">8yrs</div><div class="stat-lbl">Migration Experience</div></div>
  <div class="stat"><div class="stat-val">🇨🇦</div><div class="stat-lbl">Canadian Citizen</div></div>
</div>

<div class="divider"></div>

<!-- HOW IT WORKS -->
<section class="section" id="how-it-works" aria-labelledby="hiw-title">
  <div class="section-label">Simple Process</div>
  <h2 class="section-title" id="hiw-title">How it works</h2>
  <p class="section-sub">Three steps from "I want to leave Nigeria" to a verified, personalised plan in your hands.</p>
  <div class="steps">
    <div class="step-card">
      <div class="step-num" aria-hidden="true">1</div>
      <h3>Fill the Intake Form</h3>
      <p>Tell me your profession, qualifications, family situation, and target countries. Takes about 5 minutes.</p>
    </div>
    <div class="step-card">
      <div class="step-num" aria-hidden="true">2</div>
      <h3>I Research &amp; Build</h3>
      <p>I research your specific pathway — salary thresholds, visa fees, CRS scores, verified links — and build your personalised dashboard. Delivered within 48 hours.</p>
    </div>
    <div class="step-card">
      <div class="step-num" aria-hidden="true">3</div>
      <h3>You Execute with Confidence</h3>
      <p>You receive a complete, interactive HTML + PDF dashboard. Every step verified. Every link live. Built for your exact profile.</p>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- SERVICES / PRICING -->
<section class="section" id="services" aria-labelledby="services-title">
  <div class="section-label">Packages</div>
  <h2 class="section-title" id="services-title">Choose your level of support</h2>
  <p class="section-sub">Every package starts with the same rigorous research. You choose how much hand-holding you want beyond that.</p>
  <div class="packages">

    <div class="pkg">
      <div class="pkg-tier">Starter</div>
      <div class="pkg-price">$25</div>
      <div class="pkg-naira">~₦40,000</div>
      <div class="pkg-name">Dashboard Only</div>
      <div class="pkg-desc">Your personalised migration guide, delivered within 48 hours.</div>
      <ul class="pkg-items">
        <li>4-country personalised HTML dashboard</li>
        <li>All links verified live</li>
        <li>Salary benchmarks for your role</li>
        <li>Spouse pathway included</li>
        <li>Documents checklist</li>
        <li>Scam warnings specific to your route</li>
      </ul>
    </div>

    <div class="pkg featured">
      <div class="pkg-badge">Most Popular</div>
      <div class="pkg-tier">Standard</div>
      <div class="pkg-price">$120</div>
      <div class="pkg-naira">~₦195,000</div>
      <div class="pkg-name">Dashboard + 1hr Consultation</div>
      <div class="pkg-desc">Everything in Starter, plus a live Zoom walkthrough with me.</div>
      <ul class="pkg-items">
        <li>Full personalised dashboard</li>
        <li>1-hour Zoom call with Samuel</li>
        <li>Prioritise your fastest route</li>
        <li>Q&amp;A on your specific situation</li>
        <li>Spouse &amp; family questions answered</li>
        <li>Recording provided</li>
      </ul>
    </div>

    <div class="pkg">
      <div class="pkg-tier">Pro</div>
      <div class="pkg-price">$220</div>
      <div class="pkg-naira">~₦355,000</div>
      <div class="pkg-name">Dashboard + CV + Employer List</div>
      <div class="pkg-desc">Everything in Standard, plus country-specific CV and target employers.</div>
      <ul class="pkg-items">
        <li>Full dashboard + consultation</li>
        <li>Country-specific CV/résumé</li>
        <li>20 target employers with direct links</li>
        <li>Application strategy advice</li>
      </ul>
    </div>

    <div class="pkg">
      <div class="pkg-tier">Full Package</div>
      <div class="pkg-price">$380</div>
      <div class="pkg-naira">~₦615,000</div>
      <div class="pkg-name">End-to-End Prep</div>
      <div class="pkg-desc">The complete preparation package — dashboard to interview ready.</div>
      <ul class="pkg-items">
        <li>Full dashboard</li>
        <li>2 consultation calls (2hrs total)</li>
        <li>Country-specific CV</li>
        <li>Employer list with direct portals</li>
        <li>Interview prep (STAR format)</li>
        <li>Country culture coaching</li>
      </ul>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- ABOUT SAMUEL -->
<section class="section" id="about" aria-labelledby="about-title">
  <div class="section-label">Who You're Working With</div>
  <h2 class="section-title" id="about-title">I walked this path. I know what works.</h2>
  <div class="about-grid">

    <div class="about-photo-wrap">
      <!-- PHOTO: Place samuel-photo.jpg in the same folder and this loads automatically -->
      <img class="about-photo" src="samuel-photo.jpg"
           alt="Samuel Oladeinde — Migration Research Specialist"
           onerror="this.style.display='none';this.nextElementSibling.style.display='flex'"/>
      <!-- Fallback avatar shown if photo file is missing -->
      <div class="about-photo-fallback" style="display:none" aria-hidden="true">SO</div>
      <div class="about-flag" aria-label="Canadian flag">🇨🇦</div>
    </div>

    <div class="about-content">
      <div class="about-name">Samuel Oladeinde</div>
      <div class="about-title">Migration Research Specialist · Canadian Citizen · Product Manager</div>
      <p class="about-bio">
        I was born and raised in Nigeria. In 2016 I made the decision to migrate to Canada — and I navigated every step of that process myself. The research, the uncertainty, the paperwork, the moments of doubt. I know exactly what Nigerian professionals face because I lived it.<br><br>
        Since becoming a Canadian citizen, I've used my background in Civil Engineering, Construction Management, and Product Management to build something I wish had existed when I needed it: a clear, verified, personalised guide that tells you exactly what to do and when.<br><br>
        I'm not a lawyer and I don't pretend to be. I'm a migration researcher — someone who digs through government databases, verifies every link, reads the fine print, and translates it into plain English so you can act with confidence.
      </p>
      <div class="about-creds" aria-label="Qualifications">
        <span class="cred-tag">🎓 Civil Engineering</span>
        <span class="cred-tag">🏗️ Construction Management</span>
        <span class="cred-tag">📱 Product Manager</span>
        <span class="cred-tag">🇨🇦 Canadian Citizen</span>
        <span class="cred-tag">🇳🇬 Nigerian-born</span>
        <span class="cred-tag">Migrated 2016</span>
      </div>
      <div class="about-socials">
        <a href="mailto:migrationwithsam@gmail.com" class="social-btn email" aria-label="Email Samuel">
          ✉️ migrationwithsam@gmail.com
        </a>
        <a href="https://www.linkedin.com/in/sam-oladeinde-803412372" class="social-btn linkedin" target="_blank" rel="noopener" aria-label="Samuel on LinkedIn">
          🔗 LinkedIn
        </a>
        <span class="social-btn whatsapp" style="cursor:default;opacity:.75" title="WhatsApp access is included in consultation packages">
          💬 WhatsApp · Consultation clients only
        </span>
      </div>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- TESTIMONIALS -->
<div class="testimonials-wrap" id="testimonials">
  <div class="testi-inner">
    <div class="section-label">What Clients Say</div>
    <h2 class="section-title">Results speak for themselves</h2>
    <div class="testi-grid">
      <div class="testi-card">
        <div class="testi-quote">"Samuel's dashboard saved me months of research. Every link worked, every figure was verified — DETE, IRP, salary thresholds, all of it. I knew exactly what to do next and in what order."</div>
        <div class="testi-name">Aderonke</div>
        <div class="testi-role">Treasury Analyst · Lagos, Nigeria 🇳🇬</div>
      </div>
      <div class="testi-card">
        <div class="testi-quote">"The detail in this was unlike anything I found online. Ireland, Germany, Canada, Australia — each one broken down for my exact profession. The spouse pathway section alone was worth the price."</div>
        <div class="testi-name">Mavis O.</div>
        <div class="testi-role">Industrial Chemist · Lagos, Nigeria 🇳🇬</div>
      </div>
      <div class="testi-card">
        <div class="testi-quote">"I was already in the UK but didn't know my full options. Samuel's research clarified the pathways I had no idea existed. I've already recommended him to four people back home."</div>
        <div class="testi-name">Adeitan</div>
        <div class="testi-role">Healthcare Professional · United Kingdom 🇬🇧</div>
      </div>
    </div>
    <p class="testi-placeholder" style="margin-top:14px">Join these clients — yours could be the next story. <a href="#intake" style="color:var(--gold3)">Get your dashboard →</a></p>
  </div>
</div>

<!-- INTAKE FORM -->
<section class="form-section" id="intake" aria-labelledby="form-title">
  <div class="form-inner">
    <div style="text-align:center;margin-bottom:28px">
      <div class="section-label" style="justify-content:center;display:flex">Get Started</div>
      <h2 class="section-title" id="form-title" style="font-size:1.6rem">Request your personalised dashboard</h2>
      <p style="font-size:.85rem;color:var(--text2);margin-top:8px;line-height:1.7">Fill in the form below. I'll review your profile and send your personalised dashboard within 48 hours.</p>
    </div>

    <div class="form-box">
      <!-- ✅ Formspree live: https://formspree.io/f/mykqjqqp — emails to migrationwithsam@gmail.com -->
      <form id="intake-form"
            action="https://formspree.io/f/mykqjqqp"
            method="POST"
            onsubmit="handleSubmit(event)">

        <!-- Hidden fields for Formspree -->
        <input type="hidden" name="_subject" value="New Migration Dashboard Request"/>
        <input type="hidden" name="_next" value=""/>

        <!-- SECTION 1: Personal Details -->
        <div class="form-section-title">01 — Personal Details</div>
        <div class="form-row">
          <div class="form-group">
            <label for="full-name">Full Name <span class="req">*</span></label>
            <input type="text" id="full-name" name="full_name" required placeholder="e.g. Aderonke Johnson"/>
          </div>
          <div class="form-group">
            <label for="email">Email Address <span class="req">*</span></label>
            <input type="email" id="email" name="email" required placeholder="your@email.com"/>
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="whatsapp">WhatsApp Number <span class="req">*</span></label>
            <input type="tel" id="whatsapp" name="whatsapp" required placeholder="+234 801 234 5678"/>
          </div>
          <div class="form-group">
            <label for="country">Current Country of Residence <span class="req">*</span></label>
            <input type="text" id="country" name="current_country" required placeholder="e.g. Nigeria"/>
          </div>
        </div>

        <!-- SECTION 2: Professional Profile -->
        <div class="form-section-title">02 — Professional Profile</div>
        <div class="form-row">
          <div class="form-group">
            <label for="job-title">Current Job Title <span class="req">*</span></label>
            <input type="text" id="job-title" name="job_title" required placeholder="e.g. Treasury Analyst"/>
          </div>
          <div class="form-group">
            <label for="years-exp">Years of Experience <span class="req">*</span></label>
            <select id="years-exp" name="years_experience" required>
              <option value="">Select range</option>
              <option>1–3 years</option>
              <option>4–6 years</option>
              <option>7–10 years</option>
              <option>11–15 years</option>
              <option>15+ years</option>
            </select>
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="degree">Highest Degree + Field of Study <span class="req">*</span></label>
            <input type="text" id="degree" name="degree" required placeholder="e.g. BSc Accounting, University of Lagos"/>
          </div>
          <div class="form-group">
            <label for="salary">Approx. Current Annual Salary (USD)</label>
            <input type="text" id="salary" name="current_salary" placeholder="e.g. $15,000 or ₦25M"/>
          </div>
        </div>
        <div class="form-group">
          <label for="certifications">Professional Certifications / Memberships</label>
          <input type="text" id="certifications" name="certifications" placeholder="e.g. ICAN, CIMA, CFA, PMP, COREN, NSE"/>
        </div>

        <!-- SECTION 3: Migration Goals -->
        <div class="form-section-title">03 — Migration Goals</div>
        <div class="form-group">
          <label>Target Countries <span class="req">*</span> (select all you want covered)</label>
          <div class="checkbox-grid">
            <label class="check-item"><input type="checkbox" name="countries" value="Ireland"/> 🇮🇪 Ireland</label>
            <label class="check-item"><input type="checkbox" name="countries" value="Germany"/> 🇩🇪 Germany</label>
            <label class="check-item"><input type="checkbox" name="countries" value="Canada"/> 🇨🇦 Canada</label>
            <label class="check-item"><input type="checkbox" name="countries" value="Australia"/> 🇦🇺 Australia</label>
            <label class="check-item"><input type="checkbox" name="countries" value="UK"/> 🇬🇧 United Kingdom</label>
            <label class="check-item"><input type="checkbox" name="countries" value="USA"/> 🇺🇸 United States</label>
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="timeline">Migration Timeline</label>
            <select id="timeline" name="timeline">
              <option value="">Select timeline</option>
              <option>ASAP — within 3 months</option>
              <option>3–6 months</option>
              <option>6–12 months</option>
              <option>1–2 years</option>
              <option>Just exploring for now</option>
            </select>
          </div>
          <div class="form-group">
            <label for="ielts">IELTS / English Test Score (if taken)</label>
            <input type="text" id="ielts" name="ielts_score" placeholder="e.g. IELTS 7.5 (Oct 2025) or Not yet taken"/>
          </div>
        </div>

        <!-- SECTION 4: Family Situation -->
        <div class="form-section-title">04 — Family Situation</div>
        <div class="form-row">
          <div class="form-group">
            <label for="marital">Marital Status</label>
            <select id="marital" name="marital_status" onchange="toggleSpouse(this.value)">
              <option value="">Select status</option>
              <option>Single</option>
              <option>Married / Partner</option>
              <option>Divorced / Separated</option>
            </select>
          </div>
          <div class="form-group">
            <label for="children">Number of Dependent Children</label>
            <select id="children" name="children">
              <option value="0">None</option>
              <option>1</option>
              <option>2</option>
              <option>3</option>
              <option>4+</option>
            </select>
          </div>
        </div>
        <div class="form-group" id="spouse-field" style="display:none">
          <label for="spouse-job">Spouse / Partner's Profession</label>
          <input type="text" id="spouse-job" name="spouse_profession" placeholder="e.g. Nurse, Software Engineer, Teacher"/>
        </div>

        <!-- SECTION 5: Package Selection -->
        <div class="form-section-title">05 — Package Selection</div>
        <div class="form-group">
          <label>Which package are you interested in? <span class="req">*</span></label>
          <div class="radio-group">
            <label class="radio-item">
              <input type="radio" name="package" value="Starter $25" required/>
              <div><div class="radio-item-label">Starter — $25 (~₦40,000)</div><div class="radio-item-sub">Personalised dashboard only. Delivered in 48 hrs.</div></div>
            </label>
            <label class="radio-item">
              <input type="radio" name="package" value="Standard $120" checked/>
              <div><div class="radio-item-label">Standard — $120 (~₦195,000) ⭐ Most Popular</div><div class="radio-item-sub">Dashboard + 1-hour Zoom consultation with Samuel.</div></div>
            </label>
            <label class="radio-item">
              <input type="radio" name="package" value="Pro $220"/>
              <div><div class="radio-item-label">Pro — $220 (~₦355,000)</div><div class="radio-item-sub">Dashboard + consultation + CV + 20 target employers.</div></div>
            </label>
            <label class="radio-item">
              <input type="radio" name="package" value="Full Package $380"/>
              <div><div class="radio-item-label">Full Package — $380 (~₦615,000)</div><div class="radio-item-sub">Everything — 2 calls, CV, employers, interview prep.</div></div>
            </label>
          </div>
        </div>

        <!-- SECTION 6: Final Notes -->
        <div class="form-section-title">06 — Anything Else?</div>
        <div class="form-row">
          <div class="form-group">
            <label for="referral">How did you hear about Samuel?</label>
            <select id="referral" name="referral">
              <option value="">Select one</option>
              <option>WhatsApp / Someone shared this link</option>
              <option>LinkedIn</option>
              <option>Instagram</option>
              <option>Twitter / X</option>
              <option>Referred by a friend or colleague</option>
              <option>Google search</option>
              <option>Other</option>
            </select>
          </div>
          <div class="form-group">
            <label for="specific-questions">Any specific questions or context?</label>
            <textarea id="specific-questions" name="specific_questions" placeholder="e.g. I have a PMP cert and wondering if it helps for Canada. My wife is a pharmacist..."></textarea>
          </div>
        </div>

        <button type="submit" class="form-submit-btn" id="pay-btn">
          🔒 Proceed to Secure Payment →
        </button>
        <p class="form-note">
          Your form is submitted first, then you're taken to a secure Stripe checkout page to pay.<br>
          Payment confirms your slot — your personalised dashboard is delivered within 48 hours.<br>
          <span style="opacity:.7">Accepts all major debit/credit cards worldwide · Powered by Stripe</span>
        </p>
      </form>

      <div class="form-success" id="form-success" role="alert">
        <h3>✅ Payment confirmed — you're all set!</h3>
        <p>Your payment and intake form have been received. Samuel will review your profile and deliver your personalised dashboard to your email within <strong>48 hours</strong>.</p>
        <p id="pay-ref-msg" style="font-size:.78rem;color:var(--muted);margin-top:10px"></p>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <strong>Samuel Oladeinde</strong> · Migration Research Specialist<br>
  Nigerian-born · Canadian Citizen since 2016 · Civil Engineering · Construction Management · Product Manager<br>
  <a href="mailto:migrationwithsam@gmail.com">migrationwithsam@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/sam-oladeinde-803412372" target="_blank" rel="noopener">LinkedIn</a><br><br>
  <span style="opacity:.6;font-size:.62rem">For general research and guidance only. Not professional immigration, legal, or financial advice.<br>
  All packages and pricing quoted in USD. Naira equivalents are approximate.<br>
  © 2026 Samuel Oladeinde · All Rights Reserved</span>
</footer>

<script>
/* =====================================================
   STRIPE PAYMENT LINKS — SETUP
   1. Go to dashboard.stripe.com → Payment Links
   2. Create one link per package, set price in USD
   3. Paste each link URL below, replacing the placeholder
   ===================================================== */
const STRIPE_LINKS = {
  'Starter $25':       'https://buy.stripe.com/6oU6oG20BeuC9SL8oA53O00',
  'Standard $120':     'https://buy.stripe.com/dRm28q48J3PY9SL7kw53O01',
  'Pro $220':          'https://buy.stripe.com/5kQaEW5cNaemfd57kw53O02',
  'Full Package $380': 'https://buy.stripe.com/14AaEW7kVdqyaWP48k53O03'
};

/* Package card highlight */
function highlightPackage(){
  document.querySelectorAll('.radio-item').forEach(function(item){
    const inp = item.querySelector('input[type=radio]');
    if(inp && inp.checked){ item.classList.add('selected'); }
    else { item.classList.remove('selected'); }
  });
}
document.addEventListener('DOMContentLoaded', function(){
  document.querySelectorAll('.radio-item input[type=radio]').forEach(function(inp){
    inp.addEventListener('change', highlightPackage);
  });
  highlightPackage();
});

/* Show/hide spouse field */
function toggleSpouse(val){
  const f = document.getElementById('spouse-field');
  if(f) f.style.display = (val === 'Married / Partner') ? 'block' : 'none';
}

/* Main handler: validate → submit intake to Formspree → redirect to Stripe */
function handleSubmit(e){
  e.preventDefault();
  const form  = e.target;
  const name  = (document.getElementById('full-name')?.value || '').trim();
  const email = (document.getElementById('email')?.value || '').trim();
  const pkgEl = form.querySelector('input[name="package"]:checked');
  const btn   = document.getElementById('pay-btn');

  /* ── Validation ── */
  if(!name || !email){
    alert('Please fill in your full name and email address before proceeding.');
    return;
  }
  if(!pkgEl){
    alert('Please select a package (Section 05) before proceeding to payment.');
    document.querySelector('.radio-group')?.scrollIntoView({behavior:'smooth', block:'center'});
    return;
  }

  const stripeLink = STRIPE_LINKS[pkgEl.value];

  /* ── Guard: Stripe links not yet configured ── */
  if(!stripeLink || stripeLink.includes('_HERE')){
    alert('⚙️ Payment not yet configured.\n\nSamuel: paste your Stripe Payment Link URLs into the STRIPE_LINKS object at the bottom of index.html.\n\nCreate them at dashboard.stripe.com → Payment Links.');
    return;
  }

  /* ── Lock button while submitting ── */
  if(btn){ btn.disabled = true; btn.textContent = 'Submitting your form...'; }

  /* ── Step 1: Submit intake form to Formspree ── */
  const data = new FormData(form);
  fetch(form.action, {method:'POST', body:data, headers:{'Accept':'application/json'}})
    .finally(() => {
      /* Step 2: Redirect to Stripe Payment Link regardless of Formspree result.
         Stripe pre-fills client email and passes their name as a reference.
         Samuel receives: Formspree email (intake data) + Stripe email (payment). */
      const url = stripeLink
        + '?prefilled_email=' + encodeURIComponent(email)
        + '&client_reference_id=' + encodeURIComponent(name.replace(/\s+/g, '_').substring(0, 64));
      if(btn){ btn.textContent = 'Redirecting to payment...'; }
      window.location.href = url;
    });
}
</script>
</body>
</html>

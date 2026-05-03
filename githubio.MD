---
layout: default
title: MediaEstimator - Media & Storage Planning for Production
---

<style>
  :root {
    --accent: #3478F6;
    --bg-dark: #1a1a2e;
  }
  .hero {
    text-align: center;
    padding: 60px 20px 40px;
  }
  .hero h1 {
    font-size: 2.8em;
    margin-bottom: 10px;
  }
  .hero .tagline {
    font-size: 1.3em;
    color: #888;
    margin-bottom: 30px;
  }
  .badge-row {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
    margin-bottom: 40px;
  }
  .badge-row img {
    height: 40px;
  }
  .screenshot-showcase {
    text-align: center;
    margin: 0 auto 60px;
    max-width: 960px;
  }
  .screenshot-showcase img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.3);
  }
  .features {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px;
  }
  .feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 30px;
    margin: 40px 0 60px;
  }
  .feature-card {
    padding: 24px;
    border-radius: 12px;
    background: #f6f8fa;
    border: 1px solid #e1e4e8;
  }
  .feature-card h3 {
    margin-top: 0;
  }
  .feature-card p {
    color: #586069;
    margin-bottom: 0;
  }
  .screenshot-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    max-width: 960px;
    margin: 30px auto 60px;
  }
  .screenshot-grid img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 8px 30px rgba(0,0,0,0.15);
  }
  .section-header {
    text-align: center;
    margin: 60px 0 10px;
  }
  .section-header h2 {
    font-size: 2em;
  }
  .section-header p {
    color: #888;
    font-size: 1.1em;
  }
  .camera-list {
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px;
  }
  .camera-brands {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px 20px;
    margin: 20px 0 60px;
    font-size: 1.05em;
  }
  .camera-brands span {
    background: #f0f0f0;
    padding: 6px 14px;
    border-radius: 20px;
    white-space: nowrap;
  }
  .pricing {
    max-width: 700px;
    margin: 0 auto 60px;
    padding: 0 20px;
  }
  .pricing-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 30px;
  }
  .pricing-card {
    padding: 30px;
    border-radius: 12px;
    border: 1px solid #e1e4e8;
    text-align: center;
  }
  .pricing-card.pro {
    border-color: var(--accent);
    background: #f0f6ff;
  }
  .pricing-card h3 {
    margin-top: 0;
  }
  .pricing-card ul {
    text-align: left;
    padding-left: 20px;
  }
  .cta {
    text-align: center;
    padding: 60px 20px;
  }
  .cta a {
    display: inline-block;
    background: var(--accent);
    color: white;
    padding: 14px 36px;
    border-radius: 10px;
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 600;
  }
  .footer {
    text-align: center;
    padding: 40px 20px;
    color: #999;
    font-size: 0.9em;
  }

  @media (prefers-color-scheme: dark) {
    .feature-card {
      background: #161b22;
      border-color: #30363d;
    }
    .feature-card p {
      color: #8b949e;
    }
    .camera-brands span {
      background: #21262d;
    }
    .pricing-card {
      border-color: #30363d;
    }
    .pricing-card.pro {
      background: #0d1117;
      border-color: var(--accent);
    }
  }

  @media (max-width: 600px) {
    .hero h1 { font-size: 2em; }
    .screenshot-grid { grid-template-columns: 1fr; }
    .pricing-grid { grid-template-columns: 1fr; }
  }
</style>

<div class="hero">
  <h1>MediaEstimator</h1>
  <p class="tagline">Know your storage before you roll.</p>
  <p>The media workflow calculator built for film and television professionals.<br>Estimate storage, cards, offload times, and archival — instantly and accurately.</p>
</div>

<div class="screenshot-showcase">
  <img src="screenshots/2880x1800/darkmode1.png" alt="MediaEstimator summary view in dark mode">
</div>

---

<div class="section-header">
  <h2>Everything You Need to Plan a Shoot</h2>
  <p>From daily card counts to season-long tape archives, every number updates in real time.</p>
</div>

<div class="features">
  <div class="feature-grid">
    <div class="feature-card">
      <h3>Raw Media Estimates</h3>
      <p>Calculate daily, weekly, and seasonal raw footage in GB and TB — with single, dual, or triple copy totals.</p>
    </div>
    <div class="feature-card">
      <h3>Media Cards by Type</h3>
      <p>Know exactly how many XQD, CFexpress, SD, or SSD cards you need per day, per week, and for the entire season.</p>
    </div>
    <div class="feature-card">
      <h3>DIT Offload Hours</h3>
      <p>Estimate daily processing time based on card types, capacities, and realistic offload speeds.</p>
    </div>
    <div class="feature-card">
      <h3>Media Shuttles</h3>
      <p>Calculate how many SSDs, hard drives, RAID arrays, or NAS units you need — with multi-day accumulation support.</p>
    </div>
    <div class="feature-card">
      <h3>Server Storage</h3>
      <p>Get NAS estimates for raw media and Avid NEXIS sizing for proxy workflows with automatic headroom.</p>
    </div>
    <div class="feature-card">
      <h3>LTO Tape Archive</h3>
      <p>Plan your long-term archive with tape estimates for LTO-6 through LTO-9, in single and dual copy configurations.</p>
    </div>
  </div>
</div>

---

<div class="section-header">
  <h2>See It in Action</h2>
  <p>A clean, focused interface designed for production workflows.</p>
</div>

<div class="screenshot-grid">
  <div>
    <img src="screenshots/Screenshot 2026-04-14 at 8.18.10 AM.png" alt="Project setup and shoot day configuration">
    <p style="text-align:center; color:#888; margin-top:8px;"><em>Configure your project, shoot days, and day types</em></p>
  </div>
  <div>
    <img src="screenshots/Screenshot 2026-04-14 at 8.18.36 AM.png" alt="Camera and audio source configuration">
    <p style="text-align:center; color:#888; margin-top:8px;"><em>Add cameras with codec, resolution, and frame rate</em></p>
  </div>
  <div>
    <img src="screenshots/Screenshot 2026-04-14 at 8.18.45 AM.png" alt="Summary dashboard with all calculations">
    <p style="text-align:center; color:#888; margin-top:8px;"><em>Real-time summary with every number you need</em></p>
  </div>
  <div>
    <img src="screenshots/Screenshot 2026-04-14 at 8.18.50 AM.png" alt="LTO archive and hours shot estimates">
    <p style="text-align:center; color:#888; margin-top:8px;"><em>LTO archive estimates and total hours shot</em></p>
  </div>
</div>

<div class="screenshot-showcase">
  <img src="screenshots/2880x1800/lightmode.png" alt="MediaEstimator in light mode">
  <p style="text-align:center; color:#888; margin-top:10px;"><em>Light and dark mode support</em></p>
</div>

---

<div class="section-header">
  <h2>20+ Professional Cameras</h2>
  <p>Accurate codec data rates, card types, and offload times for the cameras you actually use.</p>
</div>

<div class="camera-list">
  <div class="camera-brands">
    <span>Sony FX9</span>
    <span>Sony Venice</span>
    <span>Sony Venice 2</span>
    <span>Sony FX3</span>
    <span>Sony FX6</span>
    <span>Sony FS7</span>
    <span>ARRI ALEXA 35</span>
    <span>ARRI ALEXA Mini LF</span>
    <span>RED V-Raptor</span>
    <span>RED Komodo</span>
    <span>RED Weapon</span>
    <span>Canon C300 MkII</span>
    <span>Canon C500 MkII</span>
    <span>Canon C70</span>
    <span>Panasonic GH5</span>
    <span>Panasonic GH6</span>
    <span>Panasonic EVA1</span>
    <span>Blackmagic Pocket 6K</span>
    <span>Blackmagic URSA Mini Pro</span>
    <span>DJI Drone</span>
    <span>GoPro</span>
    <span>iPhone</span>
    <span>Audio (BWF)</span>
  </div>
</div>

---

<div class="section-header">
  <h2>Print-Ready Reports</h2>
  <p>Generate professional summaries for production binders and budget meetings.</p>
</div>

<div class="screenshot-showcase">
  <img src="screenshots/PrintPreview.png" alt="Printable summary report" style="max-width: 600px; margin: 20px auto; display: block;">
</div>

---

<div class="section-header">
  <h2>Flexible Plans</h2>
  <p>Get started for free. Upgrade when you need more.</p>
</div>

<div class="pricing">
  <div class="pricing-grid">
    <div class="pricing-card">
      <h3>Free</h3>
      <ul>
        <li>Unlimited projects</li>
        <li>Up to 2 cameras per project</li>
        <li>Full summary calculations</li>
        <li>All camera and codec data</li>
      </ul>
    </div>
    <div class="pricing-card pro">
      <h3>Pro</h3>
      <p><strong>Monthly or Annual</strong></p>
      <ul>
        <li>Unlimited cameras</li>
        <li>Duplicate camera rows</li>
        <li>Duplicate projects</li>
        <li>Print summaries</li>
      </ul>
    </div>
  </div>
</div>

---

<div class="cta">
  <h2>Ready to plan your next production?</h2>
  <p style="color:#888; margin-bottom:30px;">Available on the Mac App Store.</p>
  <a href="#">Download MediaEstimator</a>
</div>

<div class="footer">
  <p>MediaEstimator is designed and built for production professionals.</p>
  <p>&copy; 2026 MediaEstimator. All rights reserved.</p>
</div>

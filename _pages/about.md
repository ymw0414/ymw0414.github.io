---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .about-title {
    font-family: 'Crimson Pro', Georgia, serif !important;
    font-size: 1.85rem;
    font-weight: 500;
    color: #1a1a1a;
    margin: 0 0 0.5rem 0;
    line-height: 1.2;
    letter-spacing: -0.015em;
  }
  .about-subtitle {
    font-family: 'Crimson Pro', Georgia, serif !important;
    font-size: 1.05rem;
    font-style: italic;
    color: #666;
    margin: 0 0 2.5rem 0;
    font-weight: 400;
    padding-bottom: 1.5rem;
    border-bottom: 1px solid #eee;
  }
  .about-section { margin-top: 2.2rem; }
  .about-section h3 {
    font-family: 'JetBrains Mono', 'Courier New', monospace !important;
    text-transform: lowercase;
    letter-spacing: 0;
    font-size: 0.72rem;
    color: #888;
    font-weight: 500;
    margin: 0 0 0.9rem 0;
  }
  .about-section h3::before {
    content: "// ";
    color: #bbb;
  }
  .about-interests {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .about-interests li {
    position: relative;
    padding: 0.1rem 0 0.1rem 1rem;
    font-size: 0.95rem;
    color: #1a1a1a;
    line-height: 1.55;
  }
  .about-interests li::before {
    content: "—";
    position: absolute;
    left: 0;
    top: 0.1rem;
    color: #999;
    font-family: 'Inter', sans-serif;
  }
  .about-contact p {
    margin: 0;
    line-height: 1.5;
    font-size: 0.95rem;
    color: #1a1a1a;
  }
  .about-contact a {
    color: #1a1a1a;
    text-decoration: none !important;
    border-bottom: 1px solid #1a1a1a !important;
    padding-bottom: 1px;
  }
  .about-contact a:hover { opacity: 0.6; }
  .about-actions { margin-top: 2.5rem; }
  .about-cv-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.45rem;
    background: transparent;
    color: #1a1a1a !important;
    padding: 0.55rem 0;
    border: none !important;
    border-bottom: 1.5px solid #1a1a1a !important;
    border-radius: 0;
    font-family: 'JetBrains Mono', 'Courier New', monospace !important;
    font-size: 0.82rem;
    font-weight: 500;
    letter-spacing: 0;
    text-decoration: none !important;
    text-transform: lowercase;
    transition: all 0.15s ease;
  }
  .about-cv-btn::before { content: "↓"; font-size: 1rem; }
  .about-cv-btn:hover { opacity: 0.55; }
</style>

<h1 class="about-title">Minwoo Yoo</h1>
<p class="about-subtitle">Ph.D. Candidate in Economics · The George Washington University</p>

<div class="about-section">
  <h3>research interests</h3>
  <ul class="about-interests">
    <li>Applied Microeconomics</li>
    <li>Political Economy</li>
    <li>Text Analysis / Machine Learning</li>
  </ul>
</div>

<div class="about-section about-contact">
  <h3>contact</h3>
  <p><a href="mailto:ymw0414@gmail.com">ymw0414@gmail.com</a></p>
</div>

<div class="about-actions">
  <a class="about-cv-btn" href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">curriculum vitae.pdf</a>
</div>

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
    font-size: 1.6rem;
    font-weight: 700;
    color: #111;
    margin: 0 0 0.3rem 0;
    line-height: 1.2;
    letter-spacing: -0.02em;
  }
  .about-subtitle {
    font-size: 0.98rem;
    color: #666;
    margin: 0 0 2.8rem 0;
    font-weight: 400;
    letter-spacing: -0.005em;
  }
  .about-section { margin-top: 2rem; }
  .about-section h3 {
    text-transform: uppercase;
    letter-spacing: 0.14em;
    font-size: 0.7rem;
    color: #999;
    font-weight: 600;
    margin: 0 0 0.85rem 0;
  }
  .about-interests {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .about-interests li {
    position: relative;
    padding: 0.18rem 0 0.18rem 0.95rem;
    font-size: 0.95rem;
    color: #1a1a1a;
    line-height: 1.5;
  }
  .about-interests li::before {
    content: "—";
    position: absolute;
    left: 0;
    top: 0.18rem;
    color: #bbb;
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
    border-bottom: 1px solid #ccc !important;
    padding-bottom: 1px;
    transition: border-color 0.15s ease;
  }
  .about-contact a:hover { border-bottom-color: #1a1a1a !important; }
  .about-actions { margin-top: 2.5rem; }
  .about-cv-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    background: transparent;
    color: #1a1a1a !important;
    padding: 0.5rem 0;
    border: none !important;
    border-bottom: 1.5px solid #1a1a1a !important;
    border-radius: 0;
    font-size: 0.85rem;
    font-weight: 600;
    letter-spacing: 0.02em;
    text-decoration: none !important;
    transition: opacity 0.15s ease;
  }
  .about-cv-btn::after { content: "↓"; font-size: 1rem; line-height: 1; }
  .about-cv-btn:hover { opacity: 0.55; }
</style>

<h1 class="about-title">Minwoo Yoo</h1>
<p class="about-subtitle">Ph.D. Candidate in Economics, The George Washington University</p>

<div class="about-section">
  <h3>Research Interests</h3>
  <ul class="about-interests">
    <li>Applied Microeconomics</li>
    <li>Political Economy</li>
    <li>Text Analysis / Machine Learning</li>
  </ul>
</div>

<div class="about-section about-contact">
  <h3>Contact</h3>
  <p><a href="mailto:ymw0414@gmail.com">ymw0414@gmail.com</a></p>
</div>

<div class="about-actions">
  <a class="about-cv-btn" href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Download CV</a>
</div>

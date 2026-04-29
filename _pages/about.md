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
    color: #c47d2c;
    font-size: 1.18rem;
    font-weight: 600;
    margin: 0 0 1.6rem 0;
    line-height: 1.4;
    letter-spacing: -0.005em;
  }
  .about-section { margin-top: 1.7rem; }
  .about-section h3 {
    text-transform: uppercase;
    letter-spacing: 0.14em;
    font-size: 0.72rem;
    color: #999;
    font-weight: 600;
    margin: 0 0 0.7rem 0;
  }
  .about-interests {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .about-interests li {
    position: relative;
    padding: 0.15rem 0 0.15rem 0.95rem;
    font-size: 0.95rem;
    color: #1a1a1a;
    line-height: 1.45;
  }
  .about-interests li::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0.62rem;
    width: 4px;
    height: 4px;
    background: #c47d2c;
    border-radius: 50%;
  }
  .about-contact p {
    margin: 0;
    line-height: 1.5;
    font-size: 0.95rem;
    color: #1a1a1a;
  }
  .about-contact a {
    color: #c47d2c;
    text-decoration: none !important;
    border-bottom: none !important;
  }
  .about-contact a:hover { color: #9c5d18; }
  .about-actions {
    margin-top: 2rem;
    padding-top: 1.4rem;
    border-top: 1px solid #eee;
  }
  .about-cv-btn {
    display: inline-block;
    background: transparent;
    color: #c47d2c !important;
    padding: 0.5rem 1.4rem;
    border: 1.5px solid #c47d2c;
    border-radius: 999px;
    font-size: 0.78rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-decoration: none !important;
    text-transform: uppercase;
    transition: all 0.15s ease;
  }
  .about-cv-btn:hover {
    background: #c47d2c;
    color: #fff !important;
  }
</style>

<p class="about-title">Ph.D. Candidate, The George Washington University</p>

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

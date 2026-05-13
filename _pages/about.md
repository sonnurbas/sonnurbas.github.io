---
layout: page
title: about
permalink: /
nav: true
nav_order: 1
---

<style>
  .about-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    margin: 1rem 0 2rem;
  }
  .about-image {
    flex: 0 0 180px;
    text-align: center;
  }
  .about-image img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  }
  .about-text {
    flex: 1;
    min-width: 200px;
  }
  .intro-text {
    font-size: 1.1rem;
    line-height: 1.5;
    color: #2c3e4e;
    margin-bottom: 1rem;
  }
  .cv-email {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    align-items: center;
    margin-top: 1rem;
  }
  .btn-cv {
    background: #1f6392;
    color: white;
    padding: 0.4rem 1.2rem;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 500;
    font-size: 0.9rem;
    transition: background 0.2s;
    display: inline-block;
  }
  .btn-cv:hover {
    background: #0a4570;
  }
  .email-link {
    color: #1f6392;
    text-decoration: none;
    font-weight: 500;
  }
  .email-link:hover {
    text-decoration: underline;
  }
  @media (max-width: 600px) {
    .about-container {
      flex-direction: column;
      align-items: center;
    }
    .about-text {
      text-align: center;
    }
    .cv-email {
      justify-content: center;
    }
  }
</style>

<div class="about-container">
  <div class="about-image">
    <img src="/assets/images/prof_pic.jpg" alt="Sonnur Bas">
  </div>
  <div class="about-text">
    <div class="intro-text">
      Hi! I’m <strong>Sonnur Bas</strong>, a third-year PhD student at <a href="https://cemfi.es/" target="_blank">CEMFI</a>.  
      My research focuses on <strong>Industrial Organization</strong> with a particular emphasis on <strong>Energy Economics</strong>.  
      I’m passionate about understanding market dynamics and policy impacts in the energy sector.
    </div>
    <div class="cv-email">
      <a href="/cv/" class="btn-cv">📄 View my CV</a>
      <a href="mailto:sonnur.bas@cemfi.edu.es" class="email-link">✉️ sonnur.bas@cemfi.edu.es</a>
    </div>
    <!-- No research interests line, no address, no extra name -->
  </div>
</div>
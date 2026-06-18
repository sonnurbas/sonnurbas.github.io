---
layout: page
permalink: /teaching/
title: teaching
description: 
nav: true
nav_order: 6
calendar: true
---
<!-- Teaching section: prominent CEMFI cards (static, no fake links) + simple list for Pre‑PhD -->
<style>
  /* CEMFI cards – visually important, not clickable */
  .cemfi-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2rem;
    margin: 1.5rem 0 2rem;
  }

  .cemfi-card {
    background: #ffffff;
    border-radius: 20px;
    padding: 1.4rem;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08), 0 2px 4px rgba(0, 0, 0, 0.02);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    border-left: 5px solid #1f6392;
    /* no cursor pointer */
  }

  .cemfi-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 16px 28px rgba(0, 0, 0, 0.12);
  }

  .uni-badge-important {
    font-size: 0.7rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #1f6392;
    margin-bottom: 0.5rem;
  }

  .course-title-important {
    font-size: 1.3rem;
    font-weight: 700;
    margin: 0.25rem 0 0.2rem;
    color: #0a2942;
  }

  .instructor-important {
    font-size: 0.9rem;
    color: #2c5a74;
    margin-bottom: 0.75rem;
  }

  .pdf-links {
    margin-top: 1rem;
    border-top: 1px solid #e9edf2;
    padding-top: 0.8rem;
    display: flex;
    gap: 1.2rem;
  }

  .pdf-links a {
    text-decoration: none;
    color: #1f6392;
    font-weight: 500;
    font-size: 0.85rem;
  }

  .pdf-links a:hover {
    text-decoration: underline;
  }

  /* Pre‑PhD section – simple open list, one line per course */
  .prephd-section {
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid #e2e8f0;
  }

  .prephd-title {
    font-weight: 600;
    font-size: 1rem;
    margin-bottom: 0.75rem;
    color: #2c3e4e;
  }

  .simple-list {
    list-style-type: disc;
    margin-left: 1.2rem;
    padding-left: 0;
  }

  .simple-list li {
    margin-bottom: 0.35rem;
    font-size: 0.9rem;
    color: #2c3e4e;
  }

  .simple-list li strong {
    font-weight: 600;
  }

  @media (max-width: 640px) {
    .cemfi-card {
      padding: 1rem;
    }
    .course-title-important {
      font-size: 1.1rem;
    }
  }
</style>

<!-- CEMFI – important, prominent cards (not clickable) -->
<div class="cemfi-grid">
  <div class="cemfi-card">
    <div class="uni-badge-important">CEMFI · Graduate TA</div>
    <div class="course-title-important">Energy Economics</div>
    <div class="instructor-important">Natalia Fabra</div>
    <div class="pdf-links">

      <a href="/assets/pdf/bas_eval_energy_fall25.pdf" target="_blank">
  📊 Evaluations
</a>
    </div>
  </div>

  <div class="cemfi-card">
    <div class="uni-badge-important">CEMFI · Graduate TA</div>
    <div class="course-title-important">Regulation & Competition Policy</div>
    <div class="instructor-important">Gerard Llobet</div>
    <div class="pdf-links">
      <a href="/assets/pdf/bas_eval_regulation_fall25.pdf" target="_blank">
  📊 Evaluations
</a>
    </div>
  </div>
</div>

<!-- Pre‑PhD Teaching Assistantships (Sabancı) – open list, one line each -->
<div class="prephd-section">
  <div class="prephd-title">📖 Pre‑PhD Teaching Assistantships · Sabancı University</div>
  <ul class="simple-list">
    <li><strong>Microeconomics II (graduate)</strong> – Eren Inci</li>
    <li><strong>Industrial Organization (undergraduate)</strong> – Esra Durceylan Kaygusuz</li>
    <li><strong>Macroeconomics I (graduate)</strong> – Emrahan Aktug</li>
    <li><strong>Microeconomics (undergraduate)</strong> – Yusuf Emre Akgunduz</li>
    <li><strong>Game Theory (undergraduate)</strong> – Mehmet Barlo</li>
    <li><strong>Advanced Microeconomics (undergraduate)</strong> – Mehmet Barlo</li>
  </ul>
</div>
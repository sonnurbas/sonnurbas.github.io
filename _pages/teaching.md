---
layout: page
permalink: /teaching/
title: teaching
description: 
nav: true
nav_order: 6
calendar: true
---
<!-- Teaching section: prominent CEMFI cards + compact Pre‑PhD list for Sabancı -->
<style>
  /* CEMFI card styles (important) */
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
    cursor: pointer;
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

  .pdf-link-placeholder {
    font-size: 0.8rem;
    margin-top: 1rem;
    border-top: 1px solid #e9edf2;
    padding-top: 0.8rem;
    display: flex;
    gap: 1rem;
  }

  .pdf-link-placeholder a {
    text-decoration: none;
    color: #1f6392;
    font-weight: 500;
  }

  /* Pre‑PhD / Sabancı section – compact and less fancy */
  .prephd-section {
    margin-top: 2rem;
    padding-top: 0.5rem;
    border-top: 1px solid #e2e8f0;
  }

  .prephd-section summary {
    font-weight: 600;
    font-size: 0.95rem;
    cursor: pointer;
    color: #4a627a;
    background: #f8fafc;
    padding: 0.5rem 1rem;
    border-radius: 30px;
    display: inline-block;
    transition: background 0.1s;
  }

  .prephd-section summary:hover {
    background: #eef2f8;
  }

  .compact-list {
    margin-top: 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    list-style: none;
    padding-left: 0;
  }

  .compact-list li {
    background: #f1f5f9;
    padding: 0.2rem 0.8rem;
    border-radius: 30px;
    font-size: 0.8rem;
    color: #1e3a5f;
    display: inline-block;
    border: none;
    box-shadow: none;
  }

  .compact-list li strong {
    font-weight: 600;
  }

  /* remove any fancy hover on these list items */
  .compact-list li:hover {
    background: #e6edf4;
    transform: none;
    box-shadow: none;
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

<!-- CEMFI – important, prominent cards -->
<div class="cemfi-grid">
  <div class="cemfi-card" onclick="location.href='#cemfi-energy';">
    <div class="uni-badge-important">🇪🇸 CEMFI · Graduate TA</div>
    <div class="course-title-important">Energy Economics</div>
    <div class="instructor-important">Natalia Fabra</div>
    <div class="pdf-link-placeholder">
      <a href="#">📄 Slides (soon)</a>
      <a href="#">📊 Evaluations (soon)</a>
    </div>
  </div>

  <div class="cemfi-card" onclick="location.href='#cemfi-regulation';">
    <div class="uni-badge-important">🇪🇸 CEMFI · Graduate TA</div>
    <div class="course-title-important">Regulation & Competition Policy</div>
    <div class="instructor-important">Gerard Llobet</div>
    <div class="pdf-link-placeholder">
      <a href="#">📄 Slides (soon)</a>
      <a href="#">📊 Evaluations (soon)</a>
    </div>
  </div>
</div>

<!-- Pre‑PhD TAships (Sabancı) – compact, collapsible, less space -->
<div class="prephd-section">
  <details>
    <summary>📚 Pre‑PhD Teaching Assistantships (Sabancı University, 7 courses)</summary>
    <ul class="compact-list">
      <li><strong>Microeconomics II (grad)</strong> – Eren Inci</li>
      <li><strong>Industrial Organization (undergrad)</strong> – Esra Durceylan Kaygusuz</li>
      <li><strong>Macroeconomics I (grad)</strong> – Emrahan Aktug</li>
      <li><strong>Microeconomics (undergrad)</strong> – Yusuf Emre Akgunduz</li>
      <li><strong>Game Theory (undergrad)</strong> – Mehmet Barlo</li>
      <li><strong>Advanced Microeconomics (undergrad)</strong> – Mehmet Barlo</li>
    </ul>
  </details>
</div>
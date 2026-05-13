---
layout: page
permalink: /research/
title: research
description: research projects and work in progress.
nav: true
nav_order: 2
---

<!-- Research page with dynamic cards for projects -->
<style>
  /* Consistent card style (similar to teaching, but adapted) */
  .research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 2rem;
    margin: 1.5rem 0 2rem;
  }

  .research-card {
    background: #ffffff;
    border-radius: 20px;
    padding: 1.4rem;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08), 0 2px 4px rgba(0, 0, 0, 0.02);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    border-left: 5px solid #2c7da0; /* slightly different from teaching */
  }

  .research-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 16px 28px rgba(0, 0, 0, 0.12);
  }

  .project-title {
    font-size: 1.2rem;
    font-weight: 700;
    margin: 0.2rem 0 0.5rem;
    color: #0a2942;
    line-height: 1.3;
  }

  .project-description {
    font-size: 0.9rem;
    color: #2c5a74;
    margin: 0.75rem 0 1rem;
    line-height: 1.5;
  }

  .research-links {
    margin-top: 1rem;
    border-top: 1px solid #e9edf2;
    padding-top: 0.8rem;
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
  }

  .research-links a {
    text-decoration: none;
    font-size: 0.85rem;
    font-weight: 500;
    color: #1f6392;
  }

  .research-links a:hover {
    text-decoration: underline;
  }

  .section-title {
    font-size: 1.5rem;
    font-weight: 600;
    margin: 2rem 0 0.5rem 0;
    padding-bottom: 0.25rem;
    border-bottom: 2px solid #e2e8f0;
    color: #1e2a3e;
  }

  .section-title:first-of-type {
    margin-top: 0;
  }

  .empty-note {
    color: #6c7a8a;
    font-style: italic;
    margin: 1rem 0;
  }

  @media (max-width: 640px) {
    .research-card {
      padding: 1rem;
    }
    .project-title {
      font-size: 1rem;
    }
  }
</style>

<!-- Work in Progress (has your current project) -->
<div class="section-title">⚙️ Work in Progress</div>
<div class="research-grid">
  <div class="research-card">
    <div class="project-title">Market Integration in Natural Gas: Evidence from the Spanish Market</div>
    <div class="project-description">
      This project studies how institutional integration can improve efficiency in fragmented infrastructure markets. We focus on Spain’s liquefied natural gas (LNG) system, where, until 2020, transactions occurred at terminal-specific platforms, requiring retailers and sellers to coordinate locally. Using comprehensive data on LNG shipments, terminal activity, and wholesale gas trade from 2018–2024, we analyze Spain’s 2020 reform, which centralized trading through a unified market. The empirical analysis reveals increasing LNG trade volume, improved terminal utilization, and more cost-efficient routing decisions.
    </div>
    <div class="research-links">
      <a href="#">📄 PDF (coming soon)</a>
      <a href="#">📊 Slides (coming soon)</a>
      <a href="#">📁 Code / Data (coming soon)</a>
    </div>
  </div>
  <!-- You can add more WIP projects here, each as a new .research-card -->
</div>


---
layout: page
permalink: /research/
title: research
description: research projects and work in progress.
nav: true
nav_order: 2
---

<!-- Research page: full‑width cards, stacked vertically -->
<style>
  /* Cards take full width, stack vertically */
  .research-list {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    margin: 1.5rem 0 2rem;
  }

  .research-card {
    background: #ffffff;
    border-radius: 20px;
    padding: 1.4rem;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08), 0 2px 4px rgba(0, 0, 0, 0.02);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    border-left: 5px solid #2c7da0;
    width: 100%; /* full width of parent */
  }

  .research-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 16px 28px rgba(0, 0, 0, 0.12);
  }

  .project-title {
    font-size: 1.3rem;
    font-weight: 700;
    margin: 0.2rem 0 0.5rem;
    color: #0a2942;
    line-height: 1.3;
  }

  .project-description {
    font-size: 0.95rem;
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
    gap: 1.2rem;
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
      font-size: 1.1rem;
    }
  }
</style>


<!-- Work in Progress (full‑width cards, stacked) -->
<div class="section-title">⚙️ Work in Progress</div>
<div class="research-list">
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
  <!-- Future projects: add another <div class="research-card"> here, it will appear below -->
  <div class="research-card">
    <div class="project-title">Greenwashed? Tracking Sustainability Narratives in Big
Oil</div>
    <div class="project-description">
      This study develops a data-driven framework to detect greenwashing in major oil and gas companies by analyzing the relationship between corporate sustainability communication and ESG performance. Using a dataset of over 2,000 scraped press releases and news articles, we apply sentiment analysis to quantify sustainability-related language. These textual features are combined with monthly ESG ratings and financial indicators, including oil prices and stock returns, to build an integrated empirical dataset. We showed that corporate sustainability language is closely linked to ESG performance, but may also reflect strategic communication rather than substantive environmental improvement. Overall, the findings provide evidence consistent with potential greenwashing and demonstrate a scalable approach for monitoring corporate sustainability claims over time.
    </div>
    <div class="research-links">
      <a href="#">📄 PDF (coming soon)</a>
      <a href="#">📊 Slides (coming soon)</a>
      <a href="#">📁 Code / Data (coming soon)</a>
    </div>
  </div>
</div>



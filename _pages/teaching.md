---
layout: page
permalink: /teaching/
title: teaching
description: 
nav: true
nav_order: 6
calendar: true
---
<!-- Teaching section with clickable cards & subtle hover effect -->
<style>
  .teaching-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.8rem;
    margin: 2rem 0 1rem;
  }

  .teaching-card {
    background: #ffffff;
    border-radius: 16px;
    padding: 1.2rem 1.2rem 1rem 1.2rem;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05), 0 1px 2px rgba(0, 0, 0, 0.03);
    transition: transform 0.2s ease, box-shadow 0.25s ease;
    border-left: 4px solid #2c7da0;
    cursor: pointer;
  }

  .teaching-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 22px rgba(0, 0, 0, 0.08), 0 4px 8px rgba(0, 0, 0, 0.02);
  }

  .uni-badge {
    font-size: 0.7rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    color: #2c7da0;
    font-weight: 600;
    margin-bottom: 0.5rem;
  }

  .course-title {
    font-weight: 700;
    font-size: 1.05rem;
    margin: 0.2rem 0 0.1rem;
    color: #1e2a3e;
  }

  .instructor {
    font-size: 0.85rem;
    color: #4a5b6e;
    margin: 0.2rem 0;
  }

  .role-tag {
    display: inline-block;
    background: #eef2f5;
    padding: 0.2rem 0.7rem;
    border-radius: 20px;
    font-size: 0.7rem;
    font-weight: 500;
    margin-top: 0.6rem;
    color: #1f5068;
  }

  /* Optional subtle animation for the whole section */
  .teaching-section-intro {
    margin-bottom: 1rem;
    font-size: 0.95rem;
  }

  @media (max-width: 640px) {
    .teaching-grid {
      gap: 1rem;
    }
    .teaching-card {
      padding: 1rem;
    }
  }
</style>

<div class="teaching-section-intro">
  <p>I have served as a teaching assistant for the following courses at CEMFI and Sabancı University.</p>
</div>

<div class="teaching-grid">
  
  <!-- CEMFI cards -->
  <div class="teaching-card" onclick="location.href='#cemfi-energy';" style="cursor: pointer;">
    <div class="uni-badge">🇪🇸 CEMFI · Graduate</div>
    <div class="course-title">Energy Economics</div>
    <div class="instructor">Natalia Fabra</div>
    <span class="role-tag">Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#cemfi-regulation';" style="cursor: pointer;">
    <div class="uni-badge">🇪🇸 CEMFI · Graduate</div>
    <div class="course-title">Regulation & Competition Policy</div>
    <div class="instructor">Gerard Llobet</div>
    <span class="role-tag">Teaching Assistant</span>
  </div>

  <!-- Sabancı University cards -->
  <div class="teaching-card" onclick="location.href='#sabanci-micro2';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Graduate</div>
    <div class="course-title">Microeconomics II</div>
    <div class="instructor">Eren Inci</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#sabanci-io';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Undergraduate</div>
    <div class="course-title">Industrial Organization</div>
    <div class="instructor">Esra Durceylan Kaygusuz</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#sabanci-macro1';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Graduate</div>
    <div class="course-title">Macroeconomics I</div>
    <div class="instructor">Emrahan Aktug</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#sabanci-micro-ug';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Undergraduate</div>
    <div class="course-title">Microeconomics</div>
    <div class="instructor">Yusuf Emre Akgunduz</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#sabanci-gametheory';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Undergraduate</div>
    <div class="course-title">Game Theory</div>
    <div class="instructor">Mehmet Barlo</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>

  <div class="teaching-card" onclick="location.href='#sabanci-advancedmicro';" style="cursor: pointer;">
    <div class="uni-badge">🇹🇷 Sabancı University · Undergraduate</div>
    <div class="course-title">Advanced Microeconomics</div>
    <div class="instructor">Mehmet Barlo</div>
    <span class="role-tag">Graduate Teaching Assistant</span>
  </div>
</div>

<!-- Optional tiny note: the hrefs are just anchors; you can add actual links to syllabi or instructor pages later -->
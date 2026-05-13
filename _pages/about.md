---
layout: about
title: about
permalink: /

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Calle Casado del Alisal, 5</p>
    <p>Madrid, 28014</p>

social: true

full_width: true
sidebar: false

selected_papers: false
social: true
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<!-- Main page: clean two-column layout with modern typography -->
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
  .research-interest {
    margin-top: 1.5rem;
    padding-top: 0.5rem;
    border-top: 1px solid #e9edf2;
    font-size: 0.9rem;
    color: #4a627a;
  }
  .research-interest strong {
    color: #1e2a3e;
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
    <!-- The image path is taken from your front matter: profile.image = prof_pic.jpg -->
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
    <div class="research-interest">
      <strong>Research interests:</strong> Industrial Organization, Energy Economics, Market Design.
    </div>
  </div>
</div>

<!-- The social links (if enabled in front matter) will be rendered automatically by your theme.
     If not, you can add a simple social row here -->
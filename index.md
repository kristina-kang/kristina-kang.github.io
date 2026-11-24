
---
layout: default
title: Home
---

<!-- HERO SECTION -->
<section class="hero">
  <div class="hero-content">

    <div class="hero-text">

      <span class="eyebrow">
        DATA ANALYTICS &amp; BUSINESS INTELLIGENCE
      </span>

      <h1>
        Turning Data Into
        <span class="hero-heading-accent">Meaningful Insights.</span>
      </h1>

      <p class="hero-role">
        Kristina Kang <span class="role-divider">/</span> Data Analyst
      </p>

      <p class="hero-description">
        An analytical perspective on customer behavior, product performance, and business intelligence.
      </p>

      <div class="hero-actions">
        <a href="#featured-projects" class="primary-button">
          Explore My Work <span aria-hidden="true">↗</span>
        </a>
      </div>

      <div class="hero-meta">
        <span>SQL</span>
        <span>Python</span>
        <span>Tableau</span>
        <span>Business Analytics</span>
      </div>

    </div>

    <div class="hero-image-wrapper">
      <div class="image-frame">
        <img
          src="{{ '/assets/images/profile.png' | relative_url }}"
          alt="Kristina Kang, Data Analyst"
        >
      </div>
      <span class="image-caption">DATA ANALYST PORTFOLIO</span>
    </div>

  </div>

  <div class="hero-bottom-label">
    <span>PORTFOLIO</span>
    <span>2026</span>
  </div>
</section>


<!-- FEATURED PROJECTS -->
<section class="container projects-section" id="featured-projects">

  <div class="section-heading">

    <div>
      <span class="eyebrow">A SELECTION OF MY WORK</span>
      <h2>Featured Projects</h2>
    </div>

    <p class="section-description">
      Exploring data, uncovering patterns, and translating
      analytical findings into actionable business insights.
    </p>

  </div>


  <div class="projects-grid">

    <a href="{{ '/projects/project1/' | relative_url }}"
       class="project-link">

      <article class="card">

        <div class="card-top">
          <span class="project-number">01</span>
          <span class="project-category">CUSTOMER ANALYTICS</span>
        </div>

        <h3>Cyclistic Bike Share Analysis</h3>

        <p>
          Analyzed differences in usage patterns between annual members and casual riders using SQL and Tableau, exploring ride duration, frequency, and seasonal trends.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>
          <p>
            Identified distinct riding behaviors across customer segments and developed data-driven recommendations to support membership conversion.
          </p>
        </div>

        <div class="card-footer">
          <span>SQL · TABLEAU</span>
          <span class="card-arrow">↗</span>
        </div>

      </article>

    </a>


    <a href="{{ '/projects/project2/' | relative_url }}"
       class="project-link">

      <article class="card">

        <div class="card-top">
          <span class="project-number">02</span>
          <span class="project-category">PRODUCT ANALYTICS</span>
        </div>

        <h3>Bellabeat Smart Device Usage Analysis</h3>

        <p>
          Explored Fitbit activity and wellness data using SQL and Tableau to identify patterns in daily activity, exercise intensity, and user engagement.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>
          <p>
            Uncovered behavioral patterns that can inform personalized wellness experiences, customer engagement initiatives, and product marketing strategies.
          </p>
        </div>

        <div class="card-footer">
          <span>SQL · TABLEAU</span>
          <span class="card-arrow">↗</span>
        </div>

      </article>

    </a>


    <a href="{{ '/projects/project3/' | relative_url }}"
       class="project-link">

      <article class="card">

        <div class="card-top">
          <span class="project-number">03</span>
          <span class="project-category">STATISTICAL ANALYSIS</span>
        </div>

        <h3>Statistical Inference & Behavioral Data Analysis</h3>

        <p>
          Applied statistical inference techniques in R to examine student motivation and behavioral characteristics using survey-based data.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>
          <p>
            Used confidence intervals and hypothesis testing to evaluate research questions and draw evidence-based conclusions from sample data.
          </p>
        </div>

        <div class="card-footer">
          <span>R · STATISTICS</span>
          <span class="card-arrow">↗</span>
        </div>

      </article>

    </a>

  </div>

</section>


<!-- TECHNICAL SKILLS -->
<section class="skills-section">

  <div class="container">

    <div class="section-heading">

      <div>
        <span class="eyebrow">TOOLS &amp; TECHNOLOGIES</span>
        <h2>Technical Skills</h2>
      </div>

      <p class="section-description">
        Analytical tools and technologies I use
        to transform data into meaningful insights.
      </p>

    </div>

    <div class="skills">

      <span class="skill-pill">SQL</span>
      <span class="skill-pill">Python</span>
      <span class="skill-pill">Tableau</span>
      <span class="skill-pill">Power BI</span>
      <span class="skill-pill">R</span>

    </div>

  </div>

</section>


<!-- FOOTER -->
<footer class="site-footer">

  <div class="container footer-content">

    <div>
      <h3>Kristina Kang</h3>
      <p>Data Analyst Portfolio</p>
    </div>

    <a href="#top" class="back-to-top">
      Back to top ↑
    </a>

  </div>

</footer>

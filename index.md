
---
layout: default
title: Home
---

<!-- HERO SECTION -->
<section class="hero" id="top">
  <div class="hero-content">

    <!-- LEFT: INTRODUCTION -->
    <div class="hero-text">

      <span class="eyebrow">
        DATA ANALYTICS &amp; BUSINESS INTELLIGENCE
      </span>

      <h1>
        Kristina Kang
        <span class="hero-heading-accent">Data Analyst.</span>
      </h1>

      <p class="hero-role">
        Customer Insights
        <span class="role-divider">/</span>
        Product Analytics
      </p>

      <p class="hero-description">
        Customer insights. Product analytics. Data-driven strategy.
      </p>

      <div class="hero-actions">
        <a href="#featured-projects" class="primary-button">
          Explore Selected Work
          <span aria-hidden="true">↗</span>
        </a>
      </div>

      <div class="hero-meta">
        <span>SQL</span>
        <span>Python</span>
        <span>Tableau</span>
        <span>Power BI</span>
        <span>R</span>
      </div>

    </div>

    <!-- RIGHT: PROFILE IMAGE -->
    <div class="hero-image-wrapper">

      <div class="image-frame">
        <img
          src="{{ '/assets/images/profile.png' | relative_url }}"
          alt="Kristina Kang"
        >
      </div>

      <span class="image-caption">
        DATA ANALYST PORTFOLIO
      </span>

    </div>

  </div>

  <div class="hero-bottom-label">
    <span>KRISTINA KANG</span>
    <span>PORTFOLIO · 2026</span>
  </div>

</section>


<!-- FEATURED PROJECTS -->
<section
  class="container projects-section"
  id="featured-projects"
>

  <div class="section-heading">

    <div>
      <span class="eyebrow">SELECTED WORK</span>
      <h2>Featured Projects</h2>
    </div>

    <p class="section-description">
      A collection of analytical projects exploring
      customer behavior, product usage, and statistical research.
    </p>

  </div>


  <div class="projects-grid">

    <!-- PROJECT 01 -->
    <a
      href="{{ '/projects/project1/' | relative_url }}"
      class="project-link"
    >

      <article class="card">

        <div class="card-top">
          <span class="project-number">01</span>
          <span class="project-category">CUSTOMER ANALYTICS</span>
        </div>

        <h3>Cyclistic Bike Share Analysis</h3>

        <p>
          Examined differences in riding patterns between
          annual members and casual riders using SQL and Tableau,
          with a focus on ride duration, frequency, and seasonal trends.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>

          <p>
            Identified distinct customer behavior patterns
            and developed recommendations to support
            membership conversion.
          </p>
        </div>

        <div class="card-footer">
          <span>SQL · TABLEAU</span>
          <span class="card-arrow">↗</span>
        </div>

      </article>

    </a>


    <!-- PROJECT 02 -->
    <a
      href="{{ '/projects/project2/' | relative_url }}"
      class="project-link"
    >

      <article class="card">

        <div class="card-top">
          <span class="project-number">02</span>
          <span class="project-category">PRODUCT ANALYTICS</span>
        </div>

        <h3>Bellabeat Smart Device Usage Analysis</h3>

        <p>
          Explored Fitbit activity and wellness data using
          SQL and Tableau to examine daily activity,
          exercise intensity, and user engagement patterns.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>

          <p>
            Identified behavioral patterns with implications
            for personalized wellness experiences,
            product engagement, and marketing strategy.
          </p>
        </div>

        <div class="card-footer">
          <span>SQL · TABLEAU</span>
          <span class="card-arrow">↗</span>
        </div>

      </article>

    </a>


    <!-- PROJECT 03 -->
    <a
      href="{{ '/projects/project3/' | relative_url }}"
      class="project-link"
    >

      <article class="card">

        <div class="card-top">
          <span class="project-number">03</span>
          <span class="project-category">STATISTICAL ANALYSIS</span>
        </div>

        <h3>Statistical Inference &amp; Behavioral Data Analysis</h3>

        <p>
          Applied statistical inference in R to examine
          student motivation and behavioral characteristics
          using survey-based data.
        </p>

        <div class="impact">
          <span>KEY TAKEAWAY</span>

          <p>
            Applied confidence intervals and hypothesis testing
            to evaluate research questions and draw
            evidence-based conclusions.
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
        Analytical tools and technologies across
        data analysis, visualization, and statistical research.
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

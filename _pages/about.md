---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-container {
  max-width: 1150px;
  margin: 0 auto;
  padding: 20px;
}

.hero-section {
  padding: 75px 45px;
  margin-bottom: 50px;
  border-radius: 18px;
  background: linear-gradient(135deg, #0b1f3a 0%, #123f67 55%, #176b87 100%);
  color: white;
  text-align: center;
  box-shadow: 0 14px 35px rgba(11, 31, 58, 0.18);
}

.hero-section h1 {
  margin: 0 0 16px;
  font-size: 3rem;
  line-height: 1.15;
  color: white;
}

.hero-subtitle {
  margin: 0 auto 12px;
  font-size: 1.35rem;
  font-weight: 600;
  color: #e8f4f8;
}

.hero-description {
  max-width: 780px;
  margin: 0 auto 28px;
  font-size: 1.05rem;
  line-height: 1.75;
  color: #dbeaf0;
}

.hero-buttons {
  display: flex;
  justify-content: center;
  gap: 14px;
  flex-wrap: wrap;
}

.hero-button {
  display: inline-block;
  padding: 12px 23px;
  border: 2px solid white;
  border-radius: 8px;
  color: white !important;
  text-decoration: none !important;
  font-weight: 700;
  transition: all 0.25s ease;
}

.hero-button.primary {
  background: white;
  color: #123f67 !important;
}

.hero-button:hover {
  transform: translateY(-3px);
  background: white;
  color: #123f67 !important;
}

.section-heading {
  margin: 60px 0 24px;
  text-align: center;
}

.section-heading h2 {
  margin-bottom: 10px;
  font-size: 2rem;
  color: #0b1f3a;
}

.section-heading p {
  max-width: 750px;
  margin: 0 auto;
  color: #5f6b75;
  line-height: 1.7;
}

.research-feature {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 28px;
  padding: 34px;
  border: 1px solid #dfe7ec;
  border-radius: 16px;
  background: #f8fbfc;
  box-shadow: 0 8px 24px rgba(11, 31, 58, 0.07);
}

.research-feature h3 {
  margin-top: 0;
  color: #123f67;
  font-size: 1.55rem;
}

.research-feature p {
  line-height: 1.75;
  color: #3d4b55;
}

.research-details {
  padding: 24px;
  border-radius: 12px;
  background: white;
  border-left: 5px solid #176b87;
}

.research-details strong {
  color: #0b1f3a;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 22px;
}

.info-card {
  padding: 27px;
  border: 1px solid #dfe7ec;
  border-radius: 14px;
  background: white;
  box-shadow: 0 7px 20px rgba(11, 31, 58, 0.07);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.info-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 14px 28px rgba(11, 31, 58, 0.13);
}

.info-card h3 {
  margin-top: 0;
  color: #123f67;
  font-size: 1.3rem;
}

.info-card p {
  line-height: 1.65;
  color: #4c5a64;
}

.card-link {
  font-weight: 700;
  color: #176b87 !important;
  text-decoration: none !important;
}

.interest-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 16px;
}

.interest-item {
  padding: 22px 14px;
  border-radius: 12px;
  background: #eef6f8;
  text-align: center;
  font-weight: 700;
  color: #123f67;
  border-bottom: 4px solid #176b87;
}

.highlight-section {
  margin-top: 60px;
  padding: 40px;
  border-radius: 16px;
  background: #0b1f3a;
  color: white;
  text-align: center;
}

.highlight-section h2 {
  margin-top: 0;
  color: white;
}

.highlight-section p {
  max-width: 780px;
  margin: 0 auto 24px;
  color: #dbeaf0;
  line-height: 1.75;
}

.footer-note {
  margin-top: 60px;
  padding-top: 25px;
  border-top: 1px solid #dfe7ec;
  text-align: center;
  color: #6b7780;
}

@media screen and (max-width: 850px) {
  .hero-section {
    padding: 55px 25px;
  }

  .hero-section h1 {
    font-size: 2.25rem;
  }

  .research-feature {
    grid-template-columns: 1fr;
  }

  .interest-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media screen and (max-width: 600px) {
  .home-container {
    padding: 10px;
  }

  .hero-section {
    padding: 45px 20px;
    border-radius: 12px;
  }

  .hero-section h1 {
    font-size: 1.9rem;
  }

  .hero-subtitle {
    font-size: 1.1rem;
  }

  .card-grid,
  .interest-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-container">

  <section class="hero-section">
    <h1>Thouhidul Islam Rajon</h1>

    <p class="hero-subtitle">
      Mechanical Engineering Graduate Student
    </p>

    <p class="hero-description">
      Researcher and engineering professional specializing in additive
      manufacturing, computational fluid dynamics, porous structure design,
      experimental testing, and advanced manufacturing.
    </p>

    <div class="hero-buttons">
      <a class="hero-button primary" href="/about/">About Me</a>
      <a class="hero-button" href="/research/">View Research</a>
      <a class="hero-button" href="/projects/">View Projects</a>
      <a class="hero-button" href="/cv/">View CV</a>
    </div>
  </section>

  <div class="section-heading">
    <h2>About Me</h2>
    <p>
      I am pursuing a Master of Science in Mechanical Engineering at
      Grand Valley State University. My background combines mechanical
      engineering, industrial and production engineering, research,
      manufacturing, rapid prototyping, and engineering design.
    </p>
  </div>

  <section class="research-feature">
    <div>
      <h3>Featured Research</h3>

      <h4>
        Development of 3D-Printed Porous Structures for
        Laboratory-Scale Compost Aeration
      </h4>

      <p>
        My master's thesis focuses on designing, fabricating, and evaluating
        3D-printed aeration structures for laboratory-scale composting systems.
        The research investigates airflow distribution and the effects of
        aeration on temperature, carbon dioxide concentration, relative
        humidity, and mass reduction.
      </p>

      <a class="card-link" href="/research/">
        Explore my research →
      </a>
    </div>

    <div class="research-details">
      <p><strong>Institution:</strong><br>Grand Valley State University</p>

      <p>
        <strong>Research Areas:</strong><br>
        Additive Manufacturing, CFD, Experimental Testing,
        Sustainable Engineering
      </p>

      <p>
        <strong>Tools:</strong><br>
        nTopology, CAD, FDM 3D Printing, LabQuest 3,
        Airflow Measurement
      </p>
    </div>
  </section>

  <div class="section-heading">
    <h2>Research Interests</h2>
    <p>
      My interests connect advanced manufacturing, computational modeling,
      experimentation, and sustainable engineering applications.
    </p>
  </div>

  <section class="interest-grid">
    <div class="interest-item">Additive Manufacturing</div>
    <div class="interest-item">Computational Fluid Dynamics</div>
    <div class="interest-item">Heat Transfer</div>
    <div class="interest-item">Porous Structures</div>
    <div class="interest-item">Design Optimization</div>
    <div class="interest-item">Experimental Research</div>
    <div class="interest-item">Advanced Manufacturing</div>
    <div class="interest-item">Sustainable Engineering</div>
  </section>

  <div class="section-heading">
    <h2>Featured Projects</h2>
    <p>
      Selected research, design, automation, prototyping, and manufacturing
      projects completed during my academic and professional career.
    </p>
  </div>

  <section class="card-grid">

    <article class="info-card">
      <h3>3D-Printed Compost Aeration System</h3>
      <p>
        Design and evaluation of additively manufactured aeration structures
        using nTopology, FDM printing, sensor-based monitoring, and airflow
        measurement.
      </p>
      <a class="card-link" href="/projects/">
        View project →
      </a>
    </article>

    <article class="info-card">
      <h3>Autonomous Path-Finding Cargo Cart</h3>
      <p>
        A mobile engineering system combining mechanical design, electronics,
        sensors, control, navigation, assembly, and performance testing.
      </p>
      <a class="card-link" href="/projects/">
        View project →
      </a>
    </article>

    <article class="info-card">
      <h3>Springback in V-Bending</h3>
      <p>
        Experimental investigation of applied force, holding time, and heat
        treatment effects on springback in aluminum, mild steel, and stainless
        steel.
      </p>
      <a class="card-link" href="/projects/">
        View project →
      </a>
    </article>

    <article class="info-card">
      <h3>Manufacturing Process Improvement</h3>
      <p>
        Industrial improvement projects involving production monitoring,
        bottleneck analysis, line balancing, Kaizen, 5S, and practical
        manufacturing solutions.
      </p>
      <a class="card-link" href="/experience/">
        View experience →
      </a>
    </article>

  </section>

  <section class="highlight-section">
    <h2>Research and Career Goals</h2>

    <p>
      I am seeking engineering opportunities and Ph.D. positions involving
      additive manufacturing, computational modeling, advanced manufacturing,
      design optimization, porous materials, heat transfer, and fluid mechanics.
    </p>

    <div class="hero-buttons">
      <a class="hero-button primary" href="/contact/">Contact Me</a>
      <a class="hero-button" href="/cv/"><a class="hero-button" href="/files/Thouhidul_Islam_Rajon_CV.pdf" target="_blank">

Download CV

</a></a>
    </div>
  </section>

  <div class="footer-note">
    <p>
      © 2026 Thouhidul Islam Rajon · Mechanical Engineering ·
      Research · Design · Manufacturing
    </p>
  </div>

</div>

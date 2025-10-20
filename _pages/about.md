---
permalink: /
title: "# 👋🏼 Hello there, I'm Benjamin!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
  /* Responsive two-column layout for each section */
  .section-flex {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    margin-bottom: 60px;
    flex-wrap: wrap;
  }

  .section-flex img {
    width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .section-text, .section-image {
    flex: 1.3;
    min-width: 280px;
  }

  /* Justify text paragraphs */
  .section-text p {
    text-align: justify;
    line-height: 1.65;
  }

  /* Stack vertically on narrow screens */
  @media (max-width: 900px) {
    .section-flex {
      flex-direction: column;
    }
    .section-text, .section-image {
      width: 100%;
    }
  }

  .caption {
    font-size: 0.9em;
    margin-top: 5px;
    text-align: center;
  }
</style>


<!-- Greeting subtitle -->
<p style="font-size: 1.2em; color: #555; margin-bottom: 20px;">
Astrophysicist | Galaxy Evolution & JWST Enthusiast
</p>


<!-- SECTION 1: About -->
<div class="section-flex">
  <div class="section-text">
    <h2>💡 About</h2>
    <p>
      I am a recent graduate from the master's degree in Astrophysics and Cosmology at the University of Bologna, with a life-long passion for astronomy. Before that, I obtained my undergraduate degree in Technical Physics from the Vienna University of Technology, where I spent five months at Loughborough University (UK) as part of the Erasmus+ programme. I am now looking to continue my research through a PhD, where I hope to further explore the formation and properties of high-redshift galaxies using cutting-edge observational data from JWST, complemented by ground-based observing facilities.
    </p>
  </div>

  <div class="section-image">
    <img src="/images/jwst.png" alt="JWST" style="width: 100%; height: auto; border-radius: 8px;">
    <p class="caption">Image credit: <a href="https://webbtelescope.org/contents/media/images/01GHBYCCMDW24CT0BGH7WXNMS0.html" target="_blank">NASA / JWST</a></em></p>
  </div>
</div>


<!-- SECTION 2: Research -->
<div class="section-flex">
  <div class="section-image">
    <img src="/images/sfms_relative_Leja.png" alt="Sample properties" style="width: 100%; height: auto; border-radius: 8px; margin-bottom: 10px;">
    <p class="caption"><em>Sample properties</em></p>
    <img src="/images/11142.png" alt="Example PROSPECTOR fit" style="width: 100%; height: auto; border-radius: 8px;">
    <p class="caption"><em>Example PROSPECTOR fit</em></p>
  </div>

  <div class="section-text">
    <h2>🔭 Research</h2>
    <p>
      My research interests focus on <strong>observational astrophysics</strong>, particularly <em>high-redshift galaxies</em>, 
      <em>black hole formation</em>, and the <em>evolution of cosmic structure</em>. 
      Currently, I analyse photometric data from the <strong>MIRI instrument onboard JWST</strong>, 
      taken by the PRIMER, COSMOS-Web, and COSMOS-3D surveys in the COSMOS field.
    </p>
    <p>
      In particular, I am focusing on a sample of galaxies between 1.7 < <i>z<i> < 3.5 observed in the BlueJay survey to investigate dust energy balance by comparing existing model spectra to the measured MIRI photometry. Through this exciting project I have gained valuable experience working with astronomical data, building a custom photometric pipeline and working closely with PROSPECTOR.
    </p>
    <p>
      These analyses will contribute to a forthcoming photometric catalogue release that will enable 
      further investigation of dusty, early-universe galaxies observed by JWST.
    </p>
  </div>
</div>

<div class="section-text">
  <h2>📄 For more information</h2>
  <p>
    This page provides an overview of my academic background, research interests, and professional skills. Feel free to browse the dedicated sections of this website for past projects, publications, conferences, and teaching experience.
  </p>
</div>


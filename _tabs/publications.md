---
layout: page
title: Publications
icon: fas fa-file-alt
order: 2
---

<h2>Journal Articles</h2>
<div class="publication-container">
  <div class="publication">
    <h3 class="publication-title">Tissue damage-tracking control system for image-guided photothermal therapy of cancer</h3>
    <p class="publication-authors">Mauricio Céspedes Tenorio, Carlos A. Wattson Sánchez, Diego S. Dumani</p>
    <p class="publication-info">Frontiers in Thermal Engineering, Volume 2, Date: 2022</p>
    <p class="publication-doi">DOI: <a href="https://doi.org/10.3389/fther.2022.1005117">10.3389/fther.2022.1005117</a></p>
    <p class="publication-description">This research explores Photothermal Therapy (PTT) as a promising cancer treatment that uses laser irradiation to damage tumors. PTT faces challenges like collateral damage to healthy tissue and excessive temperature increase in tumors. The study proposes a feedback control system, testing two algorithms (fuzzy logic and PI) via simulations. Both controllers successfully minimize collateral damage while enhancing tumor destruction, demonstrating potential for safer and more effective PTT.</p>
    <div class="publication-image-container">
     <img src="/assets/img/papers/Journal.jpg" alt="Journal Paper" class="publication-image">
    </div>
  </div>
  <!-- Add more publications as needed -->
  <div class="publication">
    <h3 class="publication-title">Magnetic resonance imaging datasets with anatomical fiducials for quality control and registration</h3>
    <p class="publication-authors">Taha, A., Gilmore, G., Abbass, M. et al.</p>
    <p class="publication-info">Scientific Data, Volume 10, Issue 1, Date: 2023</p>
    <p class="publication-doi">DOI: <a href="https://doi.org/10.1038/s41597-023-02330-9">10.1038/s41597-023-02330-9</a></p>
    <p class="publication-description"> This research presents our contribution: the Anatomical Fiducial (AFID) placement protocol for assessing brain correspondence in MRI data. We release meticulously curated AFID placements for widely used datasets, empowering image registration quality control and clinical applications. Our dataset, which involved over 300 hours of human annotation, is highly accurate, with placements falling within 1-2 mm, consistent with prior studies. Moreover, the data is designed for effortless integration into neuroimaging analysis pipelines.</p>
    <div class="publication-image-container">
     <img src="/assets/img/papers/AFIDS.png" alt="AFIDS Paper" class="publication-image">
    </div>
  </div>
</div>

<h2>Conference Proceedings</h2>
<div class="publication-container">
  <div class="publication">
    <h3 class="publication-title">Multivariable Fuzzy Logic Controlled Photothermal Therapy</h3>
    <p class="publication-authors">Mauricio Céspedes Tenorio, Diego S. Dumani</p>
    <p class="publication-info">IFAC-PapersOnLine, Volume 54, Issue 15, Pages 400-405, Date: 2021</p>
    <p class="publication-doi">DOI: <a href="https://doi.org/10.1016/j.ifacol.2021.10.289">10.1016/j.ifacol.2021.10.289</a></p>
    <p class="publication-description">This research explores photothermal therapy for cancer treatment, a non-invasive approach that can complement other treatments. The study introduces a multivariable fuzzy logic controller designed to enhance tumor thermal damage while maintaining safe temperature levels and minimizing harm to nearby healthy tissue. Using three input parameters and thirteen logic rules, the controller adjusts laser power. The results demonstrate the controller's effectiveness in achieving its objectives.</p>
    <div class="publication-image-container">
     <img src="/assets/img/papers/IFAC_img.png" alt="IFAC Paper" class="publication-image">
    </div>
  </div>
  
  <div class="publication">
    <h3 class="publication-title">Modeling thermometry image perturbations during photoacoustic imaging-guided photothermal therapy</h3>
    <p class="publication-authors">Mauricio Céspedes Tenorio, Diego S. Dumani</p>
    <p class="publication-info">2021 IEEE UFFC Latin America Ultrasonics Symposium (LAUS), Pages 1-4, Date: 2021</p>
    <p class="publication-doi">DOI: <a href="https://doi.org/10.1109/LAUS53676.2021.9639142">10.1109/LAUS53676.2021.9639142</a></p>
    <p class="publication-description">This research explores temperature monitoring during hyperthermia treatments using Photoacoustic (PA) imaging. It aims to improve the accuracy of monitoring by modeling and compensating for image perturbations, such as tissue movement and external noise. The study represents the initial steps toward developing a perturbation-compensated photoacoustic thermometry algorithm.</p>
    <div class="publication-image-container">
     <img src="/assets/img/papers/LAUS.png" alt="LAUS" class="publication-image" width="60%" style="display: block; margin: 0 auto;">
    </div>
  </div>

  <!-- Add more publications as needed -->
</div>

<style>
  .publication-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 0 auto;
    max-width: 800px; /* Adjust the maximum width as needed */
  }

  .publication {
    flex: 1;
    width: calc(50% - 20px); /* 50% for two columns with some margin */
    background: #1E1E1E; /* Darker background color */
    color: #FFA500; /* Orange text color */
    border: 2px solid #333333; /* Dark gray border */
    border-radius: 10px;
    margin: 10px;
    padding: 10px;
  }

  .publication-title {
    font-size: 18px;
    margin: 0;
  }

  .publication-authors, .publication-info, .publication-doi {
    font-size: 14px;
    margin: 5px 0;
  }

  .publication-description {
    font-size: 14px;
    margin-top: 10px;
    color: #979797; /* Use a less prominent color for the description */

  }

  .publication-image-container {
    display: flex;
    justify-content: center;
    margin-bottom: 10px;
  }

  .publication-image {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
  }

  .publication-image-1col {
    max-width: 60%;
    height: auto;
    margin-bottom: 10px;
  }
</style>
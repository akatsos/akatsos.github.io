---
layout: single
title: "CV"
classes: wide
permalink: /cv/
author_profile: true
author: work_persona
---


<div class="cv-container">

  <!-- Work Experience -->
  <section class="cv-section">
    <h2>Work Experience</h2>

    <div class="cv-item">
      <div class="cv-header">
        <h3>Orion Lab, National Technical University of Athens</h3>
        <span class="cv-date">Jun. 2024 – Present</span>
      </div>
      <p class="cv-role"><strong>Researcher</strong> | Athens, Greece</p>
      <ul>
        <li><strong>Research Focus:</strong> Domain Adaptation and Multi-Modal Fusion in Deep Learning for Remote Sensing Applications</li>
        <li>Study distribution shifts across different domains and downstream tasks</li>
        <li>Investigation of methods to enhance model robustness across different spatio-temporal domains</li>
      </ul>
    </div>

    <div class="cv-item">
      <div class="cv-header">
        <h3>Beyond EO Center, National Observatory of Athens</h3>
        <span class="cv-date">Jul. 2019 – May 2024</span>
      </div>
      <p class="cv-role"><strong>Technical Team Leader</strong> | Athens, Greece</p>
      <ul>
        <li>
          Technical Team Leader of the Copernicus Sentinel Hubs in Greece. Continuous monitoring of a large infrastructure (&gt;100 VMs, &gt;1PB storage) and root cause analysis of system issues. Implementation of corrective actions and documentation. Coordination of the team for daily activities and task assignments.
          <br><em>Stack: Linux (Debian), Ansible, Python, Bash, PostgreSQL, Solr, Haproxy, TIG Stack, Git</em>
        </li>
        <li>
          Development of a fully automated system for the reception, processing and dissemination of remote sensing data (&gt;5TB each month) from eight polar-orbiting earth-observation satellites.
          <br><em>Stack: Linux (Debian), PostgreSQL, GDAL, Django, Nginx</em>
        </li>
        <li>
          Development of a fully automated system performing diachronic mapping of water bodies in selected river basins using satellite data. The produced digital maps are available freely to the end users.
          <br><em>Stack: Linux (Debian), ESA SNAP, PyTorch, Django, GeoServer, Nginx</em>
        </li>
      </ul>
    </div>
  </section>

  <!-- Education -->
  <section class="cv-section">
    <h2>Education</h2>

    <div class="cv-item">
      <div class="cv-header">
        <h3>National Technical University of Athens, School of Rural, Surveying and Geoinformatics Engineering</h3>
        <span class="cv-date">Present</span>
      </div>
      <p class="cv-role"><strong>PhD Candidate</strong> | Athens, Greece</p>
      <ul>
        <li><strong>Research Focus:</strong> Domain Adaptation and Generalization in Deep Learning for Remote Sensing Applications</li>
      </ul>
    </div>

    <div class="cv-item">
      <div class="cv-header">
        <h3>National Technical University of Athens, School of Rural, Surveying and Geoinformatics Engineering</h3>
        <span class="cv-date">Oct. 2022</span>
      </div>
      <p class="cv-role"><strong>MSc in Geoinformatics</strong> | Athens, Greece</p>
      <ul>
        <li><strong>Thesis:</strong> Automated water detection system using Sentinel-1 satellite data</li>
      </ul>
    </div>

    <div class="cv-item">
      <div class="cv-header">
        <h3>Harokopio University of Athens, School of Digital Technology</h3>
        <span class="cv-date">Jul. 2020</span>
      </div>
      <p class="cv-role"><strong>BSc in Informatics and Telematics</strong> | Athens, Greece</p>
      <ul>
        <li><strong>Thesis:</strong> System Creation for Automated Reception and Process of Automatic Picture Transmission Signals from NOAA POES Satellites and Database Storing for Web-Based View</li>
      </ul>
    </div>
  </section>

  <!-- Certifications, Skills & Interests -->
  <section class="cv-section">
    <h2>Certifications, Skills &amp; Interests</h2>
    <ul>
      <li><strong>Languages:</strong> English – C2 Proficiency (Michigan ECPE), French – A2 (DELF)</li>
    </ul>
  </section>

  <!-- Download CV Button -->
  <div style="margin-bottom: 2rem; text-align: left;">
    <a href="{{ '/assets/docs/Anastasis_Katsos_CV.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="button-4" role="button">Download CV</a>
  </div>

</div>

<style>
    .cv-section {
    margin-bottom: 2.5rem;
    }

    .cv-item {
    margin-bottom: 1.5rem;
    }

    .cv-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    }

    .cv-header h3 {
    margin: 0 0 0.25rem 0;
    font-size: 1.1rem;
    }

    .cv-date {
    font-size: 0.9rem;
    color: #586069;
    white-space: nowrap;
    }

    .cv-role {
    margin: 0 0 0.5rem 0;
    font-size: 0.95rem;
    }

    .button-4 {
    appearance: none;
    background-color: #FAFBFC;
    border: 1px solid rgba(27, 31, 35, 0.15);
    border-radius: 6px;
    box-shadow: rgba(27, 31, 35, 0.04) 0 1px 0, rgba(255, 255, 255, 0.25) 0 1px 0 inset;
    box-sizing: border-box;
    color: #24292E;
    cursor: pointer;
    display: inline-block;
    font-family: -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    font-size: 14px;
    font-weight: 500;
    line-height: 20px;
    list-style: none;
    padding: 6px 16px;
    position: relative;
    transition: background-color 0.2s cubic-bezier(0.3, 0, 0.5, 1);
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;
    vertical-align: middle;
    white-space: nowrap;
    word-wrap: break-word;
    }

    .button-4:hover {
    background-color: #F3F4F6;
    text-decoration: none;
    transition-duration: 0.1s;
    }

    .button-4:disabled {
    background-color: #FAFBFC;
    border-color: rgba(27, 31, 35, 0.15);
    color: #959DA5;
    cursor: default;
    }

    .button-4:active {
    background-color: #EDEFF2;
    box-shadow: rgba(225, 228, 232, 0.2) 0 1px 0 inset;
    transition: none 0s;
    }

    .button-4:focus {
    outline: 1px transparent;
    }

    .button-4:before {
    display: none;
    }

    .button-4:-webkit-details-marker {
    display: none;
    }
</style>
---
layout: archive
title: "Skills & Methodologies"
permalink: /skills/
author_profile: true
---

{% include base_path %}

<style>
  .skills-wrapper { font-family: 'Roboto', sans-serif; letter-spacing: -0.01em; color: #333; }
  
  /* 테크니컬 스킬 그리드 레이아웃 */
  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
    gap: 15px;
    margin-top: 20px;
    margin-bottom: 40px;
  }

  .tech-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 15px;
    border: 1px solid #eee;
    border-radius: 12px;
    background: #fff;
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .tech-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
  }

  .tech-item img {
    width: 40px;
    height: 40px;
    object-fit: contain;
    margin-bottom: 10px;
  }

  .tech-item span {
    font-size: 0.85rem;
    font-weight: 500;
    text-align: center;
  }

  /* 방법론 섹션 스타일 */
  .method-section {
    background: #fcfcfc;
    padding: 25px;
    border-radius: 12px;
    border-left: 5px solid #253A73;
    margin-bottom: 30px;
  }
</style>

<div class="skills-wrapper">

  ## 🛠️ Technical Skills
  기능별 주요 활용 툴 및 언어입니다.

  <div class="tech-grid">
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/arcgis_logo.png" alt="ArcGIS">
      <span>ArcGIS Pro</span>
    </div>
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/python_logo.svg" alt="Python">
      <span>Python</span>
    </div>
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/qgis_logo.png" alt="QGIS">
      <span>QGIS</span>
    </div>
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/r_logo.png" alt="R">
      <span>R Language</span>
    </div>
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/sql_logo.png" alt="SQL">
      <span>SQL / PostGIS</span>
    </div>
    <div class="tech-item">
      <img src="{{ base_path }}/assets/images/envi_logo.png" alt="ENVI">
      <span>ENVI</span>
    </div>
  </div>

  <hr>

  ## 🔬 Methodologies
  연구 수행 시 핵심적으로 활용하는 방법론입니다.

  <div class="method-section">
    <h3 style="margin-top:0; color:#253A73;">Spatio-temporal Analysis</h3>
    <p style="margin-bottom:0; line-height:1.6;">
      Network-based traffic congestion prediction, Time-series hot-spot analysis, and spatial autocorrelation for urban risk detection.
    </p>
  </div>

  <div class="method-section" style="border-left-color: #E84A5F;">
    <h3 style="margin-top:0; color:#E84A5F;">GeoAI & Machine Learning</h3>
    <p style="margin-bottom:0; line-height:1.6;">
      Applying Random Forest, XGBoost, and Deep Learning frameworks to geospatial big data for predictive modeling and classification.
    </p>
  </div>

  <div class="method-section" style="border-left-color: #45B6FE;">
    <h3 style="margin-top:0; color:#45B6FE;">Remote Sensing</h3>
    <p style="margin-bottom:0; line-height:1.6;">
      Satellite image preprocessing, land cover change detection, and multi-spectral data analysis using ENVI and Google Earth Engine.
    </p>
  </div>

</div>

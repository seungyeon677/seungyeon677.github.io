---
layout: archive
title: "Skills & Methodologies"
permalink: /skills/
author_profile: true
---

{% include base_path %}

<style>
  /* 전체 컨테이너 설정 */
  .skills-section {
    color: #333;
    margin-top: 30px;
  }

  /* 기술 그리드 레이아웃 */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
    gap: 20px;
    margin-bottom: 50px;
    margin-top: 20px;
  }

  /* 개별 기술 카드 스타일 */
  .skill-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 15px 10px;
    border: 1px solid #f0f0f0;
    border-radius: 8px;
    background-color: #fff;
    transition: all 0.3s ease;
  }

  .skill-card:hover {
    border-color: #253A73;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    transform: translateY(-3px);
  }

  /* 로고 이미지 설정 */
  .skill-card img {
    width: 45px;
    height: 45px;
    object-fit: contain;
    margin-bottom: 12px;
    /* 이미지에 미세한 회색 필터를 주어 통일감을 높일 수도 있습니다 */
  }

  /* 기술 이름 텍스트 */
  .skill-card span {
    font-size: 0.85rem;
    font-weight: 500;
    color: #444;
    text-align: center;
    line-height: 1.2;
  }

  /* 섹션 구분선 및 제목 */
  .section-title {
    font-size: 1.6rem;
    font-weight: 700;
    color: #253A73;
    margin-bottom: 10px;
    display: inline-block;
    padding-bottom: 5px;
  }

  /* 방법론 텍스트 스타일 */
  .methodology-list {
    list-style: none;
    padding: 0;
  }
  .methodology-item {
    margin-bottom: 15px;
    padding: 15px;
    border-left: 4px solid #eee;
    background: #fcfcfc;
  }
</style>

<div class="skills-section">

  <h2 class="section-title">Technical Skills</h2>
  
  <div class="skills-grid">
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/arcgis_logo.png" alt="ArcGIS">
      <span>ArcGIS Pro</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/python_logo.svg" alt="Python">
      <span>Python</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/qgis_logo.png" alt="QGIS">
      <span>QGIS</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/r_logo.png" alt="R">
      <span>R</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/postgresql_logo.png" alt="PostgreSQL">
      <span>PostgreSQL</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/envi_logo.png" alt="ENVI">
      <span>ENVI</span>
    </div>
    <div class="skill-card">
      <img src="{{ base_path }}/assets/images/gee_logo.png" alt="GEE">
      <span>Google Earth Engine</span>
    </div>
  </div>

  <h2 class="section-title">Methodologies</h2>
  
  <div class="methodology-list">
    <div class="methodology-item">
      <strong>Spatial Data Analysis:</strong>
      <p style="margin: 5px 0 0 0; font-size: 0.95rem; color: #666;">Spatiotemporal modeling, network analysis, and hot-spot detection using various spatial statistics.</p>
    </div>
    <div class="methodology-item">
      <strong>GeoAI & Deep Learning:</strong>
      <p style="margin: 5px 0 0 0; font-size: 0.95rem; color: #666;">Implementing machine learning frameworks (XGBoost, Random Forest) and deep learning for urban risk prediction.</p>
    </div>
  </div>

</div>

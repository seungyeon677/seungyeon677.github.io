---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
  .cv-container { color: #333; margin-top: 20px; }
  
  /* 최상단 다운로드 섹션 */
  .cv-download-banner {
    display: flex; justify-content: space-between; align-items: center;
    padding: 20px; background: #f8f9fa; border-radius: 12px; border: 1px solid #253A73;
    margin-bottom: 30px;
  }
  .cv-download-text h3 { margin: 0; color: #253A73; font-size: 1.1rem; }
  .cv-download-text p { margin: 5px 0 0; font-size: 0.85rem; color: #666; }

  /* 섹션 타이틀 */
  .cv-section-title {
    font-size: 1.4rem; font-weight: 700; color: #253A73;
    border-left: 5px solid #253A73; padding-left: 15px; margin: 40px 0 20px;
  }

  /* 요약 카드 스타일 (기존 탭들과 통일) */
  .cv-summary-card {
    padding: 20px; border: 1px solid #edf0f2; border-radius: 12px;
    background: #fff; box-shadow: 0 4px 10px rgba(0,0,0,0.03); margin-bottom: 15px;
  }
  .cv-item-header { display: flex; justify-content: space-between; margin-bottom: 10px; flex-wrap: wrap; }
  .cv-item-title { font-weight: 700; color: #333; font-size: 1.05rem; }
  .cv-item-date { color: #888; font-size: 0.85rem; }
  .cv-item-sub { color: #253A73; font-size: 0.9rem; font-weight: 500; margin-bottom: 8px; }
  
  .cv-list { margin: 10px 0 0 18px; padding: 0; }
  .cv-list li { font-size: 0.85rem; color: #555; margin-bottom: 5px; line-height: 1.5; }

  /* 모바일 대응 */
  @media (max-width: 600px) {
    .cv-download-banner { flex-direction: column; text-align: center; gap: 15px; }
    .cv-item-header { flex-direction: column; gap: 3px; }
  }
</style>

<div class="cv-container">

  <div class="cv-download-banner">
    <div class="cv-download-text">
      <h3>Full Curriculum Vitae</h3>
      <p>Click the button to download or view the complete PDF version.</p>
    </div>
    <a href="/assets/pdf/CV_Lee_Seungyeon.pdf" class="btn btn--info" target="_blank" style="margin: 0;">
      <i class="fas fa-file-pdf"></i> Download PDF
    </a>
  </div>

  <h2 class="cv-section-title">Research Interests</h2>
  <div class="cv-summary-card">
    <p style="margin: 0; font-size: 0.95rem; line-height: 1.7;">
      • Spatiotemporal Data Analysis & Traffic Prediction<br>
      • Geographic Information Systems (GIS) & Cartography<br>
      • Urban Analytics & GeoAI Frameworks<br>
      • Human Mobility and Public Housing Spatial Mismatch
    </p>
  </div>

  <h2 class="cv-section-title">Selected Publications</h2>
  <div class="cv-summary-card">
    <div class="cv-item-header">
      <span class="cv-item-title">Beyond the Road: A Regional Perspective on Traffic Congestion...</span>
      <span class="cv-item-date">2025</span>
    </div>
    <div class="cv-item-sub">ISPRS International Journal of Geo–Information</div>
    <p style="font-size: 0.85rem; color: #666;">Seong, J. C., <b>Lee, S.</b>, Cho, Y., & Hwang, C. S.</p>
  </div>

  <div class="cv-summary-card">
    <div class="cv-item-header">
      <span class="cv-item-title">Measuring Spatial Associations of Intercity Flows...</span>
      <span class="cv-item-date">2023</span>
    </div>
    <div class="cv-item-sub">Journal of the Korean Geographical Society</div>
    <p style="font-size: 0.85rem; color: #666;">Cho, Y., Seong, J. C., <b>Lee, S.</b>, & Hwang, C. S.</p>
  </div>

  <h2 class="cv-section-title">Professional Experience</h2>
  <div class="cv-summary-card">
    <div class="cv-item-header">
      <span class="cv-item-title">Research Fellowship</span>
      <span class="cv-item-date">2024.06 – 2025.02</span>
    </div>
    <div class="cv-item-sub">University of West Georgia, USA</div>
    <ul class="cv-list">
      <li>Collaborative research on Metro Atlanta traffic congestion prediction.</li>
      <li>Developed GeoAI models using spatiotemporal network data.</li>
    </ul>
  </div>

  <hr style="margin-top: 50px; border: 0.5px solid #eee;">
  <p align="center" style="color: #bbb; font-size: 0.8rem;">Last updated: January 2026</p>

</div>

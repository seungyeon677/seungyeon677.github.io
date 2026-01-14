---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
---

<style>
  .edu-container { color: #333; margin-top: 20px; }
  
  /* 카드형 레이아웃 - News 탭과 통일 */
  .edu-item {
    display: flex; flex-direction: column; margin-bottom: 30px; padding: 25px;
    border: 1px solid #edf0f2; border-radius: 12px; background-color: #ffffff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05); transition: 0.3s;
  }
  .edu-item:hover { transform: translateY(-3px); box-shadow: 0 6px 15px rgba(0,0,0,0.08); }

  /* 로고 영역 */
  .edu-logo-area { 
    width: 120px; height: 120px; margin-bottom: 10px; 
    display: flex; align-items: center; justify-content: center; flex-shrink: 0;
  }
  .edu-logo-area img { max-width: 100%; max-height: 100%; object-fit: contain; }

  /* 텍스트 영역 */
  .edu-content { flex: 1; }
  .edu-degree { 
    font-size: 1.3rem !important; font-weight: 700 !important; color: #253A73 !important; 
    margin: 0 0 8px 0 !important; line-height: 1.2 !important; border-bottom: none !important; 
  }
  .edu-univ { font-size: 1.05rem; font-weight: 600; color: #444; margin-bottom: 3px; }
  .edu-dept { font-size: 0.95rem; color: #666; margin-bottom: 3px; }
  .edu-meta { font-size: 0.85rem; color: #888; margin-bottom: 15px; display: block; }
  
  /* 상세 리스트 */
  .edu-details { margin: 10px 0 0 18px; padding: 0; list-style-type: disc; }
  .edu-details li { font-size: 0.8rem; color: #555; margin-bottom: 6px; line-height: 1.3; }
  .edu-details li strong { color: #333; }
  
  /* 링크 스타일 */
  .edu-link { color: #253A73; text-decoration: none; font-size: 0.8rem; margin-left: 5px; transition: 0.2s; }
  .edu-link:hover { text-decoration: underline; color: #007bff; }

  /* PC 화면 가로 배치 */
  @media (min-width: 768px) {
    .edu-item { flex-direction: row; align-items: center; }
    .edu-logo-area { width: 140px; height: 140px; margin-right: 35px; margin-bottom: 0; }
  }
</style>

<div class="edu-container">

  <div class="edu-item">
    <div class="edu-logo-area">
      <img src="/images/khu_logo.png" alt="Kyung Hee University Logo">
    </div>
    <div class="edu-content">
      <h2 class="edu-degree">M.S. in Geography</h2>
      <div class="edu-univ">Kyung Hee University</div>
      <div class="edu-dept">Department of Geography <br> (Specialized in GIS and Cartography)</div>
      <span class="edu-meta">Mar 2023 – Aug 2025 | Seoul, Republic of Korea</span>
      
      <ul class="edu-details">
        <li>
          <strong>Advisor:</strong> Dr. Chul Sue Hwang 
          <a href="https://gis.khu.ac.kr/" target="_blank" class="edu-link">[🔗 Lab Link]</a>
        </li>
        <li><strong>Thesis:</strong> Spatiotemporal Network–Based Traffic Congestion Prediction Using Grid Data – Case Study of Atlanta, Georgia, USA</li>
      </ul>
    </div>
  </div>

  <div class="edu-item">
    <div class="edu-logo-area">
      <img src="/images/khu_logo.png" alt="Kyung Hee University Logo">
    </div>
    <div class="edu-content">
      <h2 class="edu-degree">B.S. in Geography</h2>
      <div class="edu-univ">Kyung Hee University</div>
      <div class="edu-dept">Department of Geography</div>
      <span class="edu-meta">Mar 2019 – Feb 2023 | Seoul, South Korea</span>
      
      <ul class="edu-details">
        <li>Teacher Certificate of Geography (Secondary School Teacher Grade II), Ministry of Education</li>
      </ul>
    </div>
  </div>

</div>

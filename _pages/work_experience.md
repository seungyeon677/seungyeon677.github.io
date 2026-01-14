---
layout: archive
title: "Work Experience"
permalink: /work_experience/
author_profile: true
---

{% include base_path %}

---
layout: archive
title: "Work Experience"
permalink: /work_experience/
author_profile: true
---

<style>
  .work-container { color: #333; margin-top: 20px; }
  
  /* 카드 스타일 - 타 페이지와 통일 */
  .work-item {
    display: flex; flex-direction: column; margin-bottom: 30px; padding: 25px;
    border: 1px solid #edf0f2; border-radius: 12px; background-color: #ffffff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05); transition: 0.3s;
  }
  .work-item:hover { transform: translateY(-3px); box-shadow: 0 6px 15px rgba(0,0,0,0.08); }

  /* 로고 영역 */
  .work-logo-area { 
    width: 100px; height: 100px; margin-bottom: 20px; 
    display: flex; align-items: center; justify-content: center; flex-shrink: 0;
  }
  .work-logo-area img { max-width: 100%; max-height: 100%; object-fit: contain; }

  /* 텍스트 영역 */
  .work-content { flex: 1; }
  .work-role { 
    font-size: 1.3rem !important; font-weight: 700 !important; color: #253A73 !important; 
    margin: 0 0 8px 0 !important; line-height: 1.2 !important; border-bottom: none !important; 
  }
  .work-org { font-size: 1.05rem; font-weight: 600; color: #444; margin-bottom: 5px; }
  .work-meta { font-size: 0.85rem; color: #888; margin-bottom: 15px; display: block; }
  
  /* 업무 상세 내용 */
  .work-details { margin: 10px 0 0 18px; padding: 0; list-style-type: disc; }
  .work-details li { font-size: 0.85rem; color: #555; margin-bottom: 6px; line-height: 1.3; }
  .work-details li i { color: #666; }

  /* PC 화면 가로 배치 */
  @media (min-width: 768px) {
    .work-item { flex-direction: row; align-items: flex-start; }
    .work-logo-area { width: 120px; height: 100px; margin-right: 30px; margin-bottom: 0; }
  }
</style>

<div class="work-container">

  <div class="work-item">
    <div class="work-logo-area">
      <img src="/images/uwg_logo.svg" alt="UWG Logo">
    </div>
    <div class="work-content">
      <h2 class="work-role">Visiting Researcher</h2>
      <div class="work-org">University of West Georgia</div>
      <span class="work-meta">Jun 2024 – Aug 2025 | Carrollton, GA, USA</span>
      <ul class="work-details">
        <li>Global ICT Professional Training Program (Funded by IITP, Republic of Korea)</li>
        <li>Focused on detecting urban traffic risk areas using spatial big data and GeoAI frameworks</li>
        <li>Published a co-author research paper in the <i>ISPRS International Journal of Geo-Information (IJGI)</i></li>
        <li>Supervisors: Dr. Chul Sue Hwang and Dr. Jeong Chang Seong</li>
      </ul>
    </div>
  </div>

  <div class="work-item">
    <div class="work-logo-area">
      <img src="/images/uwg_logo.svg" alt="UWG Logo">
    </div>
    <div class="work-content">
      <h2 class="work-role">Teaching Assistant</h2>
      <div class="work-org">Kyung Hee University & University of West Georgia</div>
      <span class="work-meta">Jul 2024 | Carrollton, GA, USA</span>
      <ul class="work-details">
        <li>UWG Geospatial Workshop for Kyung Hee University undergraduate students</li>
        <li>Managed a group of international students and served as a teaching assistant</li>
        <li>Provided hands-on assistance with ArcGIS Pro and geospatial data analysis</li>
        <li>Supervisors: Dr. Chul Sue Hwang and Dr. Jeong Chang Seong</li>
      </ul>
    </div>
  </div>

  <div class="work-item">
    <div class="work-logo-area">
      <img src="/images/krila_logo.jpg" alt="KRILA Logo">
    </div>
    <div class="work-content">
      <h2 class="work-role">Research Assistant</h2>
      <div class="work-org">Kyung Hee University & KRILA</div>
      <span class="work-meta">Jun 2022 – Sep 2022 | Seoul, Republic of Korea</span>
      <ul class="work-details">
        <li>Development of Support Strategies for Depopulated Regions in Republic of Korea (Funded by KRILA)</li>
        <li>Analyzed nationwide population decline indicators using road network analysis and large-scale demographic datasets</li>
        <li>Supervisors: Dr. Chul Sue Hwang and Dr. Won Do Lee</li>
      </ul>
    </div>
  </div>

  <div class="work-item">
    <div class="work-logo-area">
      <img src="/images/siipa_logo.png" alt="SIIPA Logo">
    </div>
    <div class="work-content">
      <h2 class="work-role">Office Assistant</h2>
      <div class="work-org">Kyung Hee University & Spatial Information Industry Promotion Agency</div>
      <span class="work-meta">Jul 2022 – Feb 2025 | Seoul, Republic of Korea</span>
      <ul class="work-details">
        <li>Geospatial Information Innovation Cultivation Program (Funded by Spatial Information Industry Promotion Agency)</li>
        <li>Coordinated academic activities for undergraduate students and provided mentoring in GIS applications</li>
        <li>Supervisor: Dr. Chul Sue Hwang</li>
      </ul>
    </div>
  </div>

</div>

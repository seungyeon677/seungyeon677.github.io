---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<style>
  .news-container { color: #333; margin-top: 20px; }
  .news-item {
    display: flex; flex-direction: column; margin-bottom: 40px; padding: 20px;
    border: 1px solid #eee; border-radius: 10px; background-color: #fff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05); transition: 0.2s;
  }
  .news-item:hover { transform: translateY(-5px); box-shadow: 0 8px 20px rgba(0,0,0,0.08); }

  .news-image-area { width: 100%; height: 250px; border-radius: 8px; margin-bottom: 20px; overflow: hidden; background: #f9f9f9; }
  .news-image-area img { width: 100%; height: 100%; object-fit: cover; }

  .swiper-button-next, .swiper-button-prev { color: #fff !important; transform: scale(0.6); }
  .swiper-pagination-bullet-active { background: #fff !important; }

  .news-date { font-size: 0.85rem; color: #888; margin-bottom: 8px; font-weight: 500; }
  .news-title { font-size: 1.2rem !important; font-weight: 700 !important; color: #253A73 !important; margin: 0 0 10px 0 !important; line-height: 1.3 !important; }
  .news-description { font-size: 0.85rem; color: #555; line-height: 1.5; margin-bottom: 0; }
  .news-description b { color: #333; }

  @media (min-width: 768px) {
    .news-item { flex-direction: row; align-items: flex-start; }
    .news-image-area { width: 32%; height: 200px; margin-right: 25px; margin-bottom: 0; flex-shrink: 0; }
    .news-content { flex: 1; }
  }
</style>

<div class="news-container">

  <div class="news-item">
    <div class="news-image-area"><img src="{{ base_path }}/images/graduation_1.jpg" alt="Graduation"></div>
    <div class="news-content">
      <p class="news-date">Aug 20, 2025</p>
      <h2 class="news-title">Successfully Completed M.S. in Geography</h2>
      <p class="news-description">
        I am thrilled to announce my graduation from Kyung Hee University. My thesis focused on <b>"Spatiotemporal Network–Based Traffic Congestion Prediction Using Grid Data,"</b> with a case study on Atlanta, GA.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="swiper newsSwiper news-image-area">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="{{ base_path }}/images/uwg_1.jpg"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/uwg_2.jpg"></div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div><div class="swiper-button-prev"></div>
    </div>
    <div class="news-content">
      <p class="news-date">Jun 2024 – Feb 2025</p>
      <h2 class="news-title">Research Fellowship at the University of West Georgia</h2>
      <p class="news-description">
        Conducted collaborative research at UWG, leading to a publication in the <b>ISPRS International Journal of Geo-Information</b> regarding regional traffic congestion perspectives in Metro Atlanta.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area"><img src="{{ base_path }}/images/kmi_1.jpg"></div>
    <div class="news-content">
      <p class="news-date">May 31, 2024</p>
      <h2 class="news-title">Agent-Based Marine Space Simulation Workshop</h2>
      <p class="news-description">
        Participated in the KMI project workshop. I shared insights on <b>marine spatial planning and zoning</b> utilizing AnyLogic for agent-based simulations.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area"><img src="{{ base_path }}/images/aag_1.jpg"></div>
    <div class="news-content">
      <p class="news-date">Apr 20, 2024</p>
      <h2 class="news-title">Presented at 2024 AAG Annual Meeting</h2>
      <p class="news-description">
        Presented my paper on <b>"Unveiling Spatial Mismatch between Public Rental Housing and Youth’s Activity"</b> at the AAG Annual Meeting in Honolulu, HI.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="swiper newsSwiper news-image-area">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="{{ base_path }}/images/wang_1.jpg"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/wang_2.jpg"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/wang_3.jpg"></div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div><div class="swiper-button-prev"></div>
    </div>
    <div class="news-content">
      <p class="news-date">Jan 05, 2024</p>
      <h2 class="news-title">Special Lecture by Dr. Shaowen Wang</h2>
      <p class="news-description">
        Dr. Shaowen Wang (UIUC) visited KHU for a special lecture on <b>"Harnessing the Geospatial Data Revolution for Sustainability Solutions,"</b> providing great inspiration for our graduate research.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="swiper newsSwiper news-image-area">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="{{ base_path }}/images/krila_1.jpg"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/krila_2.jpg"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/krila_3.jpg"></div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div><div class="swiper-button-prev"></div>
    </div>
    <div class="news-content">
      <p class="news-date">Dec 28, 2023</p>
      <h2 class="news-title">KRILA Workshop on Depopulated Regions</h2>
      <p class="news-description">
        Engaged in discussions regarding <b>living population-based research</b> for depopulated areas. Shared my work on spatial mismatch in public rental housing for youth.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area"><img src="{{ base_path }}/images/kgs_1.jpg"></div>
    <div class="news-content">
      <p class="news-date">Dec 01, 2023</p>
      <h2 class="news-title">Paper Presentation at KGS Conference</h2>
      <p class="news-description">
        Presented research on <b>"Spatial Associations of Intercity Flows between Depopulation Regions"</b> at the Korean Geographical Society Conference.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area"><img src="{{ base_path }}/images/cjk_1.jpg"></div>
    <div class="news-content">
      <p class="news-date">Oct 22, 2023</p>
      <h2 class="news-title">Korea–Japan–China (CJK) Regional Conference</h2>
      <p class="news-description">
        Supported the operational activities for the 2023 CJK Regional Conference, facilitating international academic exchange in the region.
      </p>
    </div>
  </div>

</div>

<script>
  var swiper = new Swiper(".newsSwiper", {
    loop: true,
    pagination: { el: ".swiper-pagination", clickable: true },
    navigation: { nextEl: ".swiper-button-next", prevEl: ".swiper-button-prev" },
  });
</script>

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
    display: flex;
    flex-direction: column;
    margin-bottom: 40px;
    padding: 20px;
    border: 1px solid #eee;
    border-radius: 10px;
    background-color: #fff;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .news-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
  }

  /* 슬라이더 영역 및 일반 이미지 공통 스타일 */
  .news-image-area {
    width: 100%;
    height: 250px; /* 슬라이더와 이미지 높이 통일 */
    border-radius: 8px;
    margin-bottom: 20px;
    overflow: hidden;
  }
  
  .news-image-area img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Swiper 커스텀 스타일 */
  .swiper-button-next, .swiper-button-prev { color: #253A73 !important; transform: scale(0.6); }
  .swiper-pagination-bullet-active { background: #253A73 !important; }

  .news-date {
    font-size: 0.85rem;
    color: #888;
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .news-title {
    font-size: 1.2rem !important;
    font-weight: 700 !important;
    color: #253A73 !important;
    margin: 0 0 10px 0 !important;
    line-height: 1.3 !important;
  }

  .news-description {
    font-size: 0.8rem;
    color: #555;
    line-height: 1.3;
    margin-bottom: 10px;
  }
  
  @media (min-width: 768px) {
    .news-item {
      flex-direction: row;
      align-items: flex-start;
    }
    .news-image-area {
      width: 35%;
      height: 220px; /* PC에서는 약간 낮게 조절 가능 */
      margin-right: 30px;
      margin-bottom: 0;
    }
    .news-content {
      flex: 1;
    }
  }
</style>

<div class="news-container">

  <div class="news-item">
    <div class="swiper newsSwiper news-image-area">
      <div class="swiper-wrapper">
        <div class="swiper-slide"><img src="{{ base_path }}/images/conference_pic.jpg" alt="Slide 1"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/conference_pic2.jpg" alt="Slide 2"></div>
        <div class="swiper-slide"><img src="{{ base_path }}/images/conference_pic3.jpg" alt="Slide 3"></div>
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
    </div>
    <div class="news-content">
      <p class="news-date">Dec 15, 2024</p>
      <h2 class="news-title">Presented at the International GIS Conference</h2>
      <p class="news-description">
        My research on "Spatio-temporal Traffic Prediction" was presented at the IGSC 2024. It was a great opportunity to share insights and connect with other researchers in the field. (Swipe to see more photos)
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area">
      <img src="{{ base_path }}/images/graduation_pic.jpg" alt="Graduation">
    </div>
    <div class="news-content">
      <p class="news-date">Feb 20, 2025</p>
      <h2 class="news-title">Successfully Completed M.S. in Geography</h2>
      <p class="news-description">
        I am thrilled to announce that I have successfully completed my Master's degree at Kyung Hee University. Special thanks to my advisor and lab members for their unwavering support.
      </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image-area">
      <img src="{{ base_path }}/images/workshop_pic.jpg" alt="Workshop Participation">
    </div>
    <div class="news-content">
      <p class="news-date">Jan 10, 2024</p>
      <h2 class="news-title">Participated in GeoAI Workshop at UWG</h2>
      <p class="news-description">
        Attended an intensive workshop on GeoAI frameworks and deep learning for urban analytics at the University of West Georgia, enhancing my practical skills.
      </p>
    </div>
  </div>

</div>

<script>
  var swiper = new Swiper(".newsSwiper", {
    loop: true,
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
  });
</script>

---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

<style>
  .news-container { color: #333; margin-top: 20px; }
  .news-item {
    display: flex;
    flex-direction: column; /* 이미지/날짜-제목/내용 순서로 배치 */
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

  .news-image {
    width: 100%; /* 이미지를 카드 너비에 꽉 채움 */
    max-height: 250px; /* 너무 길어지지 않게 최대 높이 제한 */
    object-fit: cover; /* 이미지가 잘리지 않고 채워지도록 */
    border-radius: 8px;
    margin-bottom: 20px;
  }

  .news-date {
    font-size: 0.85rem;
    color: #888;
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .news-title {
    font-size: 1.0rem;
    font-weight: 700;
    color: #253A73;
    margin: 0 0 10px 0;
    line-height: 1.3;
  }

  .news-description {
    font-size: 0.8rem;
    color: #555;
    line-height: 1.3;
    margin-bottom: 10px;
  }
  
  /* 반응형 조정 */
  @media (min-width: 768px) {
    .news-item {
      flex-direction: row; /* 넓은 화면에서는 이미지-내용 가로 배치 */
      align-items: flex-start;
    }
    .news-image {
      width: 35%; /* 넓은 화면에서는 이미지 너비 제한 */
      max-height: none; /* 높이 제한 해제 */
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
    <img src="{{ base_path }}/assets/images/conference_pic.jpg" alt="Conference Presentation" class="news-image">
    <div class="news-content">
      <p class="news-date">Dec 15, 2024</p>
      <h2 style="font-size: 1.0rem; font-weight: 700; color: #253A73; margin: 0 0 10px 0; line-height: 1.3;">Presented at the International GIS Conference</h2>
      <p class="news-description">
        My research on "Spatio-temporal Traffic Prediction" was presented at the IGSC 2024. It was a great opportunity to share insights and connect with other researchers in the field.
      </p>
    </div>
  </div>

  <div class="news-item">
    <img src="{{ base_path }}/assets/images/graduation_pic.jpg" alt="Graduation" class="news-image">
    <div class="news-content">
      <p class="news-date">Feb 20, 2025</p>
      <h2 class="news-title">Successfully Completed M.S. in Geography</h2>
      <p class="news-description">
        I am thrilled to announce that I have successfully completed my Master's degree at Kyung Hee University. Special thanks to my advisor and lab members for their unwavering support.
      </p>
    </div>
  </div>

  <div class="news-item">
    <img src="{{ base_path }}/assets/images/workshop_pic.jpg" alt="Workshop Participation" class="news-image">
    <div class="news-content">
      <p class="news-date">Jan 10, 2024</p>
      <h2 class="news-title">Participated in GeoAI Workshop at UWG</h2>
      <p class="news-description">
        Attended an intensive workshop on GeoAI frameworks and deep learning for urban analytics at the University of West Georgia, enhancing my practical skills.
      </p>
    </div>
  </div>

</div>

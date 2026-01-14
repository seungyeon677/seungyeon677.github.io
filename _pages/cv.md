---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
  .cv-wrapper { margin-top: 20px; font-family: 'Roboto', sans-serif; }

  /* 상단 헤더 섹션 */
  .cv-header-card {
    display: flex; justify-content: space-between; align-items: center;
    padding: 25px; background: #ffffff; border: 1px solid #edf0f2;
    border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    margin-bottom: 30px; border-left: 6px solid #253A73;
  }
  .cv-info h3 { margin: 0; color: #253A73; font-size: 1.2rem; }
  .cv-info p { margin: 5px 0 0; color: #888; font-size: 0.85rem; }

  /* PDF 뷰어 컨테이너 */
  .pdf-container {
    position: relative; width: 100%; border-radius: 12px;
    overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    border: 1px solid #eee; background: #f8f9fa;
  }
  
  /* 모바일용 버튼 디자인 변경: 화이트 버전 */
  .mobile-expand-btn {
    display: none; 
    width: 100%; 
    padding: 14px; 
    background: #ffffff;      /* 배경 하얀색 */
    color: #253A73;           /* 텍스트 다크 블루 */
    text-align: center; 
    text-decoration: none;
    font-weight: 600; 
    border-radius: 10px; 
    margin-bottom: 15px;      /* 위치를 뷰어 위로 조정 */
    border: 1px solid #253A73; /* 테두리 포인트 */
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    transition: 0.2s;
  }
  .mobile-expand-btn:hover {
    background: #f1f4f9;
  }

  /* 반응형 처리 */
  @media (max-width: 768px) {
    .cv-header-card { flex-direction: column; text-align: center; gap: 20px; }
    .pdf-container { height: 550px; }
    .mobile-expand-btn { display: block; } /* 모바일에서 노출 */
  }
</style>

<div class="cv-wrapper">

  <div class="cv-header-card">
    <div class="cv-info">
      <h3>Full Curriculum Vitae</h3>
      <p><i class="fas fa-sync-alt"></i> Last updated: January 2026</p>
    </div>
    <div class="cv-actions">
      <a href="/assets/pdf/CV_Lee_Seungyeon.pdf" class="btn btn--info" target="_blank" style="margin: 0;">
        <i class="fas fa-download"></i> Download PDF
      </a>
    </div>
  </div>

  <a href="/assets/pdf/CV_Lee_Seungyeon.pdf" class="mobile-expand-btn" target="_blank">
    <i class="fas fa-expand-arrows-alt"></i> Open Full Screen PDF
  </a>

  <div class="pdf-container">
    <iframe 
      src="/assets/pdf/CV_Lee_Seungyeon.pdf#toolbar=0&navpanes=0&scrollbar=0" 
      width="100%" 
      height="1000px" 
      style="border: none;">
    </iframe>
  </div>

</div>

<p style="text-align: center; color: #bbb; font-size: 0.8rem; margin-top: 30px;">
  If the PDF does not display correctly, please use the download button above.
</p>

---
layout: archive
title: "Skills & Methodologies"
permalink: /skills/
author_profile: true
---

{% include base_path %}

<style>
  .skills-wrapper { letter-spacing: -0.01em; color: #333; }
  .section-title { font-size: 1.5rem; font-weight: 700; color: #253A73; margin: 30px 0 15px; display: inline-block; }
  
  /* Grid for Technical Skills */
  .tech-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(130px, 1fr)); gap: 15px; margin-bottom: 40px; }
  .tech-card { display: flex; flex-direction: column; align-items: center; padding: 15px; border: 1px solid #f0f0f0; border-radius: 8px; background: #fff; transition: 0.3s; }
  .tech-card:hover { border-color: #253A73; transform: translateY(-3px); box-shadow: 0 4px 10px rgba(0,0,0,0.05); }
  .tech-card img { width: 40px; height: 40px; object-fit: contain; margin-bottom: 10px; }
  .tech-card .name { font-size: 0.85rem; font-weight: 600; text-align: center; }
  .tech-card .level { font-size: 0.75rem; color: #888; margin-top: 2px; }

  /* Methodology List Style */
  .method-container { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .method-box { background: #fcfcfc; padding: 18px; border-radius: 8px; border-left: 4px solid #eee; }
  .method-box h3 { font-size: 1.1rem; margin: 0 0 10px 0; color: #253A73; }
  .method-box ul { margin: 0; padding-left: 18px; font-size: 0.85rem; line-height: 1.5; }
  .method-box li { margin-bottom: 5px; }
</style>

<div class="skills-wrapper">
  <h2 class="section-title">Technical Skills</h2>
  
  <div class="tech-grid">
    <div class="tech-card"><img src="{{base_path}}/images/python_logo.png"> <span class="name">Python</span> <span class="level">Advanced</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/arcpro_logo.png"> <span class="name">ArcGIS Pro</span> <span class="level">Advanced</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/qgis_logo.png"> <span class="name">QGIS</span> <span class="level">Advanced</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/pix4d_logo.svg"> <span class="name">Pix4D Mapper</span> <span class="level">Advanced</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/R_logo.png"> <span class="name">R</span> <span class="level">Intermediate</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/pytorch_logo.svg"> <span class="name">PyTorch</span> <span class="level">Intermediate</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/erdas_logo.png"> <span class="name">ERDAS Imagine</span> <span class="level">Intermediate</span> </div>
    <div class="tech-card"><img src="{{base_path}}/images/anylogic_logo.png"> <span class="name">AnyLogic</span> <span class="level">Intermediate</span> </div>
  </div>

  <h2 class="section-title">Research Methodologies</h2>
  <div class="method-container">
    <div class="method-box">
      <h3>Spatial Statistics</h3>
      <ul>
        <li>Spatial Autocorrelation (Moran’s I / LISA)</li>
        <li>Spatial Clustering (Getis-Ord Gi*)</li>
        <li>Spatial Flow Assosiation (SFlowLISA / BiFlowLISA)</li>
        <li>Spatio-Temporal Clustering (Space Time Cube / Emerging Hot Spot)</li>
        <li>Spatial Regression (GWR / MGWR)</li>
        <li>Mann-Kendall Test</li>
      </ul>
    </div>
    <div class="method-box" style="border-left-color: #253A73;">
      <h3>Spatial Analysis</h3>
      <ul>
        <li>Road Network Analysis (Dijkstra’s)</li>
        <li>Service Area Analysis</li>
        <li>Accessibility (2SFCA / E2SFCA)</li>
        <li>Agent-based Modeling</li>
      </ul>
    </div>
    <div class="method-box" style="grid-column: span 2; border-left-color: #9D1C20;">
      <h3>GeoAI & Machine Learning</h3>
      <ul>
        <li>GNN-based frameworks (GCN, TGCN, STGCN, GC-LSTM)</li>
        <li>LSTM / Random Forest / XGBoost</li>
      </ul>
    </div>
  </div>
</div>

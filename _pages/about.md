---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div class="profile-container" style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div class="profile-content" style="flex: 1;">
    <h1 style="margin-top: 0;">Shengjia Hua</h1>
    <p style="font-size: 1.2em; color: #555; margin-bottom: 15px;">Computer Science Undergraduate | AI & Legal NLP Researcher</p>
    <p>Undergraduate student at Xiamen University, focusing on large language models, legal AI, and model optimization. Currently working on legal domain LLMs, model quantization, and diffusion policy acceleration with research groups from Xiamen University and Tsinghua University.</p>
<div style="margin-top: 20px;">
  <h3 style="margin-bottom: 10px;">Contact Information</h3>
  <ul style="list-style-type: none; padding-left: 0; margin-top: 0;">
    <li style="margin-bottom: 5px;">📧 <strong>Email:</strong>  huashengjia@stu.xmu.edu.cn</li>
    <li>💬 <strong>WeChat:</strong> Esther0095</li>
  </ul>
</div>
<!--     <div style="margin-top: 20px;">
      <h3 style="margin-bottom: 10px;">Contact Information</h3>
      <ul style="list-style-type: none; padding-left: 0; margin-top: 0;">
        <li style="margin-bottom: 5px;">📧 <strong>Email:</strong> huashengjia@stu.xmu.edu.cn</li>
        <li>📱 <strong>Phone:</strong> +86 15359231563</li>
      </ul>
    </div>
  </div> -->
  <div class="profile-image" style="flex: 0 0 200px; margin-left: 40px;">
    <!-- Profile photo placeholder -->
    <!-- <img src="images/profile.jpg" alt="Shengjia Hua" style="width: 100%; border-radius: 50%; border: 3px solid #0066cc;"> -->
  </div>
</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='education'></span>
## 🎓 Education

<div class="education-container">
  <div class="education-item" style="display: flex; margin-bottom: 30px; border-left: 4px solid #0066cc; padding-left: 15px;">
    <div style="flex: 1; margin-right: 20px;">
      <p style="font-weight: bold; color: #0066cc;">Sep 2022 - Present</p>
      <!-- <img src="images/XMUlogo.png" alt="XMU Logo" style="max-width: 80px; margin-top: 10px;"> -->
    </div>
    <div style="flex: 3;">
      <h3 style="margin-top: 0;">Xiamen University</h3>
      <p><strong>School of Informatics</strong> - B.Eng. in Computer Science and Technology</p>
      <ul style="list-style-type: none; padding-left: 0;">
        <li>📊 <strong>Overall GPA:</strong> 3.84/4.0 (Top 5%)</li>
        <li>🏆 <strong>Major Ranking:</strong> 6/124</li>
        <li>🌐 <strong>English Proficiency:</strong> CET-4 613, CET-6 599</li>
        <li>📚 <strong>Core Courses:</strong> Calculus II (100), Linear Algebra (99), Computer Graphics (99), Probability & Statistics (98), Convex Optimization (97), Digital Image Processing (96), Data Structures (95)</li>
      </ul>
    </div>
  </div>
</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='research-experience'></span>
## 🔬 Research Experience

<div class="research-container">
  <!-- Current Research 1 -->
  <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <span style="position: absolute; top: 15px; right: 15px; background-color: #ff6b6b; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Current Research</span>
      <h3>Legal Domain Large Language Model Development</h3>
      <p style="color: #666;"><strong>Sep 2024 - Present | MAC Lab, Xiamen University (Prof. Hui Li)</strong></p>
      <div style="margin-top: 15px;">
        <ul style="padding-left: 20px; margin-top: 0;">
          <li>Core member in developing legal domain large language models with LoRA fine-tuning techniques</li>
          <li>Built multiple RAG frameworks and evaluation mechanisms for legal AI applications</li>
          <li>Deeply involved in algorithm design and experimental work for "Merging Legal Trees and Graph Networks for Efficient Case Retrieval and Judgment Prediction"</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Current Research 2 -->
  <div class="research-item" style="margin-bottom: 30px; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <div style="background-color: #f8f9fa; padding: 20px; position: relative;">
      <span style="position: absolute; top: 15px; right: 15px; background-color: #4dabf7; color: white; padding: 5px 10px; border-radius: 15px; font-size: 0.8em;">Leading Project</span>
      <h3>Model Lightweight & Acceleration Research</h3>
      <p style="color: #666;"><strong>Feb 2025 - Present | Tsinghua Shenzhen Int'l Graduate School (Prof. Zhi Wang)</strong></p>
      <div style="margin-top: 15px;">
        <ul style="padding-left: 20px; margin-top: 0;">
          <li><strong>Principal Investigator</strong> of Tsinghua-Lenovo dNPU general model inference acceleration project (expecting first-author CCFA paper)</li>
          <li>Developed 2-4-8 mixed-precision quantization CUDA operators for SliM-LLM open-source project</li>
          <li>Built mixed-precision quantization framework and Triton operators for AutoAWQ open-source project</li>
          <li>Co-authored "Block-wise Adaptive Caching for Accelerating Diffusion Policy" (submitted to NIPS 2025)</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='publications'></span>
## 📝 Publications & Manuscripts

<div class="publications-container">
  <div class="publication-item" style="padding: 20px; margin-bottom: 20px; border-left: 4px solid #ff6b6b; background-color: #f8f9fa; border-radius: 0 4px 4px 0; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h4 style="margin-top: 0;">Block-wise Adaptive Caching for Accelerating Diffusion Policy</h4>
    <p style="margin-bottom: 10px;"><em>Under review at NIPS 2025</em></p>
    <p style="font-size: 0.9em; color: #666;">Proposed the first training-free acceleration method for action diffusion generation policies. Through adaptive caching scheduling and bubble joint algorithms, effectively truncated cross-block error propagation in FFN, achieving up to 3× inference acceleration with no performance loss across multiple robotic tasks.</p>
  </div>

  <div class="publication-item" style="padding: 20px; margin-bottom: 20px; border-left: 4px solid #4dabf7; background-color: #f8f9fa; border-radius: 0 4px 4px 0; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h4 style="margin-top: 0;">Group-wise Mixed-Precision Quantization for Large Language Models</h4>
    <p style="margin-bottom: 10px;"><em>Prepared for AAAI 2026</em> | <strong>First Author</strong></p>
    <p style="font-size: 0.9em; color: #666;">Proposed Group-wise mixed quantization algorithm for LLM quantization. Adopted multiple saliency measures to reduce errors, integrable with both VQ and non-VQ quantization frameworks. Achieved 15% performance improvement and 2-3× speed enhancement compared to SLIM-LLM baseline.</p>
  </div>

  <div class="publication-item" style="padding: 20px; margin-bottom: 20px; border-left: 4px solid #51cf66; background-color: #f8f9fa; border-radius: 0 4px 4px 0; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
    <h4 style="margin-top: 0;">Merging Legal Trees and Graph Networks for Efficient Case Retrieval and Judgment Prediction</h4>
    <p style="margin-bottom: 10px;"><em>Prepared for ICDE 2026</em></p>
    <p style="font-size: 0.9em; color: #666;">Proposed retrieval framework combining "Legal Trees" construction with Graph Neural Networks (GNN) for legal case retrieval. Utilized "Dynamic Selector" to continuously identify important legal nodes related to cases, simulating human reasoning processes. Achieved 15% improvement across multiple legal datasets.</p>
  </div>
</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='awards-honors'></span>
## 🏆 Awards & Honors

<div class="awards-container" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-bottom: 30px;">
  <div class="awards-card" style="background-color: #f8f9fa; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%;">
    <h4 style="color: #0066cc; margin-top: 0; border-bottom: 2px solid #0066cc; padding-bottom: 10px;">Competition Awards</h4>
    <ul style="padding-left: 20px;">
      <li><strong>Provincial First Prize</strong> - Blue Bridge Cup National Software and IT Professional Talent Competition (C/C++ Group) <em>(Apr 2024)</em></li>
      <li><strong>Provincial First Prize</strong> - National College Student Mathematical Modeling Contest <em>(Dec 2024)</em></li>
    </ul>
  </div>
  
  <div class="awards-card" style="background-color: #f8f9fa; border-radius: 8px; padding: 20px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); height: 100%;">
    <h4 style="color: #0066cc; margin-top: 0; border-bottom: 2px solid #0066cc; padding-bottom: 10px;">Scholarships & Honors</h4>
    <ul style="padding-left: 20px;">
      <li>Outstanding Academic Scholarship (Multiple Years)</li>
      <li>Academic Innovation Scholarship</li>
      <li>China Construction Bank Scholarship</li>
      <li>Outstanding Student Award</li>
    </ul>
  </div>
</div>

<div class="section-divider" style="border-top: 2px solid #eaeaea; margin: 30px 0;"></div>

<span class='anchor' id='skills'></span>
## 💻 Technical Skills

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-bottom: 30px;">
  <div style="background-color: #f8f9fa; border-radius: 8px; padding: 20px;">
    <h4 style="color: #0066cc; margin-top: 0;">Programming Languages</h4>
    <p>Python, C++, CUDA, Triton</p>
  </div>
  
  <div style="background-color: #f8f9fa; border-radius: 8px; padding: 20px;">
    <h4 style="color: #0066cc; margin-top: 0;">AI/ML Frameworks</h4>
    <p>PyTorch, TensorFlow, Transformers, AutoAWQ, SliM-LLM</p>
  </div>
  
  <div style="background-color: #f8f9fa; border-radius: 8px; padding: 20px;">
    <h4 style="color: #0066cc; margin-top: 0;">Research Areas</h4>
    <p>Large Language Models, Model Quantization, Legal AI, RAG Systems, Diffusion Models</p>
  </div>
</div>

<div style="text-align: center; margin-top: 40px; margin-bottom: 30px; padding: 20px; background-color: #f8f9fa; border-radius: 8px;">
  <p style="margin-bottom: 0; color: #666;">
    Last updated: May 2025 | 
    <!-- <a href="#" style="color: #0066cc; text-decoration: none; font-weight: bold;">Download CV</a> -->
  </p>
  <p style="margin-top: 10px; color: #999; font-size: 0.9em;">
    🌟 Open to research collaborations and internship opportunities in AI/ML
  </p>
</div>

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

Hi! I’m Kaizhen Tan (谭楷蓁). I am currently a master’s student in Artificial Intelligence at **Carnegie Mellon University**. I received my bachelor’s degree in Information Systems from **Tongji University**, where I built a solid foundation in programming, data analysis, and machine learning, complemented by interdisciplinary training in business and organizational systems.

My research sits at the intersection of **Urban Management and Spatial Intelligence**. I aim to build systems that are both **spatially intelligent and socially aware**, providing computational solutions to make cities more adaptive, inclusive, and human-centric.

Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, my work is structured around four interdisciplinary pillars:

<div class="research-container" style="margin-top: 20px;">

  <div style="margin-bottom: 25px;">
    <h4 style="margin-bottom: 8px;">🤖 Embodied Urbanism & Collaborative Governance</h4>
    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;"><i>Core Question: How do we manage and design urban spaces for human-machine co-habitation?</i></p>
    <ul style="margin-top: 0; font-size: 0.95em;">
      <li><b>Robot-Friendly Urban Space:</b> Optimizing infrastructure siting and redesigning streetscapes/building interiors (e.g., domestic service workflows) to redefine human-machine interaction boundaries and liability.</li>
      <li><b>Visual Embodied Navigation:</b> Developing navigation models (UrbanNav) for real-world scenarios, focusing on barrier-free facilities for the disabled and diverse platforms like drones and UGVs.</li>
      <li><b>Low-Altitude Economy & Order:</b> Mining operational flight routes from logistics demand and traffic flow, validated against digital twins under noise, privacy, and "urban canyon" constraints.</li>
      <li><b>Deployment Pathways for Emerging Devices:</b> Analyzing practical barriers for integrating <b>robots, low-altitude systems, BCI, and next-gen wearables</b> into urban services, while studying social acceptance across different demographics.</li>
    </ul>
  </div>

  <div style="margin-bottom: 25px;">
    <h4 style="margin-bottom: 8px;">🏙️ Self-Evolving Urban Digital Twins</h4>
    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;"><i>Core Question: How to maintain a high-fidelity, self-updating digital environment for agent-based urban governance?</i></p>
    <ul style="margin-top: 0; font-size: 0.95em;">
      <li><b>Multimodal Urban Foundation Models:</b> Fusing remote sensing, street view, trajectory, and IoT data to align spatial relations and POI semantics into unified <b>Geo-embeddings</b> for long-term agent memory.</li>
      <li><b>Dynamic Sensing & Measurement:</b> Utilizing embodied agents as mobile sensors to create a closed loop of data collection and feedback (e.g., automated sidewalk width measurement via street-view point clouds/VGGT).</li>
      <li><b>Policy Execution Sandbox:</b> Using Digital Twins as a controlled environment for spatial RAG, policy simulation, risk assessment, and mission planning (e.g., transit assistants and policy Q&A).</li>
      <li><b>Semantic Mapping & Localization:</b> Advancing Geo-localization and semantic SLAM (3DGS, Mesh, Point Cloud) to build interactive and searchable 3D urban environments.</li>
    </ul>
  </div>

  <div style="margin-bottom: 25px;">
    <h4 style="margin-bottom: 8px;">🎨 Urban Perception & Socio-Cultural Analytics</h4>
    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;"><i>Core Question: How do cultural narratives and human behavior inform smarter urban regeneration?</i></p>
    <ul style="margin-top: 0; font-size: 0.95em;">
      <li><b>AI-Enhanced Geospatial Analysis:</b> Studying how urban planning and environments shape human behavior (e.g., GIS-based analysis of lost-and-found patterns in subways).</li>
      <li><b>Urban Imagery & Aesthetics:</b> Quantifying visual aesthetics and "Sense of Place" using AI to inform urban design and historic quarter regeneration.</li>
      <li><b>Socio-Cultural LLMs:</b> Integrating local dialects, indigenous culture, and city narratives into models to foster more empathetic and localized smart city management.</li>
    </ul>
  </div>

  <div style="margin-bottom: 25px;">
    <h4 style="margin-bottom: 8px;">🚀 Spatial Intelligence & Foundation World Models</h4>
    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;"><i>Core Question: How to build reliable, interpretable, and self-evolving world models for physical agents?</i></p>
    <ul style="margin-top: 0; font-size: 0.95em;">
      <li><b>World Model Architectures:</b> Exploring forms of world models including JEPA (perception-prediction), generative video (Genie), and 3DGS-based reconstruction; developing novel 3D encoders to break the limitations of standard Transformers.</li>
      <li><b>3D-Enhanced Spatial Reasoning:</b> Leveraging 3D priors (reconstruction, camera poses, depth) to improve the stability and interpretability of VLM spatial understanding.</li>
      <li><b>Continuous Self-Evolution:</b> Investigating long-term memory mechanisms (e.g., improving CambrianS) and "infinite continuous learning" to ensure stable autonomous growth and safety-constrained adaptation for physical agents.</li>
      <li><b>Unified Representations:</b> Integrating geometry, semantics, and physical interaction (including tactile sensing) into a unified multimodal action representation.</li>
    </ul>
  </div>

</div>

<div style="text-align: center;">
  <a href="/assets/CV_Kaizhen TAN.pdf">View My CV</a> /
  <a href="mailto:wflps20140311@gmail.com">Email</a> /
  <a href="https://github.com/tantansir">Github</a> /
  <a href="/images/Wechat.jpg">Wechat</a> /
  <a href="https://www.linkedin.com/in/kaizhen-tan-b020232b3/">LinkedIn</a>
</div>

# 🔥 News

- *2026.01*: 🎉 The abstract co-authored with Prof. Fan Zhang has been accepted for the [XXV ISPRS Congress 2026](https://www.isprs2026toronto.com/). See you in Toronto!
- *2025.12*: 🎉 Our paper, led by my senior labmate Dr. Weihua Huan and co-authored with Prof. Wei Huang at Tongji University, was accepted by GIScience & Remote Sensing; honored to contribute as second author and big congratulations to Dr. Huan!
- *2025.10*: 🔭 Joined [Prof. Yu Liu](https://scholar.google.com/citations?user=Xh_lRY4AAAAJ) and [Prof. Fan Zhang](https://scholar.google.com/citations?user=dc1TzLoAAAAJ)’s team at Peking University as a remote research assistant.
- *2025.08*: 🎉 Delivered an oral presentation at Hong Kong Polytechnic University after our paper was accepted to the Global Smart Cities Summit cum The 4th International Conference on Urban Informatics [(GSCS & ICUI 2025)](https://www.isocui.org/icui2025).
- *2025.07*: 🎉 My undergraduate thesis was accepted by 7th Asia Conference on Machine Learning and Computing [(ACMLC 2025)](https://www.acmlc.org/acmlc2025.html).
- *2025.06*: 🎓 Graduated from Tongji University—grateful for the journey and excited to continue my studies at CMU.
- *2025.04*: 🔭 Completed the SITP project under the supervision of [Prof. Yujia Zhai](https://www.researchgate.net/profile/Yujia-Zhai-15) in the College of Architecture and Urban Planning.
- *2025.01*: 💼 Joined Shanghai Artificial Intelligence Laboratory as an AI Product Manager Intern.
- *2024.09*: 🌏 Conducted research at ASTAR in Singapore under the supervision of [Dr. Yicheng Zhang](https://zinczhang.github.io/) and [Dr. Sheng Zhang](https://ieeexplore.ieee.org/author/37086165610).
- *2024.04*: 🔭 Began my academic journey at [Prof. Wei Huang](https://huangweibuct.github.io/weihuang.github.io/)’s lab in the College of Surveying and Geo-Informatics, Tongji University.

# 📖 Education

<div class="edu-item">
  <img class="edu-logo" src="/assets/cmu.png" alt="CMU" />
  <div class="edu-content">
    <div class="edu-top">
      <strong>Carnegie Mellon University</strong>
    </div>
    <div class="edu-sub"><em>2025.08 – 2026.08</em></div>
    <div class="edu-sub"><em>M.S. in Artificial Intelligence Systems Management</em></div>
  </div>
</div>

<div class="edu-item">
  <img class="edu-logo" src="/assets/tongji.svg" alt="Tongji" />
  <div class="edu-content">
    <div class="edu-top">
      <strong>Tongji University</strong>
    </div>
    <div class="edu-sub"><em>2021.09 – 2025.06</em></div>
    <div class="edu-sub"><em>B.Mgt. in Information Management and Information System</em></div>
  </div>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">XXV ISPRS Congress</div><img src='images/5.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UrbanVGGT: Scalable Sidewalk Width Estimation from Street View Images**

**Kaizhen Tan**, Fan Zhang

[[abstract]](/assets/isprs_abstract_kaizhen_fan.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Accepted at *[XXV ISPRS Congress 2026](https://www.isprs2026toronto.com/)*
- Leverage street-view imagery and VGGT-based 3D reconstruction to estimate metrically scaled sidewalk widths, build the SV-SideWidth dataset, and fill OpenStreetMap gaps for equitable assessment of pedestrian infrastructure. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computational Urban Science</div><img src='images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Decoding Tourist Perception in Historic Urban Quarters with Multimodal Social Media Data: An AI-Based Framework and Evidence from Shanghai**

**Kaizhen Tan**, Yufan Wu, Yuxuan Liu, Haoran Zeng

[[arXiv]](https://arxiv.org/abs/2509.03830) [[slides]](/assets/ICUI2025.pptx)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Under Review at *Computational Urban Science*
- Developed an AI-powered multimodal framework to analyze tourist perception in historic Shanghai quarters, integrating image segmentation, color theme analysis, and sentiment mining for heritage-informed urban planning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMLC 2025</div><img src='images/21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multimodal Deep Learning for Modeling Air Traffic Controllers Command Lifecycle and Workload Prediction in Terminal Airspace**

**Kaizhen Tan**

[[arXiv]](https://arxiv.org/abs/2509.10522)[[slides]](/assets/ACMLC2025.pptx) [[github]](https://github.com/tantansir/Multimodal-Deep-Learning-for-Modeling-ATCO-Command-Lifecycle-in-Terminal-Airspace)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Published in *7th Asia Conference on Machine Learning and Computing [(ACMLC 2025)](https://www.acmlc.org/acmlc2025.html)*
- Designed a multimodal deep learning framework linking ATCO voice commands with aircraft trajectories to model workload dynamics, enabling intelligent command generation and scheduling support.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GIScience & Remote Sensing</div><img src='images/4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Spatiotemporal Adaptive Local Search Method for Tracking Congestion Propagation in Dynamic Networks**

Weihua Huan, **Kaizhen Tan**, Xintao Liu, Shoujun Jia, Shijun Lu, Jing Zhang, Wei Huang

[[paper]](https://doi.org/10.1080/15481603.2025.2602215)
- Published in *GIScience & Remote Sensing* (JCR Q1; IF = 6.9).
- Proposed a spatiotemporal adaptive local search (STALS) method combining dynamic graph learning and spatial analytics to model and mitigate large-scale urban traffic congestion propagation.
</div>
</div>

# 🔬 Projects

<div class='paper-box'><div class='paper-box-image'><div><img src='images/blindnav.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**BlindNav: YOLO+LLM for Real-Time Navigation Assistance for Blind Users**

**Kaizhen Tan**, Yufan Wang, Yixiao Li, Hanzhe Hong, Nicole Lyu

[[report]](/assets/blindnav.pdf) [[github]](https://github.com/tantansir/BlindNav)
- BlindNav is a real-time, camera-based navigation assistant that uses YOLO for street-scene detection and a local LLM to turn those signals into concise voice guidance for blind and low-vision pedestrians.
</div>
</div>

# 💬 Presentations

- 2026.07 - **XXV ISPRS Congress 2026**  
UrbanVGGT: Scalable Sidewalk Width Estimation from Street View Images  
*Toronto, Canada*  

- 2025.08 - **Global Smart Cities Summit cum The 4th International Conference on Urban Informatics [(GSCS & ICUI 2025)](https://www.isocui.org/icui2025)**  
A Multidimensional AI-powered Framework for Analyzing Tourist Perception in Historic Urban Quarters: A Case Study in Shanghai  
*Hong Kong Polytechnic University (PolyU), Hong Kong SAR, China*  

- 2025.07 - **7th Asia Conference on Machine Learning and Computing [(ACMLC 2025)](https://www.acmlc.org/acmlc2025.html)**  
Multimodal Deep Learning for Modeling Air Traffic Controllers Command Lifecycle and Workload Prediction in Terminal Airspace  
*Hong Kong SAR, China*    

# 💼 Experience

## 🔭 Research Experience

[//]: # (- *2026.04 - Present*, Research Assistant, Shanghai Key Laboratory of Urban Design and Urban Science &#40;LOUD&#41;, NYU Shanghai.)
- *2025.10 - 2026.04*, Research Assistant, Institute of Remote Sensing and Geographic Information System, Peking University, China
- *2024.09 - 2024.12*, Research Officer, [A*STAR Institute for Infocomm Research](https://www.a-star.edu.sg/i2r), Singapore
- *2024.04 - 2025.04*, Research Assistant, College of Architecture and Urban Planning, Tongji University, China
- *2024.04 - 2024.12*, Research Assistant, College of Surveying and Geo-Informatics, Tongji University, China

## 💻 Professional Experience
- *2025.01 - 2025.04*, AI Product Manager, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), China.
- *2023.01 - 2023.02*, Data Analyst, Shanghai Qiantan Emerging Industry Research Institute, China.

[//]: # (### 2027.02, aag2027)

[//]: # (Do we need a robot lane?)

[//]: # (*New York, USA*)

[//]: # ()
[//]: # (### 2026.11, acsp2026)

[//]: # (Do we need a robot lane?)

[//]: # (*Pittsburgh, USA*)
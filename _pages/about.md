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

My research sits at the intersection of **Urban Management and Spatial Intelligence**. I aim to build systems that are both spatially intelligent and socially aware, providing computational solutions to make cities more adaptive, inclusive, and human-centric.

Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, my work is structured around four interdisciplinary pillars:

[//]: # ()
[//]: # (<div class="research-container" style="margin-top: 20px;">)

[//]: # ()
[//]: # (  <div style="margin-bottom: 25px;">)

[//]: # (    <h4 style="margin-bottom: 8px;">🤖 Embodied Urbanism & Collaborative Governance</h4>)

[//]: # (    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;">)

[//]: # (      <i>Core Question: How should embodied intelligence move in cities, and how can humans govern and collaborate with them at scale?</i>)

[//]: # (    </p>)

[//]: # (    <ul style="margin-top: 0; font-size: 0.95em;">)

[//]: # (      <li><b>Robot-Friendly Urban Space:</b> Redesign streets and building interiors for deployment, including siting, infrastructure, protocols, and responsibility boundaries.</li>)

[//]: # (      <li><b>Embodied Navigation:</b> Vision-based navigation and task execution in real urban scenes, with accessibility-aware routing and ground robot and drone platforms.</li>)

[//]: # (      <li><b>Low-Altitude Governance:</b> Derive operable air corridors from demand signals, then validate in 3D city models under privacy, noise, crowds, and other effects.</li>)

[//]: # (      <li><b>Emerging Urban Devices & Deployment:</b> Study city-scale rollout of robots, low-altitude systems, wearables, and BCI-like devices, focusing on deployment bottlenecks.</li>)

[//]: # (      <li><b>Social Acceptance & Ethics:</b> Model how different groups perceive risks and capabilities, guiding interaction design, rollout strategy, and public communication.</li>)

[//]: # (    </ul>)

[//]: # (  </div>)

[//]: # ()
[//]: # (  <div style="margin-bottom: 25px;">)

[//]: # (    <h4 style="margin-bottom: 8px;">🏙️ Self-Evolving Urban Digital Twins</h4>)

[//]: # (    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;">)

[//]: # (      <i>Core Question: How do we build a high-fidelity digital twin that keeps itself updated, hosts urban agents, and improves city governance efficiency?</i>)

[//]: # (    </p>)

[//]: # (    <ul style="margin-top: 0; font-size: 0.95em;">)

[//]: # (      <li><b>Urban Foundation Models:</b> Fuse remote sensing, street-level data, trajectories, IoT, text, and graphs into unified urban representations.</li>)

[//]: # (      <li><b>Measurement & Sensing Loops:</b> Develop scalable metrics and updating pipelines, e.g., measuring sidewalk width from street-view point clouds.</li>)

[//]: # (      <li><b>Localization & Mapping:</b> Advance geo-localization and semantic SLAM across point clouds, meshes, and 3D Gaussian representations for interactive 3D cities.</li>)

[//]: # (      <li><b>Urban Agents:</b> Build task agents for planning and public services, including map-LLM systems, spatial RAG, policy QA, and travel assistance.</li>)

[//]: # (      <li><b>Policy Sandbox & Systems:</b> Use the twin for what-if simulation, risk assessment, and execution checks, supported by efficient retrieval, caching, and rendering.</li>)

[//]: # (    </ul>)

[//]: # (  </div>)

[//]: # ()
[//]: # (  <div style="margin-bottom: 25px;">)

[//]: # (    <h4 style="margin-bottom: 8px;">🎨 Urban Perception & Socio-Cultural Analytics</h4>)

[//]: # (    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;">)

[//]: # (      <i>Core Question: How can local narratives, culture, and human behavior be measured and integrated into models to support urban renewal and governance?</i>)

[//]: # (    </p>)

[//]: # (    <ul style="margin-top: 0; font-size: 0.95em;">)

[//]: # (      <li><b>AI-Enhanced Geospatial Analysis:</b> Large-scale spatial analytics linking urban form, environment, and mobility to human behavior and public service outcomes.</li>)

[//]: # (      <li><b>Urban Perception & Visual Aesthetics:</b> Quantify streetscape perception and neighborhood imagery to inform design choices and regeneration priorities.</li>)

[//]: # (      <li><b>Socio-Cultural Computing:</b> Incorporate dialects and place-based narratives into LLM-enabled applications for communication, interaction, and inclusive governance.</li>)

[//]: # (    </ul>)

[//]: # (  </div>)

[//]: # ()
[//]: # (  <div style="margin-bottom: 25px;">)

[//]: # (    <h4 style="margin-bottom: 8px;">🚀 Spatial Intelligence & Foundation World Models</h4>)

[//]: # (    <p style="margin: 0 0 8px 0; font-size: 0.95em; color: #555;">)

[//]: # (      <i>Core Question: How can world models support reliable, interpretable spatial reasoning and actionable decision-making for physical agents?</i>)

[//]: # (    </p>)

[//]: # (    <ul style="margin-top: 0; font-size: 0.95em;">)

[//]: # (      <li><b>World Models & Architecture:</b> Study generative, predictive, and representation-learning paradigms for forecasting and planning in the physical world.</li>)

[//]: # (      <li><b>Embodied Representations:</b> Unify geometry, semantics, physics, and action into shared representations, with a path toward richer embodied modalities.</li>)

[//]: # (      <li><b>Long-term Memory & Self-Evolution:</b> Build lifelong learning mechanisms with stability, forgetting control, and safety constraints for long-horizon autonomy.</li>)

[//]: # (      <li><b>Neural-Inspired Reasoning:</b> Improve interpretability and robustness of spatial reasoning, exploring 3D-aware encoders and alternatives to standard transformers.</li>)

[//]: # (    </ul>)

[//]: # (  </div>)

[//]: # ()
[//]: # (</div>)

<style>
  .research-container.research-grid{
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 22px;
    margin-top: 20px;
    width: 100%;
    min-height: 72vh;
    align-items: stretch;
    grid-auto-rows: 1fr;
  }

  .research-card{
    background: rgba(255,255,255,0.75);
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 16px;
    padding: 18px 18px 16px 18px;
    box-shadow: 0 10px 28px rgba(0,0,0,0.06);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);

    display: flex;
    flex-direction: column;
    overflow: hidden;
    transition: transform 180ms ease, box-shadow 180ms ease;
  }

  .research-card:hover{
    transform: translateY(-2px);
    box-shadow: 0 14px 36px rgba(0,0,0,0.10);
  }

  .research-card h4{
    margin: 0 0 12px 0;
    line-height: 1.2;
    font-size: 1.1rem;
    font-weight: 800;
    letter-spacing: 0.2px;
  }

  .research-card p{
    margin: 0 0 10px 0;
    font-size: 0.95em;
    color: #555;
  }

  .research-card ul{
    margin: 0;
    padding-left: 1.1em;
    font-size: 0.95em;
    line-height: 1.55;

    flex: 1 1 auto;
    overflow: auto;
  }

  .research-card li{
    margin: 0.2em 0;
  }

  @media (max-width: 900px){
    .research-container.research-grid{
      grid-template-columns: 1fr;
      min-height: auto;
    }
  }

  @media (prefers-color-scheme: dark){
    .research-card{
      background: rgba(20,20,20,0.60);
      border: 1px solid rgba(255,255,255,0.10);
      box-shadow: 0 12px 30px rgba(0,0,0,0.35);
    }
    .research-card p{
      color: rgba(255,255,255,0.75);
    }
  }


</style>

<div class="research-container research-grid">

  <div class="research-card">
    <h4>🤖 Embodied Urbanism <span class="amp">&amp;</span> Collaborative Governance</h4>
    <p><i>Core Question: How should embodied intelligence move in cities, and how can humans govern and collaborate with them at scale?</i></p>
    <ul>
      <li><b>Robot-Friendly Urban Space:</b> Redesign streets and building interiors for robot operations, setting standards for siting, infrastructure, protocols, and responsibility boundaries.</li>
      <li><b>Embodied Navigation:</b> Vision-based navigation and task execution in real urban scenes, with accessibility-aware routing and ground robot and drone platforms.</li>
      <li><b>Low-Altitude Governance:</b> Derive operable air corridors from demand signals, then validate in 3D city models under privacy, noise, crowds, and other effects.</li>
      <li><b>Emerging Urban Devices & Deployment:</b> Study city-scale rollout of robots, low-altitude systems, wearables, and BCI-like devices, focusing on deployment bottlenecks.</li>
      <li><b>Social Acceptance & Ethics:</b> Model how different groups perceive risks and capabilities, guiding interaction design, rollout strategy, and public communication.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🎨 Social Sensing & Human-Environment Interaction</h4>
    <p><i>Core Question: How can local narratives, culture, and human behavior be measured and integrated into models to support urban renewal and governance?</i></p>
    <ul>
      <li><b>AI-Enhanced Geospatial Analysis:</b> Use large-scale spatial analytics to link urban form, environment, and mobility with human behavior and public service outcomes.</li>
      <li><b>Pedestrian-Oriented Design:</b> Analyze walking experiences and accessibility barriers, integrating disabled people’s mobility needs into urban governance decisions.</li>
      <li><b>Urban Perception & Visual Aesthetics:</b> Quantify streetscape perception and neighborhood imagery to inform design choices and regeneration priorities.</li>
      <li><b>Socio-Cultural Computing:</b> Incorporate place-based narratives into LLM-enabled applications for communication, interaction, and inclusive governance.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🏙️ Self-Evolving Urban Digital Twins and Agents</h4>
    <p><i>Core Question: How can we build a self evolving urban digital twin that stays continuously updated, hosts agents, and supports sustainable and equitable city governance?</i></p>
    <ul>
      <li><b>Urban Foundation Models:</b> Fuse remote sensing, street-level data, trajectories, IoT, text, and graphs into unified urban representations.</li>
      <li><b>Measurement & Sensing Loops:</b> Develop scalable metrics and updating pipelines, using robots, drones, and wearables as new data sources for continuous urban sensing.</li>
      <li><b>Localization & Mapping:</b> Advance geo-localization and semantic SLAM across point clouds, meshes, and 3D Gaussian representations for interactive 3D cities.</li>
      <li><b>Urban Agents:</b> Build task agents for planning and public services, including map-LLM systems, spatial RAG, policy QA, and travel assistance.</li>
      <li><b>Policy Sandbox & Systems:</b> Use the twin for what-if simulation, risk assessment, and execution checks, supported by efficient retrieval, caching, and rendering.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🚀 Spatial Intelligence & Foundation World Models</h4>
    <p><i>Core Question: How can world models support reliable spatial reasoning and actionable decision-making for physical agents?</i></p>
    <ul>
      <li><b>World Models & Architecture:</b> Study generative, predictive, and representation-learning paradigms for forecasting and planning in the physical world.</li>
      <li><b>Embodied Representations:</b> Unify geometry, semantics, physics, and action into shared representations, with a path toward richer embodied modalities.</li>
      <li><b>Long-term Memory & Self-Evolution:</b> Build lifelong learning mechanisms with stability, forgetting control, and safety constraints for long-horizon autonomy.</li>
      <li><b>Neural-Inspired Reasoning:</b> Improve interpretability and robustness of spatial reasoning, exploring 3D-aware encoders and alternatives to standard transformers.</li>
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
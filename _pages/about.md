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

Hi! I am Kaizhen Tan (Chinese name: 谭楷蓁). I am currently a master's student in Artificial Intelligence at **Carnegie Mellon University**. I received my bachelor's degree in Information Systems from **Tongji University**, where I built a solid foundation in programming, data analysis, and machine learning, complemented by interdisciplinary training in business and organizational systems.

My research sits at the intersection of **Urban Science** and **Human-centered AI**. Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, I aim to build spatially intelligent and socially aware systems that make cities more adaptive, inclusive, and human-centric.

To realize this vision, my work integrates:
* **Paradigms:** Robot-Friendly City, Lightweight Urbanization, Self-evolving Urban Digital Twins
* **Methodologies:** Social Sensing, Geospatial & Spatiotemporal Data Analysis, Computational Social Science
* **Technologies:** LLMs, VLMs, AI Agents, Embodied AI, Spatial Intelligence, World Models, Emerging Devices

Specifically, my research agenda explores four key topics:

<div class="research-container research-grid">

  <div class="research-card">
    <h4>🤖 1. Robotic Urbanism <span class="amp">&amp;</span> Collaborative Governance</h4>
    <p><i>Core Question: How should embodied intelligence move through cities, and how can humans govern and collaborate with it at scale?</i></p>
    <ul>
      <li><b>Robot-Friendly Urban Space:</b> Redesign streets and building interiors for robot operations, setting standards for siting, infrastructure, protocols, and responsibility boundaries.</li>
      <li><b>Embodied Operation:</b> Vision-based navigation and task execution under real urban constraints, with accessibility-aware routing and compliance with local infrastructure and operational rules.</li>
      <li><b>Low-Altitude Governance:</b> Derive operable air corridors from demand signals, then validate in 3D city models under privacy, noise, crowds, and other effects.</li>
      <li><b>Emerging Urban Devices & Deployment:</b> Study city-scale rollout of robots, low-altitude systems, wearables, and BCI-like devices, focusing on deployment bottlenecks.</li>
      <li><b>Public Acceptance & Ethics:</b> Model how different groups perceive risks and capabilities, guiding interaction design, rollout strategy, and public communication.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🏙️ 2. Self-Evolving Urban Digital Twins and Agents</h4>
    <p><i>Core Question: How can we build self-evolving urban digital twin that stays continuously updated, hosts agents, and supports sustainable and equitable city governance?</i></p>
    <ul>
      <li><b>Urban Foundation Model:</b> Integrate remote sensing, street-level imagery, mobility trajectory, POI, IoT signal, and text into unified urban representations.</li>
      <li><b>Measurement & Sensing Pipelines:</b> Develop scalable metrics and updating pipelines, using robots, drones, and wearables as new data sources for continuous urban sensing.</li>
      <li><b>Localization, Mapping, and 3D City:</b> Geo-localization and semantic mapping across point clouds, meshes, and 3D Gaussian representations for interactive querying and simulation.</li>
      <li><b>Urban Agents:</b> Build task agents for planning and public services, including map-LLM, spatial RAG, policy QA, and travel assistance.</li>
      <li><b>Policy Sandbox:</b> Use the twin for what-if simulation, risk assessment, and execution checks, supported by efficient retrieval, caching, and rendering.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🎨 3. Social Sensing <span class="amp">&amp;</span> Human-Environment Interaction</h4>
    <p><i>Core Question: How can multimodal human-centered data translate into actionable insights for urban planning and governance?</i></p>
    <ul>
      <li><b>AI-Enhanced Geospatial Analysis:</b> Use large-scale spatial analytics to link urban form, environment, and mobility with human behavior and public service outcomes.</li>
      <li><b>Accessibility & Pedestrian Experience:</b> Analyze walking experiences and accessibility barriers, integrating disabled people's mobility needs into urban governance decisions.</li>
      <li><b>Urban Perception & Visual Aesthetics:</b> Quantify streetscape perception and neighborhood imagery to inform design choices and regeneration priorities.</li>
      <li><b>Socio-Cultural Signals for Governance:</b> Incorporate place-based narratives into LLM-enabled applications for communication, interaction, and inclusive governance.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🚀 4. Spatial Intelligence <span class="amp">&amp;</span> Foundation World Models</h4>
    <p><i>Core Question: How can world models support reliable spatial reasoning and decision-making for physical agents?</i></p>
    <ul>
      <li><b>World Models & Architectures:</b> Study generative, predictive, and representation-learning paradigms for forecasting and planning in the physical world.</li>
      <li><b>Embodied Representations:</b> Unify geometry, semantics, physics, and action into shared representations, with a path toward richer embodied modalities.</li>
      <li><b>Long-term Memory & Self-Evolution:</b> Build lifelong learning mechanisms with stability, forgetting control, and safety constraints for long-horizon autonomy.</li>
      <li><b>Interpretable Spatial Reasoning:</b> Improve interpretability and robustness of spatial reasoning, exploring 3D-aware encoders and alternatives to standard transformers.</li>
    </ul>
  </div>
</div>



# 🔥 News

<div class="news-scroll" markdown="1">

- *2026.03*: 🎓 I am pleased to share that I will begin my PhD at New York University in Fall 2026 under the supervision of [Prof. Chenghe Guan](https://wagner.nyu.edu/community/faculty/chenghe-guan) and [Prof. Zhan Guo](https://wagner.nyu.edu/community/faculty/zhan-guo).
- *2026.01*: 🎉 The abstract co-authored with Prof. Fan Zhang has been accepted for the [XXV ISPRS Congress 2026](https://www.isprs2026toronto.com/). See you in Toronto!
- *2025.12*: 🎉 Our paper, led by my senior labmate Dr. Weihua Huan and co-authored with Prof. Wei Huang at Tongji University, was accepted by GIScience & Remote Sensing; honored to contribute as second author and big congratulations to Dr. Huan!
- *2025.10*: 🔭 Joined [Prof. Yu Liu](https://scholar.google.com/citations?user=Xh_lRY4AAAAJ) and [Prof. Fan Zhang](https://scholar.google.com/citations?user=dc1TzLoAAAAJ)'s team at Peking University as a remote research assistant.
- *2025.08*: 🎉 Delivered an oral presentation at Hong Kong Polytechnic University after our paper was accepted to the Global Smart Cities Summit cum The 4th International Conference on Urban Informatics [(GSCS & ICUI 2025)](https://www.isocui.org/icui2025).
- *2025.07*: 🎉 My undergraduate thesis was accepted by 7th Asia Conference on Machine Learning and Computing [(ACMLC 2025)](https://www.acmlc.org/acmlc2025.html).
- *2025.06*: 🎓 Graduated from Tongji University—grateful for the journey and excited to continue my studies at CMU.
- *2025.04*: 🔭 Completed the SITP project under the supervision of [Prof. Yujia Zhai](https://www.researchgate.net/profile/Yujia-Zhai-15) in the College of Architecture and Urban Planning.
- *2025.01*: 💼 Joined Shanghai Artificial Intelligence Laboratory as an AI Product Manager Intern.
- *2024.09*: 🌏 Conducted research at ASTAR in Singapore under the supervision of [Dr. Yicheng Zhang](https://zinczhang.github.io/) and [Dr. Sheng Zhang](https://ieeexplore.ieee.org/author/37086165610).
- *2024.04*: 🔭 Began my academic journey at [Prof. Wei Huang](https://huangweibuct.github.io/weihuang.github.io/)'s lab in the College of Surveying and Geo-Informatics, Tongji University.

</div>


# 📖 Education

<div class="edu-item">
  <img class="edu-logo" src="/assets/nyu2.jpg" alt="NYU" />
  <div class="edu-content">
    <div class="edu-top">
      <strong>New York University</strong>
    </div>
    <div class="edu-sub"><em>2026.09 – 2031.05 (expected)</em></div>
    <div class="edu-sub"><em>Ph.D. student in Public Administration (Urban Policy)</em></div>
  </div>
</div>

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


# 💼 Experience

## 🔭 Research

- *2026.04 - Present*, Research Assistant, Shanghai Key Laboratory of Urban Design and Urban Science (LOUD)
- *2025.10 - 2026.03*, Research Assistant, Institute of Remote Sensing and GIS, Peking University, China
- *2024.09 - 2024.12*, Research Officer Intern, [A*STAR Institute for Infocomm Research](https://www.a-star.edu.sg/i2r), Singapore
- *2024.04 - 2025.04*, Research Assistant, College of Architecture and Urban Planning, Tongji University, China
- *2024.04 - 2024.12*, Research Assistant, College of Surveying and Geo-Informatics, Tongji University, China

## 💻 Industry
- *2025.01 - 2025.04*, AI Product Manager, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), China.
- *2023.01 - 2023.02*, Data Analyst, Shanghai Qiantan Emerging Industry Research Institute, China.


# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">XXV ISPRS Congress</div><img src='images/5.jpg' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">UrbanVGGT: Scalable Sidewalk Width Estimation from Street View Images</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Fan Zhang</span>
    </div>
    <div class="paper-venue">
      XXV ISPRS Congress, 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="/assets/isprs_abstract_kaizhen_fan.pdf">Abstract</a>
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      Leverage street-view imagery and VGGT-based 3D reconstruction to estimate metrically scaled sidewalk widths, build the SV-SideWidth dataset, and fill OpenStreetMap gaps for equitable assessment of pedestrian infrastructure.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">GSCS & ICUI 2025</div><img src='images/2.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Decoding Tourist Perception in Historic Urban Quarters with Multimodal Social Media Data: An AI-Based Framework and Evidence from Shanghai</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Yufan Wu, Yuxuan Liu, Haoran Zeng</span>
    </div>
    <div class="paper-venue">
      Global Smart Cities Summit cum The 4th International Conference on Urban Informatics, 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2509.03830">arXiv</a>
      <a class="paper-link" href="/assets/ICUI2025.pptx">Slides</a>
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      Developed an AI-powered multimodal framework to analyze tourist perception in historic Shanghai quarters, integrating image segmentation, color theme analysis, and sentiment mining for heritage-informed urban planning.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ACMLC 2025</div><img src='images/21.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Multimodal Deep Learning for Modeling Air Traffic Controllers Command Lifecycle and Workload Prediction in Terminal Airspace</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span>
    </div>
    <div class="paper-venue">
      Asia Conference on Machine Learning and Computing, 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://doi.org/10.1145/3772673.3772702">DOI</a>
      <a class="paper-link" href="https://dl.acm.org/doi/epdf/10.1145/3772673.3772702">PDF</a>
      <a class="paper-link" href="/assets/ACMLC2025.pptx">Slides</a>
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      Designed a multimodal deep learning framework linking ATCO voice commands with aircraft trajectories to model workload dynamics, enabling intelligent command generation and scheduling support.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">GIScience & Remote Sensing</div><img src='images/4.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">A Spatiotemporal Adaptive Local Search Method for Tracking Congestion Propagation in Dynamic Networks</div>
    <div class="paper-authors">
      <span class="author-other">Weihua Huan, </span><span class="author-self">Kaizhen Tan</span><span class="author-other">, Xintao Liu, Shoujun Jia, Shijun Lu, Jing Zhang, Wei Huang</span>
    </div>
    <div class="paper-venue">
      GIScience & Remote Sensing, 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://doi.org/10.1080/15481603.2025.2602215">DOI</a>
      <a class="paper-link" href="https://www.tandfonline.com/doi/epdf/10.1080/15481603.2025.2602215">PDF</a>
    </div>
    <div class="paper-desc">
      Proposed a spatiotemporal adaptive local search (STALS) method combining dynamic graph learning and spatial analytics to model and mitigate large-scale urban traffic congestion propagation.
    </div>
  </div>
</div>

# 🔬 Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><img src='images/blindnav.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">BlindNav: YOLO+LLM for Real-Time Navigation Assistance for Blind Users</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Yufan Wang, Yixiao Li, Hanzhe Hong, Nicole Lyu</span>
    </div>
    <div class="paper-links">
      <a class="paper-link" href="/assets/blindnav.pdf">Report</a>
      <a class="paper-link" href="https://github.com/tantansir/BlindNav">GitHub</a>
    </div>
    <div class="paper-desc">
      BlindNav is a real-time, camera-based navigation assistant that uses YOLO for street-scene detection and a local LLM to turn those signals into concise voice guidance for blind and low-vision pedestrians.
    </div>
  </div>
</div>


# 💬 Presentations

<ul class="pres-list">
  <li class="pres-item">
    2026.07 - <strong>XXV ISPRS Congress 2026</strong><br>
    UrbanVGGT: Scalable Sidewalk Width Estimation from Street View Images<br>
    <em>Toronto, Canada</em>
  </li>

  <li class="pres-item">
    2025.08 - <strong>Global Smart Cities Summit cum The 4th International Conference on Urban Informatics <a href="https://www.isocui.org/icui2025">(GSCS & ICUI 2025)</a></strong><br>
    A Multidimensional AI-powered Framework for Analyzing Tourist Perception in Historic Urban Quarters: A Case Study in Shanghai<br>
    <em>Hong Kong Polytechnic University (PolyU), Hong Kong SAR, China</em>
  </li>

  <li class="pres-item">
    2025.07 - <strong>7th Asia Conference on Machine Learning and Computing <a href="https://www.acmlc.org/acmlc2025.html">(ACMLC 2025)</a></strong><br>
    Multimodal Deep Learning for Modeling Air Traffic Controllers Command Lifecycle and Workload Prediction in Terminal Airspace<br>
    <em>Hong Kong SAR, China</em>
  </li>
</ul>

[//]: # (### 2027.02, aag2027)
[//]: # (Do we need a robot lane?)
[//]: # (*New York, USA*)

# 📫 Contact
- Email(CMU): kaizhent@cmu.edu
- Email(NYU): kt3275@nyu.edu
- Email(personal): wflps20140311@gmail.com

<p class="connect-text">
  Please feel free to reach out if any of these research directions resonate with you. I'd be happy to chat!
</p>


# 🌍 Visitor Map

<div class="visitor-map-wrap">
  <div class="visitor-map-card">
    <div class="visitor-map-embed" aria-label="Visitor map">
      <script type="text/javascript" id="mapmyvisitors"
        src="//mapmyvisitors.com/map.js?d=fU8cgDogJMfp7fmFhvAp5fSI9CakxNg1n0lI_B_Gc6o&cl=ffffff&w=a">
      </script>
    </div>
  </div>
</div>

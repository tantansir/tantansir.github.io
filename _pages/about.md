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

Hi! I am Kaizhen Tan (Chinese name: 谭楷蓁), an incoming Ph.D. student at **New York University**, currently pursuing my master’s degree in Artificial Intelligence at **Carnegie Mellon University**. I received my bachelor’s degree in Information Systems from **Tongji University**.

My research sits at the intersection of <b>Urban Science</b>, <b>Human-centered AI</b>, and <b>Embodied Intelligence</b>. Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, I aim to address the knowledge-to-action gap in digital cities: while urban digital systems are increasingly capable of monitoring conditions, modeling urban dynamics, and anticipating risks, they still struggle to support timely, place-based action. My work seeks to build spatially intelligent and socially aware urban AI systems that make cities more adaptive, inclusive, and governable.

My research integrates:
* **Paradigms:** Robotic Urbanization, Agentic Urban Digital Twins, Human-centered Urban Governance
* **Methodologies:** Multimodal Learning, Geospatial & Spatiotemporal Data Analysis, Computational Social Science
* **Technical Foundations:** LLMs, VLMs, AI Agents, Embodied AI, Spatial Intelligence, World Models, Emerging Devices

Specifically, my research agenda is organized around four key topics:

<div class="research-container research-grid">

  <div class="research-card">
    <h4>🤖 1. Robot-Friendly Urban Space</h4>
    <p><i>How can dense cities integrate embodied intelligence while preserving safety, accessibility, and pedestrian experience?</i></p>
    <ul>
      <li><b>Urban Readiness for Robots:</b> Measure whether sidewalks, crossings, curbs, buildings, and public facilities can support safe robot operation.</li>
      <li><b>Human-Robot Coexistence:</b> Study conflicts, comfort, right-of-way, and interaction norms between robots, pedestrians, cyclists, and vulnerable groups.</li>
      <li><b>Accessibility-Aware Deployment:</b> Design routing and operation strategies that avoid reducing mobility for disabled people, older adults, and children.</li>
      <li><b>Curbside and Low-Altitude Governance:</b> Develop spatial rules for delivery robots and drones, including lanes, parking, corridors, privacy, noise, and safety constraints.</li>
      <li><b>Public Acceptance and Accountability:</b> Model public perception, responsibility boundaries, and governance mechanisms for city-scale deployment.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🏙️ 2. Agentic Urban Digital Twins</h4>
    <p><i>How can urban digital twins evolve from static city models into continuously updated systems for sensing, reasoning, and policy support?</i></p>
    <ul>
      <li><b>Urban Foundation Representations:</b> Fuse remote sensing, street-view imagery, trajectories, POI, IoT, text, and 3D data into unified urban representations.</li>
      <li><b>Continuous Urban Sensing:</b> Use robots, drones, mobile devices, and wearables as emerging data sources to update urban conditions over time.</li>
<li><b>3D City Understanding:</b> Support geo-localization, semantic mapping, and spatial querying across point clouds, meshes, and 3D Gaussians.</li>
      <li><b>Urban Agents:</b> Build LLM and VLM agents for map reasoning, spatial RAG, policy QA, public service assistance, and planning workflows.</li>
      <li><b>Policy Sandbox:</b> Enable what-if simulation, risk assessment, and implementation checks for urban management and public policy.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🎨 3. Multimodal Social Sensing</h4>
    <p><i>How can multimodal human-centered data reveal urban experience, social needs, and governance priorities?</i></p>
    <ul>
      <li><b>AI-Enhanced Geospatial Analysis:</b> Link urban form, environment, mobility, and public services with human behavior and social outcomes.</li>
      <li><b>Pedestrian Experience and Accessibility:</b> Detect walking barriers, sidewalk quality, perceived safety, and mobility challenges in everyday urban environments.</li>
      <li><b>Urban Perception and Visual Aesthetics:</b> Quantify streetscape quality, neighborhood imagery, and place identity to support design and regeneration decisions.</li>
      <li><b>Socio-Cultural Signals:</b> Extract place-based narratives from text, images, and online platforms to understand local identity and public concerns.</li>
      <li><b>Participatory Governance:</b> Translate social sensing results into explainable tools for planners, communities, and decision-makers.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🚀 4. Spatial Intelligence <span class="amp">&amp;</span> World Models</h4>
    <p><i>How can spatial intelligence provide reliable reasoning, memory, and simulation capabilities for urban AI systems?</i></p>
    <ul>
      <li><b>Embodied Spatial Representations:</b> Unify geometry, semantics, physics, affordance, and action for robots, agents, and urban digital twins.</li>
      <li><b>Urban World Models:</b> Learn predictive models of how urban spaces change and how agents interact with physical and social environments.</li>
      <li><b>Spatial Reasoning with VLMs:</b> Improve map understanding, 3D reasoning, scene interpretation, and location-aware decision-making.</li>
      <li><b>Lifelong Updating and Memory:</b> Develop mechanisms for continuous learning, forgetting control, uncertainty tracking, and safe model updates.</li>
      <li><b>Interpretable and Robust Decision Support:</b> Make spatial AI systems transparent enough for planning, governance, and real-world deployment.</li>
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
- *2026.04 - Present*, Research Assistant, [Shanghai Key Laboratory of Urban Design and Urban Science (LOUD)](https://urban.shanghai.nyu.edu/), NYU Shanghai, China
- *2025.10 - 2026.03*, Research Assistant, [Spatio-Temporal Social Sensing Lab (S3-Lab)](https://geos3.netlify.app/), Peking University, China
- *2024.09 - 2024.12*, Research Officer Intern, [A*STAR Institute for Infocomm Research](https://www.a-star.edu.sg/i2r), Singapore
- *2024.04 - 2025.04*, Research Assistant, [College of Architecture and Urban Planning](https://caup.tongji.edu.cn/caupen/main.psp), Tongji University, China
- *2024.04 - 2024.12*, Research Assistant, [College of Surveying and Geo-Informatics](https://celiang.tongji.edu.cn/english/Home.htm), Tongji University, China

## 💻 Industry
- *2025.01 - 2025.04*, AI Product Manager, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), China.
- *2023.01 - 2023.02*, Data Analyst, [Shanghai Qiantan Emerging Industry Research Institute](https://www.idss.org.cn/), China

# 📝 Selected Papers

## Peer-Reviewed

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
      <a class="paper-link" href="https://arxiv.org/pdf/2603.22531">arXiv</a>
      <a class="paper-link" href="/assets/isprs_abstract_kaizhen_fan.pdf">Abstract</a>
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      Present UrbanVGGT, a measurement pipeline for estimating metrically scaled sidewalk width from a single street-view image using VGGT-based 3D reconstruction, semantic segmentation, and ground-plane fitting, achieving 0.25 m MAE on a Washington D.C. benchmark.
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
      <a class="paper-link" href="https://arxiv.org/pdf/2509.03830">arXiv</a>
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
      <strong><span class='show_paper_citations' data='JtyjnWYAAAAJ:qjMakFHDy7sC'></span></strong>
    </div>
    <div class="paper-desc">
      Proposed a spatiotemporal adaptive local search (STALS) method combining dynamic graph learning and spatial analytics to model and mitigate large-scale urban traffic congestion propagation.
    </div>
  </div>
</div>

## Preprints

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">Preprint</div><img src='images/creg.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">CREG: Compass Relational Evidence Graph for Characterizing Directional Structure in VLM Spatial-Reasoning Attribution</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Preprint, 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/pdf/2603.20475">arXiv</a>
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      A training-free interpretability framework that maps vision-language model attributions into a polar coordinate system to reveal how VLMs reason about spatial relations.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">Preprint</div><img src='images/robotlane.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Do We Need a Robot Lane? A Simulation-Based Screening Framework for Sidewalk Delivery Robots</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Preprint, 2026.
    </div>
    <div class="paper-links">
      <!-- <a class="paper-link" href="/assets/robotlane.pdf">PDF</a> -->
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      When should cities give sidewalk robots their own lane? An agent-based simulation framework that screens shared vs. dedicated space policies to answer this question.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">Preprint</div><img src='images/Pruning.png' alt="token pruning calibration" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Does Visual Token Pruning Improve Calibration? An Empirical Study on Confidence in MLLMs</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span>
    </div>
    <div class="paper-venue">
      Preprint, 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/pdf/2604.12035">arXiv</a>
    </div>
    <div class="paper-desc">
      Do visual tokens need to be kept for reliable confidence? This paper shows that moderate coverage-based pruning can make MLLMs better calibrated without noticeably hurting accuracy.
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">Preprint</div><img src='images/metro.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">What We Lose, What We Gain: Spatio-temporal Patterns of Lost-and-Found Items in Qingdao Metro</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Preprint, 2026.
    </div>
    <div class="paper-links">
      <!-- <a class="paper-link" href="/assets/metro.pdf">PDF</a> -->
      <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
    </div>
    <div class="paper-desc">
      Analyze 34,333 lost-and-found records across 173 metro stations to uncover spatio-temporal loss patterns, holiday effects, and station-level hotspots for transit service optimization.
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

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><img src='images/ragcache.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">RAGCache++: Cache-Aware Document Ordering for Low-Latency RAG Serving</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Rong Gu, Mingyuan Li</span>
    </div>
    <div class="paper-links">
      <a class="paper-link" href="/assets/RAGCACHE++.pdf">Report</a>
      <a class="paper-link" href="https://github.com/tantansir/RAGCachePlusPlus">GitHub</a>
    </div>
    <div class="paper-desc">
      Propose RAGCache++, a lightweight prompt-level optimization that reorders retrieved documents to maximize prefix sharing with cached sequences via a knowledge tree and greedy algorithm, reducing median TTFT by 20–33% with zero GPU memory cost and no serving-engine modification.
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
        <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=fU8cgDogJMfp7fmFhvAp5fSI9CakxNg1n0lI_B_Gc6o&cmo=f31919&cmn=f31919&co=2484c8'></script>
    </div>
  </div>
</div>

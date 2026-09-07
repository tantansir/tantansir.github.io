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

Hi! I am Kaizhen Tan, a Ph.D. student at **New York University**, supervised by [Prof. Chenghe Guan](https://wagner.nyu.edu/community/faculty/chenghe-guan) and [Prof. Zhan Guo](https://wagner.nyu.edu/community/faculty/zhan-guo). I received my master’s degree in Artificial Intelligence at **Carnegie Mellon University** and bachelor’s degree in Information Systems from **Tongji University**.

My research sits at the intersection of <b>Urban Science</b> and <b>Embodied AI</b>. Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, I aim to address the knowledge-to-action gap in digital cities: while urban digital systems are increasingly capable of monitoring conditions, modeling urban dynamics, and anticipating risks, they still struggle to support timely, place-based action. My work seeks to build spatially intelligent and socially aware urban AI systems that make cities more adaptive, inclusive, and governable.

My research integrates:
* **Paradigms:** Robotic Urbanization, Agentic Urban Digital Twins, Multimodal Social Sensing, Spatial Intelligence
* **Methodologies:** Representation Learning, Geospatial & Spatiotemporal Data Analysis, Agent-Based Simulation
* **Technical Foundations:** LLMs, VLMs, AI Agents, World Models

Specifically, my research agenda is organized around four key topics:

<div class="research-container research-grid">

  <div class="research-card">
    <h4>🤖 1. Robotic Urbanization <span class="amp">&amp;</span> Governance</h4>
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

- *2026.07*: 🎉 Our paper [CREG](https://arxiv.org/abs/2603.20475) was accepted by the 9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV 2026).
- *2026.03*: 🎓 I am pleased to share that I will begin my PhD at New York University in Fall 2026 under the supervision of [Prof. Chenghe Guan](https://wagner.nyu.edu/community/faculty/chenghe-guan) and [Prof. Zhan Guo](https://wagner.nyu.edu/community/faculty/zhan-guo).
- *2026.01*: 🎉 The abstract co-authored with Prof. Fan Zhang has been accepted for the [XXV ISPRS Congress 2026](https://www.isprs2026toronto.com/). See you in Toronto!
- *2025.12*: 🎉 Our paper, led by my senior labmate Dr. Weihua Huan and co-authored with Prof. Wei Huang at Tongji University, was accepted by GIScience & Remote Sensing; honored to contribute as second author and big congratulations to Dr. Huan!
- *2025.10*: 🔭 Joined [Prof. Yu Liu](https://scholar.google.com/citations?user=Xh_lRY4AAAAJ) and [Prof. Fan Zhang](https://scholar.google.com/citations?user=dc1TzLoAAAAJ)'s team at Peking University as a remote research assistant.
- *2025.08*: 🎉 Delivered an oral presentation at Hong Kong Polytechnic University after our paper was accepted to the Global Smart Cities Summit cum The 4th International Conference on Urban Informatics [(GSCS & ICUI 2025)](https://www.isocui.org/icui2025).
- *2024.04*: 🔭 Began my academic journey at [Prof. Wei Huang](https://huangweibuct.github.io/weihuang.github.io/)'s lab in the College of Surveying and Geo-Informatics, Tongji University.

</div>


# 📖 Education

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-nyu.png" alt="New York University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong>New York University</strong>
      <span class="exp-date">2026.09 – 2031.05</span>
    </div>
    <div class="exp-role">Ph.D. student in Urban Science · New York / Shanghai</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-cmu.png" alt="Carnegie Mellon University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong>Carnegie Mellon University</strong>
      <span class="exp-date">2025.08 – 2026.08</span>
    </div>
    <div class="exp-role">M.S. in Artificial Intelligence · Pittsburgh</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-tongji.png" alt="Tongji University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong>Tongji University</strong>
      <span class="exp-date">2021.09 – 2025.06</span>
    </div>
    <div class="exp-role">B.Mgt. in Information Systems · Shanghai</div>
  </div>
</div>

# 💼 Experience

## 🔭 Research

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-nyush.png" alt="NYU Shanghai" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://urban.shanghai.nyu.edu/">Shanghai Key Laboratory of Urban Design and Urban Science (LOUD)</a></strong>
      <span class="exp-date">2026.05 – Present</span>
    </div>
    <div class="exp-role">Research Assistant · NYU Shanghai, China</div>
    <div class="exp-advisor"><span class="exp-advisor__label">Advisors</span><a href="https://urban.shanghai.nyu.edu/team-member/chenghe-guan">Prof. Chenghe Guan</a>, <a href="https://urban.shanghai.nyu.edu/team-member/zhaonan">Prof. Zhaonan Wang</a></div>
    <div class="exp-desc">Designing embodied-intelligence-friendly urban spaces, and advancing collaborative governance through digital twins and urban agents that model complex city dynamics.</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-pku.png" alt="Peking University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://geos3.netlify.app/">Spatio-Temporal Social Sensing Lab (S3-Lab)</a></strong>
      <span class="exp-date">2025.10 – 2026.03</span>
    </div>
    <div class="exp-role">Research Assistant · Peking University, China</div>
    <div class="exp-advisor"><span class="exp-advisor__label">Advisors</span><a href="https://irsgis.pku.edu.cn/english/facultystaff/gis/liuyu/index.htm">Prof. Yu Liu</a>, <a href="https://irsgis.pku.edu.cn/english/facultystaff/gis/zhangfan/index.htm">Prof. Fan Zhang</a></div>
    <div class="exp-desc">Automated urban element measurement from street view using VGGT and semantic segmentation, recovering metric scale via ground-plane fitting and camera-height calibration for large-scale data generation.</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-astar.png" alt="A*STAR" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://www.a-star.edu.sg/i2r">A*STAR, Institute for Infocomm Research</a></strong>
      <span class="exp-date">2024.09 – 2025.05</span>
    </div>
    <div class="exp-role">Research Intern · Singapore</div>
    <div class="exp-advisor"><span class="exp-advisor__label">Advisors</span><a href="https://zinczhang.github.io/">Dr. Yicheng Zhang</a>, <a href="https://ieeexplore.ieee.org/author/37086165610">Dr. Sheng Zhang</a></div>
    <div class="exp-desc">Modeled air traffic controller communication tasks to predict workload from radiotelephony and trajectory data, integrating multi-source air traffic data with a CNN-Transformer model.</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-tongji.png" alt="Tongji University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://caup.tongji.edu.cn/caupen/main.psp">College of Architecture and Urban Planning</a></strong>
      <span class="exp-date">2024.04 – 2025.04</span>
    </div>
    <div class="exp-role">Research Assistant · Tongji University, China</div>
    <div class="exp-advisor"><span class="exp-advisor__label">Advisor</span><a href="https://www.researchgate.net/profile/Yujia-Zhai-15">Prof. Yujia Zhai</a></div>
    <div class="exp-desc">Built a multimodal pipeline over social media reviews and photos to analyze tourist perception of historic quarters, fine-tuning segmentation models and applying sentiment analysis for multi-dimension satisfaction scores.</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-tongji.png" alt="Tongji University" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://celiang.tongji.edu.cn/english/Home.htm">College of Surveying and Geo-Informatics</a></strong>
      <span class="exp-date">2024.04 – 2024.12</span>
    </div>
    <div class="exp-role">Research Assistant · Tongji University, China</div>
    <div class="exp-advisor"><span class="exp-advisor__label">Advisor</span><a href="https://huangweibuct.github.io/weihuang.github.io/">Prof. Wei Huang</a></div>
    <div class="exp-desc">Modeled traffic congestion propagation with spatiotemporal graphs and multi-scale community search, linking propagation patterns to built environment factors via causal analysis and POI-based features.</div>
  </div>
</div>

## 💻 Industry

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-shlab.png" alt="Shanghai AI Laboratory" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://www.shlab.org.cn/">Shanghai Artificial Intelligence Laboratory</a></strong>
      <span class="exp-date">2025.01 – 2025.04</span>
    </div>
    <div class="exp-role">AI Product Manager Intern · Shanghai, China</div>
    <div class="exp-desc">Ran end-to-end market and competitive analysis for AI products (Migo, Auto-Research) against 50+ vertical tools, built an operational KPI dashboard for retention and behavior funnels, and established evaluation frameworks for Migo's InternLM model.</div>
  </div>
</div>

<div class="exp-item">
  <img class="exp-logo" src="/assets/logo-idss.png" alt="Shanghai Qiantan Emerging Industry Research Institute" />
  <div class="exp-content">
    <div class="exp-top">
      <strong><a href="https://www.idss.org.cn/">Shanghai Qiantan Emerging Industry Research Institute</a></strong>
      <span class="exp-date">2023.01 – 2023.02</span>
    </div>
    <div class="exp-role">Data Analyst · Shanghai, China</div>
  </div>
</div>

# 📝 Publications

<div class="pub-filter" id="pubFilter" role="group" aria-label="Filter publications by research direction">
  <button type="button" class="pub-pill is-active" data-filter="all" aria-pressed="true">All<span class="pub-pill__n"></span></button>
  <button type="button" class="pub-pill" data-filter="robotic" aria-pressed="false">🤖 Robotic Urbanization<span class="pub-pill__n"></span></button>
  <button type="button" class="pub-pill" data-filter="twins" aria-pressed="false">🏙️ Urban Digital Twins<span class="pub-pill__n"></span></button>
  <button type="button" class="pub-pill" data-filter="sensing" aria-pressed="false">🎨 Spatiotemporal Analysis &amp; Social Sensing<span class="pub-pill__n"></span></button>
  <button type="button" class="pub-pill" data-filter="spatial" aria-pressed="false">🚀 Spatial Intelligence &amp; World Models<span class="pub-pill__n"></span></button>
  <button type="button" class="pub-pill" data-filter="others" aria-pressed="false">✦ AI Systems &amp; Multimodal Learning<span class="pub-pill__n"></span></button>
</div>

<div class="pub-group">
<h3 class="pub-group__title">Peer-Reviewed</h3>

<div class='paper-box paper-box--lead' data-tags="twins robotic">
  <div class='paper-box-image'>
    <div><img src='images/5.jpg' alt="UrbanVGGT" width="100%"></div>
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
      <a class="paper-link" href="https://doi.org/10.5194/isprs-archives-XLIX-B2-2026-559-2026">DOI</a>
      <a class="paper-link" href="https://arxiv.org/abs/2603.22531">arXiv</a>
      <a class="paper-link" href="/assets/poster.pdf">Poster</a>
    </div>
    <div class="paper-desc">
      A measurement pipeline that estimates metrically scaled sidewalk width from a single street-view image through VGGT-based 3D reconstruction, semantic segmentation, and adaptive ground-plane fitting, reaching 0.25 m MAE on a Washington D.C. benchmark.
    </div>
  </div>
</div>

<div class='paper-box paper-box--lead' data-tags="sensing">
  <div class='paper-box-image'>
    <div><img src='images/4.png' alt="STALS" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">A Spatiotemporal Adaptive Local Search Method for Tracking Congestion Propagation in Dynamic Networks</div>
    <div class="paper-authors">
      <span class="author-other">Weihua Huan, </span><span class="author-self">Kaizhen Tan</span><span class="author-other">, Xintao Liu, Shoujun Jia, Shijun Lu, Jing Zhang, Wei Huang</span>
    </div>
    <div class="paper-venue">
      GIScience &amp; Remote Sensing, 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://doi.org/10.1080/15481603.2025.2602215">DOI</a>
      <a class="paper-link" href="https://arxiv.org/abs/2509.06099">arXiv</a>
    </div>
    <div class="paper-desc">
      A spatiotemporal adaptive local search (STALS) method combining dynamic graph learning and spatial analytics to trace how large-scale urban traffic congestion propagates through a road network.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="sensing">
  <div class='paper-box-image'>
    <div><img src='images/2.png' alt="Tourist perception framework" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Decoding Tourist Perception in Historic Urban Quarters with Multimodal Social Media Data: An AI-Based Framework and Evidence from Shanghai</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Yufan Wu, Yuxuan Liu, Haoran Zeng</span>
    </div>
    <div class="paper-venue">
      Global Smart Cities Summit cum The 4th International Conference on Urban Informatics (GSCS &amp; ICUI), 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2509.03830">arXiv</a>
      <a class="paper-link" href="/assets/ICUI2025.pptx">Slides</a>
    </div>
    <div class="paper-desc">
      A multimodal framework for reading tourist perception in historic Shanghai quarters, combining image segmentation, color theme analysis, and sentiment mining into four-dimensional satisfaction scores.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="others">
  <div class='paper-box-image'>
    <div><img src='images/21.png' alt="ATCO command lifecycle" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Multimodal Deep Learning for ATCO Command Lifecycle Modeling and Workload Prediction</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span>
    </div>
    <div class="paper-venue">
      7th Asia Conference on Machine Learning and Computing, 2025.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://doi.org/10.1145/3772673.3772702">DOI</a>
      <a class="paper-link" href="https://arxiv.org/abs/2509.10522">arXiv</a>
      <a class="paper-link" href="/assets/ACMLC2025.pptx">Slides</a>
    </div>
    <div class="paper-desc">
      A CNN-Transformer framework linking air traffic controller voice commands to aircraft trajectories, modeling command lifecycle and workload dynamics to support command generation and scheduling in terminal airspace.
    </div>
  </div>
</div>

<div class='paper-box paper-box--lead' data-tags="spatial">
  <div class='paper-box-image'>
    <div><img src='images/CREG.png' alt="CREG" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">CREG: Compass Relational Evidence Graph for Characterizing Directional Structure in VLM Spatial-Reasoning Attribution</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Yang Feng, Heqing Du</span>
    </div>
    <div class="paper-venue">
      9th Chinese Conference on Pattern Recognition and Computer Vision (PRCV), 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2603.20475">arXiv</a>
    </div>
    <div class="paper-desc">
      A training-free diagnostic that maps vision-language model attributions onto a compass graph, measuring whether the evidence a model attends to aligns with the queried spatial direction. Higher accuracy does not imply better directional structure.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="others">
  <div class='paper-box-image'>
    <div><img src='images/ragcache.png' alt="CacheWeaver" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">CacheWeaver: Cache-Aware Evidence Ordering for Efficient Grounded RAG Inference</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Rong Gu, Mingyuan Li</span>
    </div>
    <div class="paper-venue">
      GroundLM @ EMNLP 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2606.19667">arXiv</a>
    </div>
    <div class="paper-desc">
      A prompt-layer reordering method that rearranges retrieved evidence so overlapping passages share prefix-cache hits, cutting median time-to-first-token by 20–33% across three vLLM configurations without touching the serving engine or the evidence set.
    </div>
  </div>
</div>
</div>

<div class="pub-group">
<h3 class="pub-group__title">Preprints &amp; Under Review</h3>

<div class='paper-box paper-box--lead' data-tags="spatial">
  <div class='paper-box-image'>
    <div><img src='images/geofidelity.jpg' alt="Real street views compared with six text-to-image generators across six cities" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">GeoFidelity-Bench: Evaluating Segment-Level Geographic Fidelity in Text-to-Image Street-View Generation</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to NeurIPS 2026.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2606.23669">arXiv</a>
    </div>
    <div class="paper-desc">
      A benchmark of 7,117 curated Mapillary images over 109 named road segments in 25 cities, asking whether text-to-image models render <em>this</em> street or merely a plausible one. Street and neighborhood names help; GPS coordinates alone do not.
    </div>
  </div>
</div>

<div class='paper-box paper-box--lead' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/failure-footprint.png' alt="Terminal pose of a failed sidewalk robot evaluated against clear-width and accessibility-feature criteria" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Failure Has a Footprint: Rethinking Sidewalk Robot Failure in Public Space</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to HRI 2027.
    </div>
    <div class="paper-desc">
      Defines the terminal footprint as the ground area a failed delivery robot occupies until retrieval and evaluates it against published clear-width thresholds and accessibility features. In 1,000 simulated failures on measured New York footways, stopping in place leaves 55.7% of failures below the ADA clear width, and an access-aware siting policy reduces the share to 18.8%. Across 17,136 km of New York footway, 28.0% of the network has no width-compliant pose under PROWAG.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/popnavshift.png' alt="PopNavShift pipeline from persona records to pedestrian motion profiles, and matched replay of one encounter under three controllers" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">PopNavShift: Stress-Testing Social Navigation Strategies under Population Shift</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to ICRA 2027.
    </div>
    <div class="paper-desc">
      Replays identical physical episodes under different synthetic pedestrian-profile distributions to test whether robot navigation strategies keep their relative ranking. Across eight population conditions and 7,488 matched runs, changing pedestrian time pressure reverses 22.4% of mean pedestrian-delay orderings, compared with 8.6% of robot travel-time orderings.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/hri-design-response.png' alt="Evidence needed to compare model-predicted and observed human responses to robot actions in public HRI releases" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">From Robot Actions to Human Responses: What Can Public HRI Data Support?</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to HRI 2027.
    </div>
    <div class="paper-desc">
      Introduces Design × Response, an evaluation method that compares the model-predicted response change between robot actions with the observed human-response change for the same action pair, response, and population. Applied to seven public HRI releases, it shows that temporal specificity, action comparability, and population alignment provide independent evidence about whether a release can support model–empirical agreement.
    </div>
  </div>
</div>

<div class='paper-box paper-box--lead' data-tags="spatial">
  <div class='paper-box-image'>
    <div><video class="paper-media" data-src="images/worldmodel.mp4" poster="images/worldmodel.png" muted loop playsinline preload="none" aria-label="Six PokeWorld episodes spanning the observability spectrum: low and high drag, light and heavy mass, soft and stiff contact"></video></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">What Can Latent World Models Know? Physical Parameter Identifiability in Multimodal Predictive Representations</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to ICLR 2027.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://tantansir.github.io/latent-world-model-identifiability/">Project Page</a>
      <a class="paper-link" href="https://arxiv.org/abs/2607.27017">arXiv</a>
    </div>
    <div class="paper-desc">
      Asks which physical parameters a latent world model actually recovers in its predictive representation, and which stay structurally unidentifiable however well the model predicts.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="spatial">
  <div class='paper-box-image'>
    <div><video class="paper-media" data-src="images/physical-language.mp4" poster="images/physical-language.png" muted loop playsinline preload="none" aria-label="A probe sweeping a textured surface while audio and acceleration particle streams converge into the frozen response chart"></video></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Beyond Multimodal Alignment: Certifying Physical Language through Response Substitution and Ordered Execution</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to ICLR 2027.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://tantansir.github.io/multimodal-physical-language/">Project Page</a>
      <a class="paper-link" href="https://arxiv.org/abs/2608.19492">arXiv</a>
    </div>
    <div class="paper-desc">
      Defines physical meaning through responses to registered interventions and introduces a certificate that compares independently trained sensor mappings on held-out entities. On Cluster Haptic the same-surface audio–acceleration response distance is 4.5 times smaller than the wrong-surface distance for all 19 test surfaces, and in a controlled elastoplastic system a step-factorized executor generalizes to an unseen action order while a program-level executor is 38.5 times worse than an entity-blind predictor.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="others">
  <div class='paper-box-image'>
    <div><img src='images/Pruning.png' alt="Token pruning calibration" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">When Does Visual Token Pruning Improve Calibration? The Role of Evidence Coverage in MLLMs</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Submitted to AAAI 2027.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://arxiv.org/abs/2604.12035">arXiv</a>
    </div>
    <div class="paper-desc">
      For multimodal LLM confidence, the selection rule matters more than the token budget: coverage-based pruning cuts expected calibration error on POPE with LLaVA-1.5 while holding accuracy, and the kept-set coverage tracks accuracy but not confidence.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="sensing">
  <div class='paper-box-image'>
    <div><img src='images/metro.png' alt="Study area with the eight Qingdao Metro services and 172 stations" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Institutional Workflows and the Observed Geography of Metro Lost-Property Records: Evidence from Qingdao</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span>
    </div>
    <div class="paper-venue">
      Submitted to Journal of Transport Geography.
    </div>
    <div class="paper-links">
      <a class="paper-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7382978">SSRN</a>
    </div>
    <div class="paper-desc">
      Examines 54,658 lost-property postings from the Qingdao Metro between July 2024 and July 2026 to ask where administrative records locate the events they describe. After accounting for station-area characteristics, terminal-only stations post at 8.76 times the rate of ordinary stations and terminal-plus-transfer stations at 21.15 times, consistent with recovery and attribution workflows shaping the observed geography.
    </div>
  </div>
</div>
</div>

<div class="pub-group">
<h3 class="pub-group__title">In Preparation</h3>

<div class='paper-box paper-box--lead' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/roborow-framework.png' alt="RoboROW research framework: urban worlds and road users, executable right of way, and experiments and policy evidence" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">RoboROW: A Right-of-Way Simulation and Policy Toolkit for Urban Service Robots</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      A multi-agent co-simulation framework that translates robot right-of-way policies into spatial access masks, priority rules, motion parameters, and independent safety constraints, coupling JuPedSim pedestrians, SUMO traffic, and a ROS 2, Nav2, and Gazebo stack. The formal design compares nine spatial-allocation policies and 14 priority policies across three urban environments, seven sidewalk widths, and five pedestrian levels of service, with a 19-factor Sobol design estimating a joint deployment-feasibility boundary.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/roboticurban.jpg' alt="Framework for reviewing robotic urbanization in urban ground transportation systems: agents, spaces, and mechanisms" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Robotic Urbanization and the Transformation of Urban Ground Transportation Systems: An Updated Review</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      A PRISMA-informed systematic mapping review of Scopus and Web of Science literature from 2017 to June 2026, with a final synthesis corpus of 347 full texts. Road automation accounts for 88.5% of primary agent codes and simulation or optimization studies for 42.4% of methods, and the Agent-Space-Mechanism-Outcome framework organises the evidence around the urban interfaces where robots move, stop, load, wait, yield, and interact with people.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="robotic">
  <div class='paper-box-image'>
    <div><img src='images/legal-layer-assignment.png' alt="Twenty-one delivery-robot instruments from China and the United States grouped by the street layer they assign the device to: sidewalk, cycle lane, or carriageway" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Legal Classification and the Morphological Selectivity of Delivery Robot Deployment: Comparing China and the United States</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      Codes twenty-one delivery-robot instruments from China and the United States by the layer of the street cross-section each rule assigns the device to, and shows that this assignment decides which dimensions of urban form constrain deployment. In a rule-parameterised feasible network, the same 0.60 m device completes 83% of sampled trips in Beijing’s Yizhuang under a carriageway rule and 33% under Pennsylvania’s sidewalk rule, and across 7,891 grid cells in ten study areas sidewalk coverage predicts where American operators run and, with the opposite sign, which streets Chinese regulators authorise.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="twins sensing">
  <div class='paper-box-image'>
    <div><img src='images/seeing-the-city.png' alt="Study design comparing street-view imagery with existing urban data across paired source conditions" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Seeing the City or Recognizing the Place? What Street-View Imagery Adds Beyond Existing Urban Data in VLM Urban Sensing</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      Compares image-based predictions with existing urban data across seven attributes, five public resources, and three VLMs, using paired source conditions, image replacements, and conflicting records. Existing data matched or exceeded image-only models for road damage, curb ramps, and house price, while images were more informative for building type, building function, and low-rise floor count, with the floor-count advantage rising 5.7 percentage points per doubling of distance to the nearest labelled building.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="sensing twins">
  <div class='paper-box-image'>
    <div><img src='images/same-street-twice.png' alt="One Oakland Street View standpoint photographed over fifteen years, with model perception scores at each visit" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">You Cannot Photograph the Same Street Twice: Reliability Limits in Vision–Language Measurement of Urban Change</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      Uses 4,648 consecutive-epoch Google Street View pairs from 435 standpoints in five US cities to measure how much a VLM perception score changes when the street itself does not. Re-photographing the same street moves a score by 0.80 points on average, equal to 66.5% of the difference between two streets in the same city, while aggregation over hundreds of pairs still recovers a coherent redevelopment signal.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="sensing">
  <div class='paper-box-image'>
    <div><img src='images/urban-appraisal-eeg.png' alt="Stimuli, trial structure, and the structure of urban scene appraisal ratings" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Vision Models Predict Urban Scene Appraisal with Limited Neural Alignment</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      Tests predictive accuracy and neural alignment separately using EEG from 63 adults who rated 56 Berlin street scenes, across seventeen feature spaces. The best representation, DINOv2 ViT-B, reaches 29.6% of the noise-ceiling lower bound and a Gabor energy descriptor is indistinguishable from it, while the same embeddings predict held-out appraisal ratings at up to r = 0.87; the two measures do not track each other across models.
    </div>
  </div>
</div>

<div class='paper-box' data-tags="spatial">
  <div class='paper-box-image'>
    <div><img src='images/equisd.png' alt="Rescaling the supplied world reference, response slopes across eight vision-language models, and training on the scale symmetry" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">Teaching Vision-Language Models to Use the Scale They Are Given: Label-Free Equivariance Training for Metric Physical Reasoning</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, et al.</span>
    </div>
    <div class="paper-venue">
      Manuscript in preparation.
    </div>
    <div class="paper-desc">
      When every world-space quantity in a prompt is rescaled by a common factor, the correct metric answer changes by that factor, but eight vision-language models move only part of the way over four orders of magnitude. EquiSD uses this exact scaling relation as label-free supervision and raises a 3B model’s median response slope from 0.66 to 0.94 with one query per training video.
    </div>
  </div>
</div>

</div>

<div class="pub-group">
<h3 class="pub-group__title">Technical Reports</h3>

<div class='paper-box' data-tags="sensing">
  <div class='paper-box-image'>
    <div><img src='images/blindnav.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text'>
    <div class="paper-title">BlindNav: YOLO+LLM for Real-Time Navigation Assistance for Blind Users</div>
    <div class="paper-authors">
      <span class="author-self">Kaizhen Tan</span><span class="author-other">, Yufan Wang, Yixiao Li, Hanzhe Hong, Nicole Lyu</span>
    </div>
    <div class="paper-venue">
      Technical report, 2025.
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
</div>

<p class="pub-empty" hidden>No publications in this direction yet.</p>

# 💬 Presentations

<ul class="pres-list">
  <li class="pres-item">
    2026.07 - <strong>XXV ISPRS Congress 2026</strong><br>
    UrbanVGGT: Scalable Sidewalk Width Estimation from Street View Images<br>
    <em>Toronto, Canada</em>
  </li>

  <li class="pres-item">
    2025.08 - <strong>Global Smart Cities Summit cum The 4th International Conference on Urban Informatics <a href="https://www.isocui.org/icui2025">(GSCS & ICUI 2025)</a></strong><br>
    Decoding Tourist Perception in Historic Urban Quarters with Multimodal Social Media Data: An AI-Based Framework and Evidence from Shanghai<br>
    <em>Hong Kong Polytechnic University (PolyU), Hong Kong SAR, China</em>
  </li>

  <li class="pres-item">
    2025.07 - <strong>7th Asia Conference on Machine Learning and Computing <a href="https://www.acmlc.org/acmlc2025.html">(ACMLC 2025)</a></strong><br>
    Multimodal Deep Learning for ATCO Command Lifecycle Modeling and Workload Prediction<br>
    <em>Hong Kong SAR, China</em>
  </li>
</ul>

# 📫 Contact
- Email(NYU): kt3275@nyu.edu
- Email(CMU): kaizhent@cmu.edu

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

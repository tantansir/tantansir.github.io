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

Hi! I am Kaizhen Tan (Chinese name: 谭楷蓁). I am currently a master’s student in Artificial Intelligence at **Carnegie Mellon University**. I received my bachelor’s degree in Information Systems from **Tongji University**, where I built a solid foundation in programming, data analysis, and machine learning, complemented by interdisciplinary training in business and organizational systems.

My research sits at the intersection of **Urban Management and Spatial Intelligence**. I aim to build systems that are both spatially intelligent and socially aware, providing computational solutions to make cities more adaptive, inclusive, and human-centric. 

Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, my research agenda is structured around four key topics. Please feel free to contact me if any of these resonate with you, I’d be happy to chat!


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

  /* 卡片主体：柔和边界 + 彩色底 */
  .research-card{
    position: relative;
    background: rgba(255,255,255,0.78);
    overflow: hidden;

    border: none;
    border-radius: 22px;

    padding: 18px 18px 16px 18px;

    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);

    display: flex;
    flex-direction: column;

    /* 外侧柔影 + 内侧高光，让边界更“软” */
    box-shadow:
      0 18px 48px rgba(0,0,0,0.08),
      0 6px 18px rgba(0,0,0,0.06),
      0 1px 0 rgba(255,255,255,0.70) inset,
      0 -1px 0 rgba(0,0,0,0.03) inset;

    transition: transform 180ms ease, box-shadow 180ms ease;
  }

  .research-card:hover{
    transform: translateY(-2px);
    box-shadow:
      0 22px 60px rgba(0,0,0,0.10),
      0 8px 22px rgba(0,0,0,0.07),
      0 1px 0 rgba(255,255,255,0.75) inset,
      0 -1px 0 rgba(0,0,0,0.03) inset;
  }

  /* 彩色光晕层 */
  .research-card::after{
    content:"";
    position:absolute;
    inset:0;
    background:
      radial-gradient(1200px circle at 18% 14%, var(--tint, rgba(99,102,241,0.18)) 0%, rgba(255,255,255,0) 55%),
      radial-gradient(900px circle at 88% 88%, var(--tint2, rgba(16,185,129,0.12)) 0%, rgba(255,255,255,0) 58%);
    pointer-events:none;
  }

  /* 顶部细色条 */
  .research-card::before{
    content:"";
    position:absolute;
    left:0; right:0; top:0;
    height:6px;
    background: linear-gradient(90deg, var(--accent, #6366F1), rgba(255,255,255,0));
    opacity:0.95;
    pointer-events:none;
  }

  /* 内容层级盖住伪元素 */
  .research-card > *{
    position: relative;
    z-index: 1;
  }

  .research-card h4{
    margin: 0 0 12px 0;
    line-height: 1.2;
    font-size: 1.1rem;
    font-weight: 800;
    letter-spacing: 0.2px;
  }

  .research-card h4 .amp{
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans", Arial, sans-serif !important;
    font-weight: inherit;
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

  /* 四张卡分别配色 */
  .research-container.research-grid .research-card:nth-child(1){
    --accent:#6366F1;
    --tint: rgba(99,102,241,0.22);
    --tint2: rgba(56,189,248,0.14);
  }
  .research-container.research-grid .research-card:nth-child(2){
    --accent:#EC4899;
    --tint: rgba(236,72,153,0.20);
    --tint2: rgba(168,85,247,0.12);
  }
  .research-container.research-grid .research-card:nth-child(3){
    --accent:#10B981;
    --tint: rgba(16,185,129,0.18);
    --tint2: rgba(34,211,238,0.12);
  }
  .research-container.research-grid .research-card:nth-child(4){
    --accent:#F59E0B;
    --tint: rgba(245,158,11,0.20);
    --tint2: rgba(251,191,36,0.12);
  }

  @media (max-width: 900px){
    .research-container.research-grid{
      grid-template-columns: 1fr;
      min-height: auto;
    }
  }

  /* 深色模式：去掉方框边界，保留柔和彩色 */
  @media (prefers-color-scheme: dark){
    .research-card{
      background: rgba(20,20,20,0.62);
      border: none;
      box-shadow:
        0 22px 64px rgba(0,0,0,0.42),
        0 10px 26px rgba(0,0,0,0.30),
        0 1px 0 rgba(255,255,255,0.10) inset,
        0 -1px 0 rgba(0,0,0,0.35) inset;
    }
    .research-card p{
      color: rgba(255,255,255,0.75);
    }
    .research-card::after{
      filter: saturate(1.05) brightness(0.9);
      opacity: 0.9;
    }
  }
</style>


<div class="research-container research-grid">

  <div class="research-card">
    <h4>🤖 1. Robotic Urbanism <span class="amp">&amp;</span> Collaborative Governance</h4>
    <p><i>Core Question: How can embodied intelligence serve as a critical mediation layer between the physical and digital worlds so humans can govern and collaborate with these systems at scale, especially in the context of robotics and lightweight urbanization?</i></p>
    <ul>
      <li><b>Robot-Friendly Urban Space:</b> Redesign streets and building interiors for robot operations, setting standards for siting, infrastructure, protocols, and responsibility boundaries.</li>
      <li><b>Embodied Navigation:</b> Vision-based navigation and task execution under real urban constraints, with accessibility-aware routing and compliance with local infrastructure and operational rules.</li>
      <li><b>Low-Altitude Governance:</b> Derive operable air corridors from demand signals, then validate in 3D city models under privacy, noise, crowds, and other effects.</li>
      <li><b>Emerging Urban Devices & Deployment:</b> Study city-scale rollout of robots, low-altitude systems, wearables, and BCI-like devices, focusing on deployment bottlenecks.</li>
      <li><b>Social Acceptance & Ethics:</b> Model how different groups perceive risks and capabilities, guiding interaction design, rollout strategy, and public communication.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🎨 2. Social Sensing <span class="amp">&amp;</span> Human-Environment Interaction</h4>
    <p><i>Core Question: How can multimodal human-centered data translate into actionable insights for urban planning and governance?</i></p>
    <ul>
      <li><b>AI-Enhanced Geospatial Analysis:</b> Use large-scale spatial analytics to link urban form, environment, and mobility with human behavior and public service outcomes.</li>
      <li><b>Pedestrian-Oriented Design:</b> Analyze walking experiences and accessibility barriers, integrating disabled people’s mobility needs into urban governance decisions.</li>
      <li><b>Urban Perception & Visual Aesthetics:</b> Quantify streetscape perception and neighborhood imagery to inform design choices and regeneration priorities.</li>
      <li><b>Socio-Cultural Computing:</b> Incorporate place-based narratives into LLM-enabled applications for communication, interaction, and inclusive governance.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🏙️ 3. Self-Evolving Urban Digital Twins and Agents</h4>
    <p><i>Core Question: How can we build self-evolving urban digital twin that stays continuously updated, hosts agents, and supports sustainable and equitable city governance?</i></p>
    <ul>
      <li><b>Urban Foundation Models:</b> Fuse remote sensing, street-level data, trajectories, IoT, text, and graphs into unified urban representations.</li>
      <li><b>Measurement & Sensing Loops:</b> Develop scalable metrics and updating pipelines, using robots, drones, and wearables as new data sources for continuous urban sensing.</li>
      <li><b>Localization & Mapping:</b> Advance geo-localization and semantic SLAM across point clouds, meshes, and 3D Gaussian representations for interactive 3D cities.</li>
      <li><b>Urban Agents:</b> Build task agents for planning and public services, including map-LLM systems, spatial RAG, policy QA, and travel assistance.</li>
      <li><b>Policy Sandbox & Systems:</b> Use the twin for what-if simulation, risk assessment, and execution checks, supported by efficient retrieval, caching, and rendering.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🚀 4. Spatial Intelligence <span class="amp">&amp;</span> Foundation World Models</h4>
    <p><i>Core Question: How can world models support reliable spatial reasoning and decision-making for physical agents?</i></p>
    <ul>
      <li><b>World Models & Architecture:</b> Study generative, predictive, and representation-learning paradigms for forecasting and planning in the physical world.</li>
      <li><b>Embodied Representations:</b> Unify geometry, semantics, physics, and action into shared representations, with a path toward richer embodied modalities.</li>
      <li><b>Long-term Memory & Self-Evolution:</b> Build lifelong learning mechanisms with stability, forgetting control, and safety constraints for long-horizon autonomy.</li>
      <li><b>Neural-Inspired Reasoning:</b> Improve interpretability and robustness of spatial reasoning, exploring 3D-aware encoders and alternatives to standard transformers.</li>
    </ul>
  </div>
</div>

[//]: # (<div style="text-align: center;">)

[//]: # (  <a href="/assets/CV_Kaizhen TAN.pdf">View My CV</a> /)

[//]: # (  <a href="mailto:wflps20140311@gmail.com">Email</a> /)

[//]: # (  <a href="https://github.com/tantansir">Github</a> /)

[//]: # (  <a href="/images/Wechat.jpg">Wechat</a> /)

[//]: # (  <a href="https://www.linkedin.com/in/kaizhen-tan-b020232b3/">LinkedIn</a>)

[//]: # (</div>)

<style>
  .social-row{
    display:flex;
    justify-content:center;
    gap:16px;
    flex-wrap:wrap;
    margin: 18px 0 6px 0;
  }

  .sbtn{
    --bg:#2d2d2d;
    width:35px;
    height:35px;
    border-radius:16px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    background: var(--bg);
    box-shadow: 0 8px 18px rgba(0,0,0,0.10);
    border: 1px solid rgba(0,0,0,0.08);
    transition: transform 160ms ease, box-shadow 160ms ease;
    text-decoration:none;
    -webkit-tap-highlight-color: transparent;
  }

  .sbtn:hover{
    transform: translateY(-2px);
    box-shadow: 0 12px 24px rgba(0,0,0,0.14);
  }

  .sbtn:active{
    transform: translateY(-1px);
  }

  .sbtn img,
  .sbtn svg{
    width:24px;
    height:24px;
    display:block;
  }

  /* 背景色按品牌来 */
  .s-cv{ --bg:#111; }
  .s-mail{ --bg:#1E88FF; }
  .s-scholar{ --bg:#2F6FE4; }
  .s-github{ --bg:#111; }
  .s-wechat{ --bg:#07C160; }
  .s-xhs{ --bg:#FF2442; }
  .s-linkedin{ --bg:#0A66C2; }

  @media (prefers-color-scheme: dark){
    .sbtn{
      border: 1px solid rgba(255,255,255,0.10);
      box-shadow: 0 14px 34px rgba(0,0,0,0.36);
    }
  }
</style>

<div class="social-row" aria-label="Links">
  <!-- CV -->
  <a class="sbtn s-cv" href="/assets/CV_Kaizhen%20TAN.pdf" aria-label="CV" title="CV">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path fill="#fff" d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8l-6-6zm0 2.5L19.5 10H14V4.5z"/>
      <path fill="#fff" d="M8 13h8v1.7H8V13zm0 3h6v1.7H8V16z"/>
    </svg>
  </a>

  <!-- Email -->
  <a class="sbtn s-mail" href="mailto:wflps20140311@gmail.com" aria-label="Email" title="Email">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path fill="#fff" d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/>
    </svg>
  </a>

  <!-- Google Scholar（Simple Icons 原版） -->
  <a class="sbtn s-scholar" href="https://scholar.google.com/citations?user=JtyjnWYAAAAJ" aria-label="Google Scholar" title="Google Scholar" rel="me noopener noreferrer" target="_blank">
    <img src="https://cdn.simpleicons.org/googlescholar/ffffff" alt="" />
  </a>

  <!-- GitHub（Simple Icons 原版） -->
  <a class="sbtn s-github" href="https://github.com/tantansir" aria-label="GitHub" title="GitHub" rel="me noopener noreferrer" target="_blank">
    <img src="https://cdn.simpleicons.org/github/ffffff" alt="" />
  </a>

  <!-- WeChat（Simple Icons 原版） -->
  <a class="sbtn s-wechat" href="/images/Wechat.jpg" aria-label="WeChat" title="WeChat">
    <img src="https://cdn.simpleicons.org/wechat/ffffff" alt="" />
  </a>

  <!-- Xiaohongshu（Simple Icons 原版） -->
  <a class="sbtn s-xhs" href="https://www.xiaohongshu.com/user/profile/5e2031bc000000000100b761" aria-label="Xiaohongshu" title="Xiaohongshu" rel="me noopener noreferrer" target="_blank">
    <img src="https://cdn.simpleicons.org/xiaohongshu/ffffff" alt="" />
  </a>

  <!-- LinkedIn（Simple Icons 原版） -->
  <a class="sbtn s-linkedin" href="https://www.linkedin.com/in/kaizhen-tan-b020232b3/" aria-label="LinkedIn" title="LinkedIn" rel="me noopener noreferrer" target="_blank">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path fill="#fff" d="M20.45 20.45h-3.56v-5.57c0-1.33-.03-3.04-1.85-3.04-1.85 0-2.13 1.45-2.13 2.95v5.66H9.35V9h3.41v1.56h.05c.47-.9 1.63-1.85 3.35-1.85 3.59 0 4.26 2.36 4.26 5.43v6.31zM5.34 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12zM7.12 20.45H3.56V9h3.56v11.45z"/>
    </svg>
  </a>
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

<style>
  .section-gap{ height: 2px; }
</style>
<div class="section-gap"></div>

# 📖 Education

[//]: # (<div class="edu-item">)

[//]: # (  <img class="edu-logo" src="/assets/nyu.png" alt="NYU" />)

[//]: # (  <div class="edu-content">)

[//]: # (    <div class="edu-top">)

[//]: # (      <strong>New York University</strong>)

[//]: # (    </div>)

[//]: # (    <div class="edu-sub"><em>2026.09 – 2031.05 &#40;expected&#41;</em></div>)

[//]: # (    <div class="edu-sub"><em>Ph.D. in Public Administration</em></div>)

[//]: # (  </div>)

[//]: # (</div>)

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


<style>
  .section-gap1{ height: 10px; }
</style>
<div class="section-gap1"></div>

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

<style>
  .section-gap1{ height: 6px; }
</style>
<div class="section-gap1"></div>

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


<style>
  .edu-item{
    display: flex;
    align-items: center;
    gap: 40px;          /* 这里调大就是间隔更远 */
    margin: 14px 0;
  }
  .edu-logo{
    width: 95px;        /* 需要的话也可以调大 */
    height: 95px;
    object-fit: contain;
    flex: 0 0 auto;
  }
  .edu-content{
    flex: 1 1 auto;
    font-size: 18px;
    line-height: 1.5;
  }

  .edu-top strong{
    font-size: 18px;
  }

  .edu-sub{
    font-size: 15px;
    margin-top: 4px;
  }
</style>


<style>
  .section-gap10{ height: 2px; }
</style>
<div class="section-gap10"></div>

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

[//]: # (### 2027.02, aag2027)

[//]: # (Do we need a robot lane?)

[//]: # (*New York, USA*)

[//]: # ()
[//]: # (### 2026.11, acsp2026)

[//]: # (Do we need a robot lane?)

[//]: # (*Pittsburgh, USA*)
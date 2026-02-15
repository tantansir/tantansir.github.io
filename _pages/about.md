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

Driven by the vision of **harmonizing artificial intelligence with urban ecosystems**, my research agenda is organized around four key areas:


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
    <h4>🤖 1. Embodied Urbanism <span class="amp">&amp;</span> Collaborative Governance</h4>
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
    <h4>🎨 2. Social Sensing <span class="amp">&amp;</span> Human-Environment Interaction</h4>
    <p><i>Core Question: How can local narratives, culture, and human behavior be measured and integrated into models to support urban renewal and governance?</i></p>
    <ul>
      <li><b>AI-Enhanced Geospatial Analysis:</b> Use large-scale spatial analytics to link urban form, environment, and mobility with human behavior and public service outcomes.</li>
      <li><b>Pedestrian-Oriented Design:</b> Analyze walking experiences and accessibility barriers, integrating disabled people’s mobility needs into urban governance decisions.</li>
      <li><b>Urban Perception & Visual Aesthetics:</b> Quantify streetscape perception and neighborhood imagery to inform design choices and regeneration priorities.</li>
      <li><b>Socio-Cultural Computing:</b> Incorporate place-based narratives into LLM-enabled applications for communication, interaction, and inclusive governance.</li>
    </ul>
  </div>

  <div class="research-card">
    <h4>🏙️ 3. Self-Evolving Urban Digital Twins and Agents</h4>
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
    <h4>🚀 4. Spatial Intelligence <span class="amp">&amp;</span> Foundation World Models</h4>
    <p><i>Core Question: How can world models support reliable spatial reasoning and actionable decision-making for physical agents?</i></p>
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
    gap:14px;
    flex-wrap:wrap;
    margin: 18px 0 6px 0;
  }

  .social-row a{
    width:56px;
    height:56px;
    border-radius:18px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    position:relative;
    overflow:hidden;

    box-shadow: 0 10px 22px rgba(0,0,0,0.10);
    border: 1px solid rgba(0,0,0,0.06);
    transform: translateZ(0);
    transition: transform 160ms ease, box-shadow 160ms ease, filter 160ms ease;
    text-decoration:none;
  }

  .social-row a::before{
    content:"";
    position:absolute;
    inset:0;
    background: radial-gradient(circle at 28% 22%, rgba(255,255,255,0.38), rgba(255,255,255,0) 58%);
    opacity: .95;
    pointer-events:none;
  }

  .social-row a::after{
    content:"";
    position:absolute;
    inset:0;
    box-shadow: inset 0 -10px 16px rgba(0,0,0,0.18);
    opacity:.22;
    pointer-events:none;
  }

  .social-row a:hover{
    transform: translateY(-2px);
    box-shadow: 0 14px 30px rgba(0,0,0,0.14);
    filter: saturate(1.05);
  }

  .social-row a:active{
    transform: translateY(-1px) scale(0.99);
  }

  .social-row svg{
    width:24px;
    height:24px;
    fill:#fff;
    position:relative;
    z-index:1;
  }

  .bg-cv{ background: linear-gradient(135deg,#2D2D2D,#0B0B0B); }
  .bg-mail{ background: linear-gradient(135deg,#2F8CFF,#1767FF); }
  .bg-scholar{ background: linear-gradient(135deg,#3C7CFF,#1E4ED8); }
  .bg-github{ background: linear-gradient(135deg,#2A2A2A,#000); }
  .bg-wechat{ background: linear-gradient(135deg,#18D86A,#07C160); }
  .bg-xhs{ background: linear-gradient(135deg,#FF4B61,#FF2442); }
  .bg-linkedin{ background: linear-gradient(135deg,#1B7BFF,#0A66C2); }

  @media (prefers-color-scheme: dark){
    .social-row a{
      border: 1px solid rgba(255,255,255,0.10);
      box-shadow: 0 14px 34px rgba(0,0,0,0.36);
    }
    .social-row a::after{ opacity:.28; }
  }
</style>

<div class="social-row" aria-label="Links">
  <!-- CV -->
  <a class="bg-cv" href="/assets/CV_Kaizhen%20TAN.pdf" aria-label="CV" title="CV">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M6 2h9l3 3v17H6V2zm9 1.5V6h2.5L15 3.5zM8 9h8v2H8V9zm0 4h8v2H8v-2zm0 4h6v2H8v-2z"/>
    </svg>
  </a>

  <!-- Email -->
  <a class="bg-mail" href="mailto:wflps20140311@gmail.com" aria-label="Email" title="Email">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/>
    </svg>
  </a>

  <!-- Google Scholar -->
  <a class="bg-scholar" href="https://scholar.google.com/citations?user=JtyjnWYAAAAJ" aria-label="Google Scholar" title="Google Scholar" rel="me noopener noreferrer" target="_blank">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M12 3 1 9l11 6 9-4.91V17h2V9L12 3zm0 10.5L4 9.5 12 5l8 4.5-8 4z"/>
      <path d="M6 12.7V16c0 1.9 2.7 3.5 6 3.5s6-1.6 6-3.5v-3.3l-6 3.3-6-3.3z"/>
    </svg>
  </a>

  <!-- GitHub -->
  <a class="bg-github" href="https://github.com/tantansir" aria-label="GitHub" title="GitHub" rel="me noopener noreferrer" target="_blank">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M12 .5C5.73.5.5 5.74.5 12.22c0 5.18 3.44 9.58 8.21 11.13.6.11.82-.27.82-.58 0-.29-.01-1.04-.02-2.05-3.34.74-4.04-1.64-4.04-1.64-.55-1.42-1.34-1.8-1.34-1.8-1.09-.77.08-.76.08-.76 1.2.09 1.84 1.26 1.84 1.26 1.07 1.86 2.81 1.32 3.5 1.01.11-.8.42-1.32.76-1.62-2.66-.31-5.47-1.36-5.47-6.05 0-1.34.46-2.44 1.23-3.3-.12-.31-.53-1.57.12-3.27 0 0 1.01-.33 3.3 1.26.96-.27 1.98-.4 3-.41 1.02.01 2.04.14 3 .41 2.29-1.59 3.3-1.26 3.3-1.26.65 1.7.24 2.96.12 3.27.77.86 1.23 1.96 1.23 3.3 0 4.7-2.81 5.74-5.49 6.04.43.38.82 1.13.82 2.28 0 1.64-.02 2.97-.02 3.37 0 .32.22.7.83.58 4.77-1.55 8.2-5.95 8.2-11.13C23.5 5.74 18.27.5 12 .5z"/>
    </svg>
  </a>

  <!-- WeChat -->
  <a class="bg-wechat" href="/images/Wechat.jpg" aria-label="WeChat" title="WeChat">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M9.3 4C5.6 4 2.6 6.5 2.6 9.6c0 1.8 1 3.4 2.7 4.4l-.7 2.2 2.4-1.2c.7.2 1.5.3 2.3.3 3.7 0 6.7-2.5 6.7-5.6S13 4 9.3 4z"/>
      <path d="M14.8 9.2c-3.1 0-5.6 2.1-5.6 4.7s2.5 4.7 5.6 4.7c.6 0 1.2-.1 1.8-.2l2 1-.6-1.9c1.3-.8 2.2-2.1 2.2-3.6 0-2.6-2.5-4.7-5.4-4.7z"/>
      <circle cx="7.7" cy="9.3" r="0.8"/><circle cx="10.5" cy="9.3" r="0.8"/>
      <circle cx="13.4" cy="13.6" r="0.7"/><circle cx="16.2" cy="13.6" r="0.7"/>
    </svg>
  </a>

  <!-- Xiaohongshu -->
  <a class="bg-xhs" href="https://www.xiaohongshu.com/user/profile/5e2031bc000000000100b761" aria-label="Xiaohongshu" title="Xiaohongshu" rel="me noopener noreferrer" target="_blank">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M7.2 8.2h9.6c1.7 0 3.2 1.3 3.2 3.1v2.6c0 3.9-3.2 6.9-8 6.9S4 17.8 4 13.9v-2.6c0-1.8 1.5-3.1 3.2-3.1zm.3 2.2c-.7 0-1.3.5-1.3 1.2v2.3c0 2.6 2.2 4.8 5.8 4.8s5.8-2.2 5.8-4.8v-2.3c0-.7-.6-1.2-1.3-1.2H7.5z"/>
      <path d="M9 6.5c0-.6.5-1.1 1.1-1.1h3.8c.6 0 1.1.5 1.1 1.1S14.5 7.6 13.9 7.6h-3.8C9.5 7.6 9 7.1 9 6.5z"/>
    </svg>
  </a>

  <!-- LinkedIn -->
  <a class="bg-linkedin" href="https://www.linkedin.com/in/kaizhen-tan-b020232b3/" aria-label="LinkedIn" title="LinkedIn" rel="me noopener noreferrer" target="_blank">
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M4.98 3.5C4.98 4.88 3.87 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1 4.98 2.12 4.98 3.5zM0.5 23.5h4V7.5h-4v16zM8 7.5h3.8v2.2h.1c.5-1 1.9-2.2 3.9-2.2 4.2 0 5 2.7 5 6.3v9.7h-4v-8.6c0-2.1 0-4.7-2.9-4.7-2.9 0-3.4 2.2-3.4 4.6v8.7H8v-16z"/>
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
  .section-gap{ height: 8px; }
</style>
<div class="section-gap"></div>

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
    gap: 50px;          /* 这里调大就是间隔更远 */
    margin: 14px 0;
  }
  .edu-logo{
    width: 100px;        /* 需要的话也可以调大 */
    height: 100px;
    object-fit: contain;
    flex: 0 0 auto;
  }
  .edu-content{
    flex: 1 1 auto;
    font-size: 18px;
    line-height: 1.5;
  }

  .edu-top strong{
    font-size: 20px;
  }
  .edu-sub{
    font-size: 16px;
    margin-top: 4px;
  }
</style>

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


<style>
  .section-gap{ height: 10px; }
</style>
<div class="section-gap"></div>

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
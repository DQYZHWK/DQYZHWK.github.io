---
permalink: /
title: ""
excerpt: ""
layout: homepage
author_profile: false
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
{% assign author = site.author %}

<section class="header" id="about-me">
  <div class="header__text">
    <h1 class="name">{{ author.name }}</h1>
    <p class="social">
      <a href="mailto:{{ author.email }}" title="Email"><i class="fas fa-envelope"></i></a>
      <a href="{{ author.googlescholar }}" title="Google Scholar" target="_blank" rel="noopener noreferrer"><i class="ai ai-google-scholar-square"></i></a>
      <a href="https://github.com/{{ author.github }}" title="GitHub" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a>
      <a href="{{ author.orcid }}" title="ORCID" target="_blank" rel="noopener noreferrer"><i class="ai ai-orcid"></i></a>
      <a href="{{ author.twitter }}" title="X / Twitter" target="_blank" rel="noopener noreferrer"><i class="fab fa-twitter"></i></a>
    </p>
    <p>I am currently a Researcher at <strong>Tencent</strong>, where my research focuses on multimodal agents and reinforcement learning, with applications to world models for games and generalist game-playing agents. Prior to joining Tencent, I received my M.S. degree from <a href="https://www.zju.edu.cn/english/" target="_blank" rel="noopener noreferrer">Zhejiang University</a> (2023.09-2026.03) under the supervision of <a href="https://scholar.google.com/citations?user=o_G2qa0AAAAJ" target="_blank" rel="noopener noreferrer">Jingyuan Chen</a>.</p>
    <p>My publications have received <a href="{{ author.googlescholar }}" target="_blank" rel="noopener noreferrer"><img class="badge" alt="citations" src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> on Google Scholar.</p>
  </div>
  <div class="header__photo">
    <img src="{{ author.avatar | relative_url }}" alt="{{ author.name }}">
  </div>
</section>

<section class="section">
  <p>Building on my internship experience with RL-based GUI agents, my current research centers on Multimodal Agents within digital environments, spanning web browsers, OS interfaces (PC/Mobile), and gaming scenarios. I am particularly driven by several core challenges in this field:</p>
  <ul class="interests">
    <li><strong>Long-Horizon Memory:</strong> Enabling agents to efficiently store and retrieve action experiences during extended interactions.</li>
    <li><strong>Human-in-the-Loop Reinforcement Learning:</strong> Incorporating human feedback directly into the online training loop to mitigate the exposure bias that afflicts both pure behavior cloning and conventional RL training, where policies optimized on static demonstrations or unguided rollouts struggle to recover from compounding errors in states they have rarely encountered.</li>
    <li><strong>Model Post-Training:</strong> Consolidating multiple domain-specific expert models into a single unified policy via multi-expert on-policy distillation (OPD), thereby alleviating the gradient conflicts that arise when heterogeneous capabilities are jointly optimized during model consolidation.</li>
    <li><strong>World Model Grounded VLA:</strong> Aligning Vision-Language-Action policies with physical priors from world models, enabling more grounded and generalizable decision-making.</li>
  </ul>
  <p>I am open to collaborations in multimodal understanding and reinforcement learning. If you are recruiting researchers or algorithm engineers, please feel free to contact me at <a href="mailto:{{ author.email }}">{{ author.email }}</a>.</p>
</section>

<section class="section" id="publications">
  <h2>Publications</h2>
  <p class="note"><sup>*</sup>Equal contribution</p>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">IJCAI 2026</span></div>
    <div class="entry__body">
      <a class="entry__title" href="https://ijcai.org/proceedings/2026/238" target="_blank" rel="noopener noreferrer">A<sub>3</sub>B<sub>2</sub>: Adaptive Asymmetric Adapter for Alleviating Branch Bias in Vision-Language Image Classification with Few-Shot Learning</a>
      Yiyun Zhou, Zhonghua Jiang, <strong>Wenkang Han</strong>, Kunxi Li, Mingjing Xu, Chang Yao, Jingyuan Chen<br>
      <em>International Joint Conference on Artificial Intelligence (<strong>IJCAI</strong>)</em>, 2026
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">ACM MM 2025</span></div>
    <div class="entry__body">
      <span class="entry__title">Show and Polish: Reference-Guided Identity Preservation in Face Video Restoration</span>
      <strong>Wenkang Han</strong>, Wang Lin, Jingyuan Chen, et al.<br>
      <em>ACM International Conference on Multimedia (<strong>ACM MM</strong>)</em>, 2025
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">ECML-PKDD 2025</span></div>
    <div class="entry__body">
      <span class="entry__title">Revisiting Applicable and Comprehensive Knowledge Tracing in Large-Scale Data</span>
      Yiyun Zhou, <strong>Wenkang Han</strong>, Jingyuan Chen<br>
      <em>European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (<strong>ECML-PKDD</strong>)</em>, 2025
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">IJCAI 2025</span></div>
    <div class="entry__body">
      <span class="entry__title">Contrastive Cross-Course Knowledge Tracing via Concept Graph Guided Knowledge Transfer</span>
      <strong>Wenkang Han</strong>, Wang Lin, Jingyuan Chen, et al.<br>
      <em>International Joint Conference on Artificial Intelligence (<strong>IJCAI</strong>)</em>, 2025
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">CVPR 2025</span></div>
    <div class="entry__body">
      <span class="entry__title">Towards Transformer-Based Aligned Generation with Self-Coherence Guidance</span>
      Shulei Wang, Wang Lin, Hai Huang, Hanting Wang, Sihang Cai, <strong>Wenkang Han</strong>, Zhou Zhao, et al.<br>
      <em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (<strong>CVPR</strong>)</em>, 2025
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">NeurIPS 2024</span></div>
    <div class="entry__body">
      <span class="entry__title">E<sup>3</sup>: Exploring Embodied Emotion Through A Large-Scale Egocentric Video Dataset</span>
      Wang Lin<sup>*</sup>, Yueying Feng<sup>*</sup>, <strong>Wenkang Han</strong><sup>*</sup>, Tao Jin, Zhou Zhao, Fei Wu, Chang Yao, Jingyuan Chen<br>
      <em>Conference on Neural Information Processing Systems (<strong>NeurIPS</strong>)</em>, 2024
    </div>
  </div>
  <div class="entry entry--pub">
    <div class="entry__aside"><span class="venue-tag">ACL 2024</span></div>
    <div class="entry__body">
      <span class="entry__title">MPCoder: Multi-User Personalized Code Generator with Explicit and Implicit Style Representation Learning</span>
      Zhenlong Dai, Chang Yao, <strong>Wenkang Han</strong>, Jingyuan Chen, et al.<br>
      <em>Annual Meeting of the Association for Computational Linguistics (<strong>ACL</strong>)</em>, 2024
    </div>
  </div>
</section>

<section class="section" id="honors-and-awards">
  <h2>Honors and Awards</h2>
  <ul class="plain-list">
    <li><span class="date">2025.10</span> National Scholarship (Master's, Top 3%)</li>
    <li><span class="date">2021.04</span> The 2020 ICPC Asia-East Continent Final (<strong>EC-Final</strong>), Bronze Medal</li>
    <li><span class="date">2021.04</span> The 2020 ICPC Asia Kunming Regional Contest, Silver Medal</li>
    <li><span class="date">2020.11</span> The 2020 ICPC Asia Nanjing Regional Contest, Bronze Medal</li>
  </ul>
</section>

<section class="section" id="academic-service">
  <h2>Academic Service</h2>
  <ul class="plain-list">
    <li><span class="label">Conference and Journal Reviewer:</span> CVPR 2026, AAAI 2026, ICLR (2026, 2027), ACM TOIS 2026</li>
  </ul>
</section>

<section class="section" id="experience">
  <h2>Experience</h2>
  <div class="entry">
    <div class="entry__aside"><img class="logo" src="{{ '/assets/logo/tencent.svg' | relative_url }}" alt="Tencent"></div>
    <div class="entry__body">
      <span class="entry__title">Tencent</span>
      <em>Researcher</em>, 2026.03 - Present, Shenzhen<br>
      <span class="entry__meta">Research Topics: Generalist Game Agents, Multi-Expert On-Policy Distillation</span>
    </div>
  </div>
  <div class="entry">
    <div class="entry__aside"><img class="logo" src="{{ '/assets/logo/meituan.png' | relative_url }}" alt="Meituan"></div>
    <div class="entry__body">
      <span class="entry__title">Meituan (M17)</span>
      <em>Research Intern</em>, 2025.01 - 2025.08, Beijing<br>
      <span class="entry__meta">Research Topics: Generalist Multimodal Agents, End-to-End Online Reinforcement Learning</span>
    </div>
  </div>
</section>

<section class="section" id="education">
  <h2>Education</h2>
  <div class="entry">
    <div class="entry__aside"><img class="logo logo--emblem" src="{{ '/assets/logo/zju.png' | relative_url }}" alt="Zhejiang University"></div>
    <div class="entry__body">
      <span class="entry__title">Zhejiang University</span>
      <em>M.S.</em>, 2023.09 - 2026.03, Hangzhou<br>
      <span class="entry__meta">Advised by <a href="https://scholar.google.com/citations?user=o_G2qa0AAAAJ" target="_blank" rel="noopener noreferrer">Jingyuan Chen</a></span>
    </div>
  </div>
  <div class="entry">
    <div class="entry__aside"><img class="logo logo--emblem" src="{{ '/assets/logo/zafu_emblem.png' | relative_url }}" alt="Zhejiang A&amp;F University"></div>
    <div class="entry__body">
      <span class="entry__title">Zhejiang A&amp;F University</span>
      <em>B.S.</em>, 2018.09 - 2022.06, Hangzhou
    </div>
  </div>
</section>

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

# About Me

I am currently a Researcher at Tencent, where my research focuses on multimodal agents and reinforcement learning, with applications to world models for games and generalist game-playing agents. Prior to joining Tencent, I received my M.S. degree from Zhejiang University<img src="../assets\logo\zju.png" alt="ZJU" style="height: 1em; vertical-align: middle;"/> (2023.09-2026.03) under the supervision of [Jingyuan Chen](https://scholar.google.com/citations?user=o_G2qa0AAAAJ). My publications have received <a href='https://scholar.google.com/citations?user=6ykuTIYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> on Google Scholar.


Building on my internship experience with RL-based GUI agents, my current research centers on Multimodal Agents within digital environments, spanning web browsers, OS interfaces (PC/Mobile), and gaming scenarios.
I am particularly driven by several core challenges in this field:

* **Long-Horizon Memory**: Enabling agents to efficiently store and retrieve action experiences during extended interactions.

* **Human-in-the-Loop Reinforcement Learning**: Incorporating human feedback directly into the online training loop to mitigate the exposure bias that afflicts both pure behavior cloning and conventional RL training, where policies optimized on static demonstrations or unguided rollouts struggle to recover from compounding errors in states they have rarely encountered.

* **Model Post-Training**: Consolidating multiple domain-specific expert models into a single unified policy via multi-expert on-policy distillation (OPD), thereby alleviating the gradient conflicts that arise when heterogeneous capabilities are jointly optimized during model consolidation.

* **World Model Grounded VLA**: Aligning Vision-Language-Action policies with physical priors from world models, enabling more grounded and generalizable decision-making.

I am open to collaborations in multimodal understanding and reinforcement learning. If you are recruiting researchers or algorithm engineers, please feel free to contact me at [dqyzhwk@gmail.com](mailto:dqyzhwk@gmail.com).




# Publications

* ``IJCAI 2026`` A$_3$B$_2$: Adaptive Asymmetric Adapter for Alleviating Branch Bias in Vision-Language Image Classification with Few-Shot Learning. *Yiyun Zhou, Zhonghua Jiang, **Wenkang Han**, Kunxi Li, Mingjing Xu, Chang Yao, Jingyuan Chen.*

* ``ACM-MM 2025`` Show and polish: reference-guided identity preservation in face video restoration. ***Wenkang Han**, Wang Lin, Jingyuan Chen, et al.*


* ``ECML-PKDD 2025`` Revisiting applicable and comprehensive knowledge tracing in large-scale data. *Yiyun Zhou, **Wenkang Han**, Jingyuan Chen.*

* ``IJCAI 2025`` Contrastive Cross-Course Knowledge Tracing via Concept Graph Guided Knowledge Transfer. ***Wenkang Han**, Wang Lin, Jingyuan Chen, et al.* 


* ``CVPR 2025`` Towards transformer-based aligned generation with self-coherence guidance. *Shulei Wang, Wang Lin, Hai Huang, Hanting Wang, Sihang Cai, **WenKang Han**, Zhou Zhao, et al.* 

* ``NeurIPS 2024`` $E^3$: Exploring Embodied Emotion Through A Large-Scale Egocentric Video Dataset. *Wang Lin, **Wenkang Han**, Yueying Feng, Jingyuan Chen, et al.*

* ``ACL 2024`` Mpcoder: Multi-user personalized code generator with explicit and implicit style representation learning. *Zhenlong Dai, Chang Yao, **WenKang Han**, Jingyuan Chen, et al.*
  
# Honors and Awards
- 2025.10 National Scholarship (master) (Top 3%).
- 2021.4 The 2020 ICPC Asia-East Continent Final (**EC-Final**) Contest, 🥉Bronze Medal.
- 2021.4 The 2020 ICPC Asia Kunming Regional Contest, 🥈Sliver Medal.

- 2020.11 The 2020 ICPC Asia Nanjing Regional Contest, 🥉Bronze Medal.


# Academic Service
- Conference and Journal Reviewer: CVPR 2026, AAAI 2026, ICLR (2026, 2027), ACM TOIS 2026.
  
# Experience
- *2026.03 - Present*, Researcher, Tencent, Shenzhen. Research Topics: Generalist Game Agents, Multi-Expert On-Policy Distillation.
- *2025.01 - 2025.08*, Research Intern, Meituan (M17). Research Topics: Generalist Multimodal Agents, End-to-End Online Reinforcement Learning.

# Education
- *2023.09 - 2026.03*, M.S., Zhejiang University, Hangzhou.
- *2018.09 - 2022.06*, B.S., Zhejiang A&F University, Hangzhou.

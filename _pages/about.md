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
# 💼 About Me

I received my B.S. from Zhejiang A&F University <img src="../assets\logo\zafu.png" alt="ZAFU" style="height: 1.2em; vertical-align: middle;"/>, where I actively participated in ACM competitions and advanced to the 2020 EC-Final. Currently, I am a graduate student (2023.09-2026.03) at Zhejiang University<img src="../assets\logo\zju.png" alt="ZJU" style="height: 1.2em; vertical-align: middle;"/>, advised by [Jingyuan Chen](https://scholar.google.com/citations?user=o_G2qa0AAAAJ). My research focuses on visual generation and multimodal understanding, with <a href='https://scholar.google.com/citations?user=6ykuTIYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> on Google Scholar.


Building on my internship experience with RL-based GUI Agents, my current research centers on Multimodal Agents within digital environments, spanning web browsers, OS interfaces (PC/Mobile), and gaming scenarios.
I am particularly driven by three core challenges in this field:

* **Adaptive Reasoning**: Developing mechanisms to adaptively trigger ``thinking mode`` to minimize redundant computation and enhance efficiency.

* **Long-Horizon Memory**: Enabling agents to efficiently store and retrieve action experiences during extended interactions.

* **Real-Time Responsiveness**: Designing low-latency architectures for high-frequency interaction scenarios, such as video games.

I am open to collaborations in multimodal understanding and reinforcement learning. If you are recruiting researchers or algorithm engineers, please feel free to contact me at [dqyzhwk@gmail.com](mailto:dqyzhwk@gmail.com).




# 📝 Publications 

* ``ACM-MM 2025`` Show and polish: reference-guided identity preservation in face video restoration. **Wenkang Han**, Wang Lin, Jingyuan Chen, et al. 


* ``ECML-PKDD 2025`` Revisiting applicable and comprehensive knowledge tracing in large-scale data. Yiyun Zhou, **Wenkang Han**, Jingyuan Chen.

* ``IJCAI 2025`` Contrastive Cross-Course Knowledge Tracing via Concept Graph Guided Knowledge Transfer. **Wenkang Han**, Wang Lin, Jingyuan Chen, et al. 


* ``CVPR 2025`` Towards transformer-based aligned generation with self-coherence guidance. Shulei Wang, Wang Lin, Hai Huang, Hanting Wang, Sihang Cai, **WenKang Han**, Zhou Zhao, et al. 

* ``NeurIPS 2024`` $E^3$: Exploring Embodied Emotion Through A Large-Scale Egocentric Video Dataset. Wang Lin, **Wenkang Han**, Yueying Feng, Jingyuan Chen, et al.

* ``ACL 2024`` Mpcoder: Multi-user personalized code generator with explicit and implicit style representation learning. Zhenlong Dai, Chang Yao, **WenKang Han**, Jingyuan Chen, et al.
  
# 🏅 Honors and Awards
- 2025.10 National Scholarship (master) (Top 3%).
- 2021.4 The 2020 ICPC Asia-East Continent Final (**EC-Final**) Contest, 🥉Bronze Medal.
- 2021.4 The 2020 ICPC Asia Kunming Regional Contest, 🥈Sliver Medal.

- 2020.11 The 2020 ICPC Asia Nanjing Regional Contest, 🥉Bronze Medal.


# 👨‍🏫 Academic Service
Conference Reviewer
- AAAI 2026, ICLR2026

Journal Reviewer
- TOIS 2026
  
# 📖 Educations
- *2023.09 - 2026.03*, Zhejiang University, Hangzhou.
- *2018.09 - 2022.06*, Zhejiang A&F University, Hangzhou.


# 👨‍💻 Internships
* *2025.01 - 2025.08*, Meituan M17. Topic: Generalist Multi-modal Agent, EndtoEnd Online RL.

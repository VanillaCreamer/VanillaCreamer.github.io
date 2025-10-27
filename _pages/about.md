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

Hello! This is Yuting Liu (刘禹廷 in Chinese). I am a second-year PhD student at the [Software College](http://sc.neu.edu.cn/) of [Northeastern University](http://www.neu.edu.cn/), Shenyang, China. I am fortunate to be advised by [Prof Guibing Guo](https://guoguibing.github.io/cn/) and [Prof Qiang Liu](https://people.ucas.edu.cn/~qiangliu?language=en). Before that, I earned my B.E. degree in 2022 at the same institute. I am honored to work closely with [Dr. Jinghao Zhang](https://scholar.google.com/citations?user=2yXhkbsAAAAJ&hl=en) and [Ph.D Student Yizhou Dang](https://kinggugu.github.io/). 

My research interests include multimodal recommendation systems (RS) and personalized large language models (LLM). Please feel free to contact me by email if you have any questions or are seeking collaborations.


# 🔥 News
- *2025.10*: &nbsp;🏆 I have just been awarded the National Scholarship!
- *2025.05*: &nbsp;🎉 One paper is accepted by ACL 2025!
- *2025.04*: &nbsp;🔊 We released an [Awesome-Personalized-LLMs](https://github.com/VanillaCreamer/Awesome-Personalized-LLMs) repository for personalized large language models papers.
- *2025.04*: &nbsp;🎉 One paper is accepted by SIGIR 2025!
- *2025.01*: &nbsp;🎉 Two papers are accepted by DASFAA 2025!
- *2025.01*: &nbsp;🎉 One paper is accepted by WWW 2025!
- *2024.12*: &nbsp;🎉 One paper is accepted by ICASSP 2025!
- *2024.12*: &nbsp;🎉 Four papers are accepted by AAAI 2025!
- *2024.11*: &nbsp;🎉 One paper is accepted by TOIS!
- *2024.09*: &nbsp;🔊 We released a survey on data augmentation for sequential recommendation
- *2024.07*: &nbsp;🎉 One paper is accepted by RecSys 2024!
- *2024.06*: &nbsp;🎉 One paper is accepted by KBS!
- *2024.05*: &nbsp;🎉 One paper is accepted by ACL 2024!
- *2022.06*: &nbsp;🎓 I graduated from NEU!

# 📝 Publications 

† indicates the corresponding author.

### Surveys

- **\[Arxiv 2024\]** Data Augmentation for Sequential Recommendation: A Survey. ([Paper](https://arxiv.org/pdf/2409.13545),[Code](https://github.com/KingGugu/DA-CL-4Rec))  
  Yizhou Dang, Enneng Yang, **Yuting Liu**, Guibing Guo†, Linying Jiang, Xingwei Wang†, Jianzhe Zhao

### Research Papers

- **\[ACL 2025\]** Stealthy attack on large language model based recommendation. ([Paper](https://aclanthology.org/2024.acl-long.318/), [Code](https://github.com/CRIPAC-DIG/RecTextAttack))  
  Jinghao Zhang, **Yuting Liu**, Wenjie Wnag, Qiang Liu, Shu Wu, Liang Wang, Tat-Seng Chua

- **\[SIGIR 2025\]** Data Augmentation as Free Lunch: Exploring the Test-Time Augmentation for Sequential Recommendation. ([Paper](https://arxiv.org/abs/2504.04843), [Code](https://github.com/KingGugu/TTA4SR))  
  Yizhou Dang, **Yuting Liu**, Enneng Yang, Minhan Huang, Guibing Guo, Jianzhe Zhao, Xingwei Wang

- **\[DASFAA 2025\]** Towards Unified Modeling for Positive and Negative Preferences in Sign-aware Recommendation. (Oral)  
  **Yuting Liu**, Yizhou Dang, Yuliang Liang, Qiang Liu, Guibing Guo, Jianzhe Zhao, Xingwei Wang

- **\[DASFAA 2025\]** Self-supervised Hierarchical Representation for Medication Recommendation. (Oral)  
  Yuliang Liang, **Yuting Liu**, Yizhou Dang, Enneng Yang, Guibing Guo, Wei Cai, Jianzhe Zhao, Xingwei Wang

- **\[WWW 2025\]** Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation. (Oral)  
  Chu Zhao, Enneng Yang, Yuliang Liang, Pengxiang Lan, **Yuting Liu**, Jianzhe Zhao, Guibing Guo, Xingwei Wang

- **\[ICASSP 2025\]** Harnessing Content and Structure in ID for Multimodal Recommendation. Just Accepted.  
  **Yuting Liu**, Enneng Yang, Yizhou Dang, Qiang Liu, Yuliang Liang, Guibing Guo, Linying Jiang†, Xingwei Wang

- **\[AAAI 2025\]** CoRA: Collaborative Information Perception by Large Language Model's Weights for Recommendation. (Oral ~20%).  
  **Yuting Liu**, Jinghao Zhang, Yizhou Dang, Yuliang Liang, Qiang Liu, Guibing Guo†, Jianzhe Zhao, Xingwei Wang
  
- **\[AAAI 2025\]** Advancing Large Language Model Fine-Tuning: An Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion. Just Accepted.  
  Pengxiang Lan, Enneng Yang, **Yuting Liu**, Guibing Guo†, Jianzhe Zhao, Xingwei Wang
  
- **\[AAAI 2025\]** Augmenting Sequential Recommendation with Balanced Relevance and Diversity. Just Accepted.  
  Yizhou Dang, Jiahui Zhang, **Yuting Liu**, Enneng Yang, Yuliang Liang, Guibing Guo†, Jianzhe Zhao, Xingwei Wang

- **\[AAAI 2025\]** Multiple Purchase Chains with Negative Transfer Elimination for Multi-Behavior Recommendation. Just Accepted.  
  Shuwei Gong, **Yuting Liu**, Yizhou Dang, Guibing Guo†, Jianzhe Zhao, Xingwei Wang

- **\[TOIS 2024\]** Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences. ([Paper](https://dl.acm.org/doi/10.1145/3706633),[Code](https://github.com/KingGugu/GFEraser))  
  Yizhou Dang, **Yuting Liu**, Enneng Yang, Guibing Guo†, Linying Jiang, Jianzhe Zhao, Xingwei Wang

- **\[RecSys 2024\]** Repeated Padding for Sequential Recommendation. ([Paper](https://arxiv.org/abs/2403.06372),[Code](https://github.com/KingGugu/RepPad))  
  Yizhou Dang, **Yuting Liu**, Enneng Yang, Guibing Guo, Linying Jiang, Xingwei Wang†, Jianzhe Zhao†

- **\[ACL 2024\]** Stealthy attack on large language model based recommendation. ([Paper](https://aclanthology.org/2024.acl-long.318/), [Code](https://github.com/CRIPAC-DIG/RecTextAttack))  
  Jinghao Zhang, **Yuting Liu**, Qiang Liu, Shu Wu†, Guibing Guo, and Liang Wang

- **\[KBS 2024\]** Video and audio are images: A cross-modal mixer for original data on video–audio retrieval. ([Paper](https://www.sciencedirect.com/science/article/pii/S095070512400710X), [Code](https://github.com/Alexius233/Video-and-Audio-are-Images))  
   Zichen Yuan, Qi Shen, Bingyi Zheng, **Yuting Liu**†, Linying Jiang, Guibing Guo†

- **\[ECML-PKDD 2022\]** Bi-directional Contrastive Distillation for Multi-behavior Recommendation. ([Paper](https://link.springer.com/chapter/10.1007/978-3-031-26387-3_30))  
  Yabo Chu, Enneng Yang, Qiang Liu, **Yuting Liu**, Linying Jiang, Guibing Guo

# 📖 Educations
- *2024.09 - now*, Ph.D. student in Software Engineering, Northeastern University, Shenyang, China.
- *2022.09 - 2024.06*, Master in Software Engineering, Northeastern University, Shenyang, China.
- *2018.09 - 2022.06*, Bachelor in Software Engineering, Northeastern University, Shenyang, China.

# 🎖 Honors and Awards
- *2025* National Scholarship for Graduate Student
- *2023* First-Class Scholarship from NEU for Graduate Student
- *2022* Outstanding Graduate of Northeastern University
- *2022* Huawei Smart Base Scholarship
- *2021* Northeastern University Cai Guanshen Scholarship
- *2019,2020,2021,2022* Outstanding Student of NEU

# 💻 Service
- Conference Reviewers:
  - AAAI 2026
  - The Web Conference 2025
  - IJCNN 2025
  - ACM KDD 2024
  - The Web Conference 2024
- Journal Reviewers:
  - ACM Transactions on Recommender Systems (TORS)
  - Electronic Commerce Research and Applications (ECRA)
  - Knowledge-based Systems (KBS)

# 🖥️ Internship

- Research Intern at [Ant Group](https://github.com/AntResearchNLP), mentored by [Jian Guan](https://jianguanthu.github.io/)


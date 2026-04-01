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

😎 Hi, I am **Zhenyu Li (李振宇)**, currently a Ph.D. student in Computer Science and Technology at Tsinghua University, advised by Prof. [Jianyong Wang](https://dbgroup.cs.tsinghua.edu.cn/wangjy/). Prior to that, I received my B.S. degree from Tsinghua University in 2021.

My primary research focuses on enhancing the reasoning and agentic capabilities of large language models:
- **Native Agentic Model**: Equip LLMs with intrinsic agentic capabilities such as instruction following, multi-step planning, and complex tool orchestration, towards models that can autonomously handle diverse real-world tasks.
- **Agent RL**: Extend reinforcement learning to open-ended, hard-to-verify agent scenarios by designing effective reward mechanisms (e.g., rubric-based evaluation), improving agent performance in deep research and creative design.
- **Long-Context & Efficient Architecture**: Extend LLMs' long-context capabilities while designing efficient attention mechanisms and in-context updatable architectures for test-time learning.


# 📖 Educations
- [2021.09-Present] Ph.D. student, Tsinghua University (Advisor: Prof. Jianyong Wang)
- [2017.09-2021.07] B.S. Tsinghua University (Outstanding Graduate of the Department)


# 🔥 News
- 🎉 [2026.02.16]: **Seed 2.0** made its debut in the LM Arena rankings, securing **6th** place in the Text Arena and **3rd** place in the Vision Arena respectively ! 🎉🎉🎉
- 🔥 [2026.02.14]: We released **Seed 2.0**. It is a powerful unified model with comprehensive capabilities surpassing Gemini 3 Pro with extreme superior agent capabilities.
As a contributor, I am responsible for **deep research ability** (DeepConsult 61.1, DeepResearchBench 53.3, ResearchRubrics 50.7), which has been greatly improved compared to version 1.8. More details check the [model card](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf).
- 🚀 [2026.02]: [**Doubao Super Mode (豆包超能模式)**](https://www.doubao.com) is now fully available to all users! It is a powerful AI agent that autonomously handles complex tasks through multi-tool collaboration — integrating web browsing, multi-round search, code execution, data analysis, file processing, and multimodal content generation — supporting a wide range of scenarios including deep research, report writing, coding assistance, travel planning, and creative design. As a key contributor, I am primarily responsible for the **reinforcement learning (RL) pipeline** that powers its agentic capabilities.
- 🌟 [2025.12.18]: Our team is releasing **Seed1.8**, a model designed for generalized real-world agency. It supports text and image inputs and with its powerful multimodal processing capabilities, it demonstrates good performance across various complex application scenarios such as information retrieval, coding, Graphical User Interface (GUI) interaction. More details check the [model card](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/research/Seed-1.8-Modelcard.pdf).
- 🎉 [2025.05]: [FocusLLM](https://aclanthology.org/2025.acl-long.1500/) has been accepted by **ACL 2025 Main**. A framework for extending LLM context length through dynamic condensing.
- 🎉 [2025.05]: [Negative Matters](https://arxiv.org/abs/2509.00842) has been accepted by **ACL 2025 Main**.
- 🎉 [2025.05]: [Maximum Score Routing](https://aclanthology.org/2025.findings-acl.653/) has been accepted by **ACL 2025 Findings**.
- 🎉 [2024.07]: [UniMem](https://openreview.net/forum?id=gQAEGSGVnN) has been accepted by **COLM 2024**.
- 🎉 [2023.12]: [FlexKBQA](https://arxiv.org/abs/2308.12060) has been accepted by **AAAI 2024 (Oral, Top 2%)**.
- 🎉 [2023.11.23] We released the [XAgent](https://github.com/OpenBMB/XAgent) v1.0.0! 🎉🎉🎉



# 💌 Projects
- [XAgent](https://github.com/OpenBMB/XAgent): **An Autonomous Agent for Complex Task Solving.** ![Github stars](https://img.shields.io/github/stars/OpenBMB/XAgent.svg)


# 📝 Selected Publications 
- **Seed 2.0 Model Card: Towards Intelligence Frontier for Real-World Complexity** \
 Seed Team \
 Model card 2026, [[Paper](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf)]
- **Seed 1.8 Model Card: Towards Generalized Real-World Agency** \
  Seed Team \
  Model card 2025, [[Paper](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/research/Seed-1.8-Modelcard.pdf)]
- **Efficient Attention Mechanisms for Large Language Models: A Survey** \
  Yutao Sun\*, <i>**Zhenyu Li\***</i>, Yike Zhang\*, Tengyu Pan\*, Bowen Dong\*, Yuyi Guo, Jianyong Wang \
  Under Review (Cell Patterns), [[Paper](https://arxiv.org/abs/2507.19595)]
- **FocusLLM: Precise Understanding of Long Context by Dynamic Condensing** \
  <i>**Zhenyu Li**</i>, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang \
  ACL 2025 Main, [[Paper](https://aclanthology.org/2025.acl-long.1500/)]
- **Negative Matters: Multi-Granularity Hard-Negative Synthesis and Anchor-Token-Aware Pooling for Enhanced Text Embeddings** \
  Tengyu Pan, Zhichao Duan, <i>**Zhenyu Li**</i>, Bowen Dong, Ning Liu, Xiuxing Li, Jianyong Wang \
  ACL 2025 Main, [[Paper](https://arxiv.org/abs/2509.00842)]
- **Maximum Score Routing For Mixture-of-Experts** \
  Bowen Dong, Yilong Fan, Yutao Sun, <i>**Zhenyu Li**</i>, Tengyu Pan, Xun Zhou, Jianyong Wang \
  ACL 2025 Findings, [[Paper](https://aclanthology.org/2025.findings-acl.653/)]
- **UniMem: Towards a Unified View of Long-Context Large Language Models** \
  Junjie Fang, Likai Tang, Hongzhe Bi, Yujia Qin, Si Sun, <i>**Zhenyu Li**</i>, Haolun Li, Yongjian Li, Xin Cong, Yankai Lin, Yukun Yan, Xiaodong Shi, Sen Song, Zhiyuan Liu, Maosong Sun \
  COLM 2024, [[Paper](https://openreview.net/forum?id=gQAEGSGVnN)]
- **FlexKBQA: A Flexible LLM-Powered Framework for Few-Shot Knowledge Base Question Answering** \
  <i>**Zhenyu Li**</i>, Sunqi Fan, Yu Gu, Xiuxing Li, Zhichao Duan, Bowen Dong, Ning Liu, Jianyong Wang \
  AAAI 2024 (Oral, Top 2%), [[Paper](https://arxiv.org/abs/2308.12060)]
- **Optimization Techniques for Unsupervised Complex Table Reasoning via Self-Training Framework** \
  <i>**Zhenyu Li**</i>, Xiuxing Li, Sunqi Fan, Jianyong Wang \
  IEEE Transactions on Knowledge and Data Engineering (TKDE), [[Paper](https://arxiv.org/abs/2212.10097)]
- **Toward a Unified Framework for Unsupervised Complex Tabular Reasoning** \
  <i>**Zhenyu Li**</i>, Xiuxing Li, Zhichao Duan, Bowen Dong, Ning Liu, Jianyong Wang \
  ICDE 2023, [[Paper](https://arxiv.org/abs/2212.10097)]
- **Effective Few-Shot Named Entity Linking by Meta-Learning** \
  Xiuxing Li\*, <i>**Zhenyu Li\***</i>, Zhengyan Zhang, Ning Liu, Haitao Yuan, Wei Zhang, Zhiyuan Liu, Jianyong Wang \
  ICDE 2022, [[Paper](https://ieeexplore.ieee.org/document/9835266/)]

> Full paper list refer to [google scholar](https://scholar.google.com/citations?user=v0IDKw4AAAAJ&hl=zh-CN).

# 🎖 Honors and Awards
- [2024] Comprehensive Excellence Scholarship, Tsinghua University
- [2023] Comprehensive Excellence Scholarship, Tsinghua University
- [2022] Comprehensive Excellence Scholarship, Tsinghua University
- [2021] Outstanding Graduate of the Department of Computer Science, Tsinghua University
- [2021] National Encouragement Scholarship
- [2020] First Prize of Hua Luogeng Mathematical Contest in Modeling, Tsinghua University (Top 3%)
- [2019] Academic & Social Work Excellence Scholarship, Tsinghua University
- [2018] Second Prize of the Physics Competition for College Students in Parts of China


# 💻 Work Experience
- [2025.9-present] Bytedance-Seed Intern (Agent Group, supervised by Dr. [Yujia Qin](https://yujia-qin.github.io/))
- [2025.6-2025.9] Bytedance-Seed Intern (Pretrain Group, supervised by Ke Shen)
- [2024.8-2025.4] Microsoft Research Asia, NLC Group Intern (Mentor: Dr. [Li Dong](https://www.microsoft.com/en-us/research/people/lidong1/))
- [2023.9-2024.2] Tsinghua University, THUNLP Group Research Collaboration (Advisor: Prof. [Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/))

# 🎓 Teaching Experience
- [2021.09-Present] Undergraduate Counselor, Tsinghua University (12·9 Counselor Scholarship)
- [2022.01-2023.12] Teaching Assistant of Software Engineering, Tsinghua University

# 📚 Academic Services
- Serving as a reviewer of ACL 2025, ICLR 2026

# 💡 Lifestyle

- My hobbies include but are not limited to 🎤 singing, 🏸 badminton and 🥏 frisbee.

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

I am Haoyu Wang, currently a part-time Ph.D. student at College of Computing and Data Science, Nanyang Technological University, Singapore, supervised by [Prof. Bo An](https://personal.ntu.edu.sg/boan/), and an AI Researcher at the 2050 Research Lab, Skywork AI. I received my Bachelor degree of Computer Science and Technology from Beijing University of Posts and Telecommunications in June 2025.

I am a research engineer for **long-horizon agents**, from the models underneath to the applications on top. I post-train models end to end (data, training and evaluation) across reasoning, audio-visual generation and multimodal understanding; build the runtime that keeps agents working for hours; design evaluations for extended tasks; and ship agents into real applications, from SurveyGO to Skywork's products. My work started from long-context processing (LLM×MapReduce) and is heading toward healthcare, where agents must be observable, auditable and safe to authorize.

# 🔥 News
- *2026.09*: &nbsp;🎉🎉 LLM×MapReduce-V2 is accepted by *Journal of Computer Science and Technology (JCST)* ([DOI](https://doi.org/10.1007/s11390-026-6037-8)).
- *2025.04*: &nbsp;🎉🎉 Release LLMxMapReduce-V2 in [arxiv](https://arxiv.org/abs/2504.05732) and [Github](https://github.com/thunlp/LLMxMapReduce), an extremely-long article generation algorithm for survey writing. You could try it in [SurveyGO](https://surveygo.modelbest.cn/)!

# 📝 Publications 

## ⌛️ 2026
- <span class="badge">JCST</span>
[LLM$\times$MapReduce-V2: Entropy-Driven Convolutional Test-Time Scaling for Generating Long-Form Articles from Extremely Long Resources](https://doi.org/10.1007/s11390-026-6037-8)
**Haoyu Wang**, Yujia Fu, Zhu Zhang, Shuo Wang, Zirui Ren, Xiaorong Wang, Zhili Li, Chaoqun He, Bo An, Zhiyuan Liu, Maosong Sun
[![](https://img.shields.io/badge/arXiv-2504.05732-b31b1b)](https://arxiv.org/abs/2504.05732)
[![](https://img.shields.io/github/stars/thunlp/LLMxMapReduce?style=social&label=Code+Stars)](https://github.com/thunlp/LLMxMapReduce)

- <span class="badge">Preprint</span>
[Organizing Intelligence Over Time: Human–AI Collaboration as Joint Cognitive Development](https://doi.org/10.20944/preprints202609.1092.v1)
Zhiyu Yang, **Haoyu Wang**, Hanqing Wang, Hao Yang, Xupeng Zhang

## ⌛️ 2025
- <span class="badge">ACL 2025</span>
[LLM$\times$MapReduce: Simplified Long-Sequence Processing using Large Language Models](https://aclanthology.org/2025.acl-long.1341)
Zihan Zhou, Chong Li, Xinyi Chen, Shuo Wang, Yu Chao, Zhili Li, **Haoyu Wang**, Qi Shi, Zhixing Tan, Xu Han, Xiaodong Shi, Zhiyuan Liu, Maosong Sun
[![](https://img.shields.io/github/stars/thunlp/LLMxMapReduce?style=social&label=Code+Stars)](https://github.com/thunlp/LLMxMapReduce)

- <span class="badge">EMNLP 2025 Demo</span>
[LLM$\times$MapReduce-V3: Enabling Interactive In-Depth Survey Generation through a MCP-Driven Hierarchically Modular Agent System](https://aclanthology.org/2025.emnlp-demos.51)
Yu Chao, Siyu Lin, Xiaorong Wang, Zhu Zhang, Zihan Zhou, **Haoyu Wang**, Shuo Wang, Jie Zhou, Zhiyuan Liu, Maosong Sun
[![](https://img.shields.io/github/stars/thunlp/LLMxMapReduce?style=social&label=Code+Stars)](https://github.com/thunlp/LLMxMapReduce)

## ⌛️ 2024
- <span class="badge">ACL 2024</span>
[UltraLink: An Open-Source Knowledge-Enhanced Multilingual Supervised Fine-tuning Dataset.](https://arxiv.org/abs/2402.19142)
**Haoyu Wang**, Shuo Wang, Yukun Yan, Xujia Wang, Zhiyu Yang, Yuzhuang Xu, Zhenghao Liu, Liner Yang, Ning Ding, Xu Han, Zhiyuan Liu, Maosong Sun
[![](https://img.shields.io/badge/Source%20Code-ffffff?logo=github&style=social)](https://github.com/OpenBMB/UltraLink)

- <span class="badge">CCL 2024</span>
[SpanCS: Span-Level Code-Switching for Cross-Lingual Program Synthesis](https://aclanthology.org/2024.ccl-1.1/)
Qingfu Zhu, Shiqi Zhou, Shuo Wang, Zhiming Zhang, **Haoyu Wang**, Qiguang Chen, Wanxiang Che

- <span class="badge">arxiv preprint</span>
[OMGEval: An Open Multilingual Generative Evaluation Benchmark for Large Language Models](https://arxiv.org/abs/2402.13524)
Yang Liu, Meng Xu, Shuo Wang, Liner Yang, **Haoyu Wang**, Zhenghao Liu, Cunliang Kong, Yun Chen, Yang Liu, Maosong Sun, Erhong Yang
[![](https://img.shields.io/badge/Source%20Code-ffffff?logo=github&style=social)](https://github.com/blcuicall/OMGEval)

- <span class="badge">WWW 2024</span><span style="color:red;">(Oral)</span>
[Federated Heterogeneous Graph Neural Network for Privacy-preserving Recommendation](https://dl.acm.org/doi/10.1145/3589334.3645535)
Bo Yan, Yang Cao, **Haoyu Wang**, Wenchuan Yang, Junping Du, Chuan Shi
[![](https://img.shields.io/badge/Source%20Code-ffffff?logo=github&style=social)](https://github.com/BUPT-GAMMA/FedHGNN)

# 🛠 Projects
- **Perdura** (creator, sole developer; open-source release in preparation): An agent that runs on your own computer, takes on long-running jobs and delivers results with the models you choose. Agents act by writing Python in a resident process, so working state lives in the process rather than the context window; durable state is committed to disk apart from the replaceable execution, so jobs resume after restarts. Against Codex, Claude Code, Hermes and OpenClaw on Sentinel, ToolMaze, BEAM and WildClaw with two models, it places in the top two in all eight settings at the lowest total cost.
- [**Signetum**](https://github.com/R0k1e/Signetum): One Skill that makes coding agents deliver reliably: decisions recorded once, changes validated against the exact source with the repository's own commands, and every delivery inspectable.

# 🎖 Honors and Awards
- *2025.05* Outstanding Graduate Award of Beijing University of Posts and Telecommunications
- *2024.12* National Scholarship (Undergraduate) (Top 1%). 

# 📖 Educations
- *2025.08 - Present*, Part-time Ph.D., College of Computing and Data Science, Nanyang Technological University, supervised by [Prof. Bo An](https://personal.ntu.edu.sg/boan/).
- *2021.09 - 2025.06*, B.S, School of Computer Science and Technology (National Demonstration Software College), Beijing University of Posts and Telecommunications.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.08 - Present*, [2050 Research Lab, Skywork AI](https://skywork.ai/), Singapore.
- *2024.04 - 2025.05*, [ModelBest & OpenBMB](https://modelbest.cn/), China.
- *2023.11 - 2024.04*, [THUNLP, Tsinghua University](http://nlp.csai.tsinghua.edu.cn/), China.
- *2023.03 - 2023.12*, [GAMMA Lab, BUPT](https://github.com/BUPT-GAMMA), China.

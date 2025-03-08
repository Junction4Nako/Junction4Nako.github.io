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

# About Me
Hi! This is Zejun Li. I am currently a Ph.D. candidate at Fudan Univeristy, where I am fortunate to be advised by Prof. [Zhongyu Wei](https://scholar.google.com/citations?user=AjLDxxgAAAAJ). I am a member of the [Fudan Data Intelligence and Social Computing (Fudan DISC) lab](http://fudan-disc.com/) and the Fudan NLP group. Previously, I had the opportunity to visit the UCSB (University of California, Santa Barbara) NLP group, where I was worked with Prof. [William Wang](https://sites.cs.ucsb.edu/~william/).

My research focuses on multi-modal learning across vision and language, particularly:
- Construction and Evaluation of Large Multi-modal Models (LMMs)
- Exploring Visually-enhanced Reasoning abilities in LMMs
- Vision-language pre-training

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025</div><img src='images/vocot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VoCoT: Unleashing Visually-Grounded Multi-Step Reasoning in Large Multi-Modal Models](https://arxiv.org/abs/2405.16919)

**Zejun Li\***, Ruipu Luo*, Jiwen Zhang, Minghui Qiu, Xuanjing Huang, Zhongyu Wei.

[**GitHub Project**](https://github.com/RupertLuo/VoCoT) [**Data**](https://huggingface.co/datasets/luoruipu1/VoCoT/) [**Model**](https://huggingface.co/luoruipu1/Volcano-7b/tree/main)
- We present VoCoT, a multi-modal interleaved reasoning CoT format for MLLM.
- We construct a SFT dataset to enable LMMs to reason with VoCoT!
- We construct VolCano, a VoCoT-enhanced LMM, which is able to perform reasoning with visually-grounded and highly explainable thoughts!
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/reform.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reform-eval: Evaluating large vision language models via unified re-formulation of task-oriented benchmarks"](https://arxiv.org/pdf/2310.02569)

**Zejun Li\***, Ye Wang*, Mengfei Du*, Qingwen Liu*, Binhao Wu*, Jiwen Zhang*, et al.

[**Benchmark Page**](https://github.com/FudanDISC/ReForm-Eval)
- A simple yet effective method to transform task-oriented benchmarks to formats that are compatible to evaluate LMMs based on open-ended generation.
- Please also see [EmbSpatial-Bench](https://github.com/mengfeidu/EmbSpatial-Bench) for a benchmark dedicated for the diagnosis of the main limitation of current LMMs, namely spatial reasoning.
</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

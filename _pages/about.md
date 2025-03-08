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

[\[**GitHub Project**\]](https://github.com/RupertLuo/VoCoT) [\[**Data**\]](https://huggingface.co/datasets/luoruipu1/VoCoT/) [\[**Model**\]](https://huggingface.co/luoruipu1/Volcano-7b/tree/main)
- We present VoCoT, a multi-modal interleaved reasoning CoT format for MLLM.
- We construct a SFT dataset to enable LMMs to reason with VoCoT!
- We construct VolCano, a VoCoT-enhanced LMM, which is able to perform reasoning with visually-grounded and highly explainable thoughts!
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/reform.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reform-eval: Evaluating large vision language models via unified re-formulation of task-oriented benchmarks](https://arxiv.org/pdf/2310.02569)

**Zejun Li\***, Ye Wang*, Mengfei Du*, Qingwen Liu*, Binhao Wu*, Jiwen Zhang*, et al.

[\[**Benchmark Page**\]](https://github.com/FudanDISC/ReForm-Eval)
- An effective method to transform task-oriented benchmarks to formats that are compatible to evaluate LMMs based on open-ended generation.
- Please also see [EmbSpatial-Bench](https://github.com/mengfeidu/EmbSpatial-Bench) for a benchmark dedicated for the diagnosis of the main limitation of current LMMs, namely spatial reasoning.
</div>
</div>


- [Unifying Cross-Lingual and Cross-Modal Modeling Towards Weakly Supervised Multilingual Vision-Language Pre-training](https://aclanthology.org/2023.acl-long.327.pdf). **Zejun Li**, Zhihao Fan, Jingjing Chen, Qi Zhang, Xuanjing Huang, Zhongyu Wei, **ACL 2023**.
- [MVPTR: Multi-Level Semantic Alignment for Vision-Language Pre-Training via Multi-Stage Learning](https://arxiv.org/pdf/2201.12596). **Zejun Li**, Huaixiao Tou, Jingjing Chen, Zhongyu Wei, Xuanjing Huang. **ACM MM 2022**.
- [An Unsupervised Sampling Approach for Image-Sentence Matching Using Document-Level Structural Information](https://ojs.aaai.org/index.php/AAAI/article/view/17573/17380). **Zejun Li**, Zhongyu Wei, Zhihao Fan, Haijun Shan, Xuanjing Huang. **AAAI 2021**.
- [Unifying Local and Global Knowledge: Empowering Large Language Models as Political Experts with Knowledge Graphs](https://dl.acm.org/doi/10.1145/3589334.3645616). Xinyi Mou, **Zejun Li**, Hanjia Lyu, Jiebo Luo, Zhongyu Wei. **WWW 2024**.
- [EmbSpatial-Bench: Benchmarking Spatial Understanding for Embodied Tasks with Large Vision-Language Models](https://arxiv.org/abs/2406.05756). Mengfei Du\*, Binhao Wu\*, **Zejun Li**, Xuanjing Huang, Zhongyu Wei. **ACL 2024**.
- [DELAN: Dual-Level Alignment for Vision-and-Language Navigation by Cross-Modal Contrastive Learning](https://arxiv.org/abs/2404.01994). Mengfei Du\*, Binhao Wu\*, Jiwen Zhang, Zhihao Fan, **Zejun Li**, Ruipu Luo, Xuanjing Huang, Zhongyu Wei. **COLING 2024**.
- [Negative Sample is Negative in Its Own Way: Tailoring Negative Sentences for Image-Text Retrieval](https://arxiv.org/pdf/2111.03349). Zhihao Fan, Zhongyu Wei, **Zejun Li**, Siyuan Wang, Xuanjing Huang, Jianqing Fan. **NAACL 2022**.
- [Constructing phrase-level semantic labels to form multi-grained supervision for image-text retrieval](https://arxiv.org/pdf/2109.05523). Zhihao Fan, Zhongyu Wei, **Zejun Li**, Siyuan Wang, Haijun Shan, Xuanjing Huang, Jianqing Fan. **ICMR 2022**.
- [Tcic: Theme concepts learning cross language and vision for image captioning](https://arxiv.org/pdf/2106.10936). Zhihao Fan, Zhongyu Wei, Siyuan Wang, Ruize Wang, **Zejun Li**, Haijun Shan, Xuanjing Huang. **IJCAI 2021**.


# 📖 Educations
- *2020.09 - 2026.06 (estimated)*, Ph.D. Candidate in Statistics (Statistical Machine Learning Direction), Fudan University, Shanghai, China. 
- *2016.09 - 2020.06*, Bachelor of Computer Science, Fudan University, Shanghai, China. 

# 💬 Teaching and Service
## Teaching Assistant
- Head TA for "Introduction to Artificial Intelligence", Fudan University, *Spring 2020, 2021, Fall 2022*.
- Organizer for "NLP training camp of Fudan DISC", Fudan University, *Spring 2023*.

## Program Committee:
- Area Chair of Multi-Modality: EMNLP 2024, NAACL 2025.
- Reviewer: ACL, EMNLP, AAAI, IJCAI, CL, ACM MM, TKDD, NLPCC, CCL.

## Invited Talks
- "Evolution of the Vision-Language Pre-traning Framework", *in CSSNLP 2022 Student Seminar*.
- "How to Eficiently Conduct Team-based Research?", *in SMP 2023, Student Seminar*.
- "Rethinking Research Direction Selection in Your Graduate Career", *in YSSNLP 2024, Student Seminar*.

# 💻 Internships
- *2021.09 - 2022.09*, intern of CV algorithm engineer at ByteDance E-Commerce Group, Shanghai, China.
- *2019.06 - 2019.09*, intern of machine learning algorithm enginner at Alibaba Koubei Group, Hangzhou, China.

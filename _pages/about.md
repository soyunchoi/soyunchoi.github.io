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

I am a third-year Ph.D. student at SKKU (Sungkyunkwan University), South Korea, advised by <a href='https://www.csehong.com/'>Prof. Sungeun Hong</a> in the Artificial Intelligence and Media Lab (<a href='https://aim.skku.edu/home'>AIM Lab</a>). My research focuses on segmentation tasks in various multimodal settings, such as RGB-X and amodal segmentation. Recently, I have been expanding this work toward vision-language-action tasks for robotic applications.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a>  -->
<!-- (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 📝 Publications 
<span style="font-size: smaller;">Equal contribution are denoted by *</span>
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/qa-tiger.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

- <strong>Dual Path Semantic Segmentation with Locality Guidance Tokens, <span style="color:blue"> Neurocomputing 2026 </span></strong> <br>
Jaeik Kim, Yoonjae Baek, Aecheon Jung, Hongyeob Kim, <strong><span style="color:blue">Soyun Choi</span></strong>, Youngeun Kim, Jaeyoung Do, and Sungeun Hong <br>
[[DOI]](https://doi.org/10.1016/j.neucom.2026.135268) [[paper]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6380741) <a href="https://scholar.google.com/scholar?q=%22Dual+Path+Semantic+Segmentation+with+Locality+Guidance+Tokens%22"><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>


- <strong>Connecting the Objects: Relational Occlusion Graphs for Amodal Segmentation, <span style="color:blue">Pattern Recognition Letters 2026</span></strong> <br> <span>Huiling Liu*</span>, <span>Eunnam Cho*</span>, <strong><span style="color:blue">Soyun Choi</span></strong>, Aecheon Jung, Seung Wook Kim, and Sungeun Hong†<br>
[[DOI]](https://doi.org/10.1016/j.patrec.2026.06.021) [[paper]](https://www.sciencedirect.com/science/article/pii/S0167865526002230) <a href="https://scholar.google.com/scholar?q=%22Connecting+the+Objects%3A+Relational+Occlusion+Graphs+for+Amodal+Segmentation%22"><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

- <strong>Comprehensive Survey on Advances and Challenges in RGB-D Semantic Segmentation, <span style="color:blue">Pattern Recognition 2026</span></strong> <span style="font-size: smaller;">(Q1)</span> <br> <strong><span style="color:blue">Soyun Choi</span></strong>, Eunnam Cho, Aecheon Jung, Byung-Cheol Min, Junhong Min†, and Sungeun Hong†<br>[[DOI]](https://doi.org/10.1016/j.patcog.2026.114146) [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320326011118) [[code]](https://github.com/AIM-SKKU/RGBD-SS-survey) <a href="https://scholar.google.com/scholar?q=%22Comprehensive+Survey+on+Advances+and+Challenges+in+RGB-D+Semantic+Segmentation%22"><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

- <strong>Memory-efficient cross-modal attention for RGB-X segmentation and crowd counting, <span style="color:blue">Pattern Recognition 2025</span></strong> <span style="font-size: smaller;">(Q1)</span> <br> Youjia Zhang, <strong><span style="color:blue">Soyun Choi</span></strong>, and Sungeun Hong†<br>[[DOI]](https://doi.org/10.1016/j.patcog.2025.111376) [[paper]](https://www.sciencedirect.com/science/article/pii/S0031320325000366) <a href='https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=RcVbUFgAAAAJ&authuser=1&citation_for_view=RcVbUFgAAAAJ:2osOgNQ5qMEC'><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

- <strong>IAM: Enhancing RGB-D Instance Segmentation with New Benchmarks, <span style="color:blue">arXiv 2025</span></strong><br> Aecheon Jung*, <strong><span style="color:blue">Soyun Choi</span>*</strong>, Junhong Min, and Sungeun Hong†<br>[[project page]](https://huggingface.co/datasets/kasurashan/RGBD-Instance-Segmentation) [[arXiv]](https://arxiv.org/pdf/2501.01685) <a href='https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=RcVbUFgAAAAJ&authuser=1&citation_for_view=RcVbUFgAAAAJ:9yKSN-GCB0IC'><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

- <strong>Intra-inter Modal Attention Blocks for RGB-D Semantic Segmentation, <span style="color:blue">ICMR 2023 Oral</span></strong><br><strong><span style="color:blue">Soyun Choi</span></strong>, Youjia Zhang, and Sungeun Hong†<br>[[project page]](https://aim.skku.edu/publication/international-conference/ima_icmr23) [[paper]](https://dl.acm.org/doi/pdf/10.1145/3591106.3592235) [[code]](https://github.com/AIM-SKKU/IMA) <a href='https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=RcVbUFgAAAAJ&authuser=1&citation_for_view=RcVbUFgAAAAJ:d1gkVwhDpl0C'><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

- <strong>Spatio-channel Attention Blocks for Cross-modal Crowd Counting, <span style="color:blue">ACCV 2022 Oral</span></strong><br>Youjia Zhang, <strong><span style="color:blue">Soyun Choi</span></strong>, and Sungeun Hong†<br>[[project page]](https://aim.skku.edu/publication/international-conference/csca_accv22) [[paper]](https://openaccess.thecvf.com/content/ACCV2022/papers/Zhang_Spatio-channel_Attention_Blocks_for_Cross-modal_Crowd_Counting_ACCV_2022_paper.pdf) [[code]](https://github.com/AIM-SKKU/CSCA) <a href='https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=RcVbUFgAAAAJ&authuser=1&citation_for_view=RcVbUFgAAAAJ:u-x6o8ySG0sC'><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>



</div>

# 💡 Projects
- *2025.09 - Present*: <strong>Training-Free Prompt-Based Reasoning for Multimodal Missing Modality Completion</strong> <br> Ph.D. Students Fellowship by National Research Foundation of Korea (NRF)
- *2024.07 - Present*: <strong>Development of Reliable, Secure, and Safe Human-AI Alignment Techniques</strong> <br> Funded by Institute for Information & communications Technology Promotion (IITP)
- *2023.03 - 2026.02*: <strong>RGB-X Path Networks for Multi-modal Multi-task Learning</strong> <br> Funded by National Research Foundation of Korea (NRF)
- *2023.03 - 2023.10*: <strong>RGB-D Object Detection and Segmentation based on Multimodal Fusion</strong> <br> Funded by Samsung Electronics
- *2021.09 - 2023.08*: <strong>Visuo-Tactile Perception for Human-Like Manipulation of Deformable Objects with Dynamic Center of Mass</strong> <br> Funded by Samsung Research Funding & Incubation Center for Future Technology

# 🎖 Honors and Awards
- *2026.11*: Ranked **3rd** in the [CoRL 2026 RoboFineMani MetaFine Open Competition](https://robofinemani2026.github.io/competition.html). [[Technical Report]](https://arxiv.org/abs/2611.00955)
- *2026.06*: Ranked **5th** in the Real-world Challenge at the [ICRA 2026 LeHome Challenge](https://lehome-challenge.com/).
- *2026.06*: Ranked **8th** in the Simulation Challenge at the [ICRA 2026 LeHome Challenge](https://lehome-challenge.com/).
- *2025.11*: Selected as <strong>a recipient of the AI SeoulTech Graduate Scholarship</strong>, awarded for outstanding research potential in AI.
- *2022.02*: <strong>Excellence Award</strong>, Inha Artificial Intelligence Challenge.

# 🔍 Academic Activities
- Pattern Recognition 2026 Reviewer

# 📖 Educations
- *<strong>2024.03 - Present</strong>*: Sungkyunkwan University, Ph.D. Student, Department of Immersive Media Engineering.
- *<strong>2024.09 - 2025.02</strong>*: Purdue University, Visiting Scholar @ [SMART LAB](https://www.smart-laboratory.org/).
- *<strong>2021.09 - 2024.02</strong>*: Inha University, M.S., Department of Electrical and Computer Engineering.
- *<strong>2016.03 - 2020.02</strong>*: Andong National University, B.E., Department of Information and Communication Engineering.

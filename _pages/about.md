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


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 Ranked 5th in the Real-world Challenge at the ICRA 2026 LeHome Challenge!
- *2026.06*: &nbsp;🎉🎉 Comprehensive survey on advances and challenges in RGB-D semantic segmentation is accepted at Pattern Recognition!
- *2026.05*: &nbsp;🎉🎉 Ranked 8th in the Simulation Challenge at the ICRA 2026 LeHome Challenge!
- *2025.01*: &nbsp;🎉🎉 Memory-efficient cross-modal attention for RGB-X segmentation and crowd counting is accepted at Pattern Recognition!

# 📝 Publications 
<span style="font-size: smaller;">Equal contribution are denoted by *</span>
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/qa-tiger.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

- <strong>Connecting the Objects: Relational Occlusion Graphs for Amodal Segmentation </strong> <br> Under Review <br> Huiling Liu<sup>*</sup>, Eunnam Cho<sup>*</sup>, <strong><span style="color:blue">Soyun Choi</span></strong>, Aecheon Jung, Seung Wook Kim, and Sungeun Hong†<br>

- <strong>Comprehensive Survey on Advances and Challenges in RGB-D Semantic Segmentation, <span style="color:blue">Pattern Recognition 2026</span></strong> <span style="font-size: smaller;">(Q1)</span> <br> <strong><span style="color:blue">Soyun Choi</span></strong>, Eunnam Cho, Aecheon Jung, Byung-Cheol Min, Junhong Min†, and Sungeun Hong†<br>[[DOI]](https://doi.org/10.1016/j.patcog.2026.114146) [[paper]](https://pdf.sciencedirectassets.com/272206/1-s2.0-S0031320326X2009X/1-s2.0-S0031320326011118/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEB8aCXVzLWVhc3QtMSJHMEUCIEDNCqV98Ib%2Bk9sdibyeJbZDtF2D7OGJqoLABEL1tte1AiEAxX%2BBj3a8BX%2Foes2b%2B7POW0k6aivpvwn4%2BQ2GImVAVPoqvAUI6P%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDECrDk2kzYhInIH3uCqQBavwCX5b5qsTCPNSKj4O%2F02r%2FNDLHWtquyTNiv6IuI3%2BmV6z3zgpXptfDZyj4SXqPvheoNKzktKXGi6MVIrG%2BeH9LKx1c9hBQDkD5R%2FJ4BHODD1IwK%2BbiNJzzkEI2nYZcEnN7enJozR5M1Rgs%2FTuxY2an5TkAJLPgJMNCSwdiv4wO1pvdO%2Bu7HsvIuRKz6Qq1RuC1fqBskBN5EzO%2Bf%2Bo0v8v1zGEMg49MSxyAZfUXUUsVGyMTytg3D8a8pyqu0gyml%2B1ju2geC5wnDIDDXZMbtFRLpj4cpR8hKW%2BmX1KD0wu%2F9vQH4tyK3u46%2BOMAbUDNNTkZBjzTbMviUZkP71jnXlTcdJUUl%2FP73gP0PBfOpID9JIGl0aEEEMOuVR9UfXJ8s3cHcDyqoO5TWlXfnruqg9%2Fg8GeP%2F7CyPkdaeYUr2p%2B7Q%2B%2FivXgs6YcDVyeh%2BR3LgfTc33j81C9Q3CAPwmaJq%2FHoZArRJ057vr36IvOtYWGDhhJA%2Bjvph4%2BdDtiRBQC2eSRbwufIabCNLxIppjzKTSU%2FvTpsTUc8UndG3m4Jw5lpRsZJRR7IgH1N8C2R8p4c%2Fp79gJGIuQYauBXcOo8xncWkq2uNcZiYsNDRZ4jVx62C6oQrq%2BmgtHW%2BPSRaRMXOj26HhAfBJpkjAFvMV9pHSfQJNRNWBIUMSG8l%2BOp5IIPXfa01UFknMZCruAj26Nx6iTLmBgStHZTfy5H5pXVazkGWRGuq7tL6OaSjWZwr1ymHzIRXiiE7nrqTFR3z9dv3Drl%2Fr3Nl%2B2ls5EfsCCvn92Qh0Fsz19La9Dleb2sRYTSFnqNRPJpsMG6IwjqFUC4cYDaZOd9jX4s8YjD%2FJKgS1ghO4Tp5SkauSGFzWxwe%2BW8MOPmpdEGOrEBp83aVguGb1HgbVwiLq51hMrxkB%2F2gwba2xDyKrh4OoDSfhw6ltvPYZWZuyrgvhIxKDXlUz78mSsfU1QepHadiwaEYDnnTzoyMKTW8Za%2BNX18J9qGShGvi%2FW9UXlQ2FirQwUQaQBlboE9BP2tQWnEcfiJL2jCj5rmxuZgt4ZnK16zjnXIXpdFA%2BXTwaO%2BEljc50GOUtZIO32vqaEMWidMbMQAZoyfsVFLYkUzhaX51Ckw&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260610T143754Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYXUR5MHLZ%2F20260610%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b1c4083f1596f85e04c0c9f2d8645268b4d8ec798cc27644b1533da5f7ee0383&hash=91be4eed2ff1e9ebb43916d35827f6f73722052c92b954352469dd54d84019e0&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0031320326011118&tid=spdf-d7fdd67d-55ae-4eba-9be6-007adabeb334&sid=a841d6514efb70461329cba5f299dc828db2gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=11140e535c585e0a030d04&rr=a0991ddbcdb91b19&cc=kr) [[code]](https://github.com/AIM-SKKU/RGBD-SS-survey)

- <strong>Memory-efficient cross-modal attention for RGB-X segmentation and crowd counting, <span style="color:blue">Pattern Recognition 2025</span></strong> <span style="font-size: smaller;">(Q1)</span> <br> Youjia Zhang, <strong><span style="color:blue">Soyun Choi</span></strong>, and Sungeun Hong†<br>[[DOI]](https://doi.org/10.1016/j.patcog.2025.111376) [[paper]](https://pdf.sciencedirectassets.com/272206/1-s2.0-S0031320325X00029/1-s2.0-S0031320325000366/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJ3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQD9h1FytkSoc4lPGM7sg4E8zbZ4AisL1xu7yi6ytRnjHwIgYSXOp%2Bw1cmgAUejehYvFV8yngo4siyZQVEdEdyCUqhEquwUIhf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDObZZC9Qk2dQM1qq7SqPBUNbN2M92mkwnjcXIyur%2FE1CgbvByeYTtrhruoGgZq6xpz9d0B3LNJc5kjNEs3kEzDD6WnNr25%2F3gSiEgdWuiEDX7eBol69bTlXlivmf2fAive7U7ES%2Fzc9UPec1tpbp3%2F0ySqzw0roKpv96cWJ%2Fpo1P1cLt2%2FsNI8uEicpoUHcDmikvTahxH9WbxaCLyL%2B%2FbV%2FItItaXZUyXa3VFuEIxNAJbZHmAUUfogibdIKq3E4jmDnwFFOvWXPPpAA5XIztN8yj2%2Bibe28nLe%2BAKDqBXUw9l1rN05PQQF0sxSXzzZ%2F35TzWA5Q7nI8DlecUoKNvjIjtt7UsoA%2BqcGtPbgWS61jN4LTD8ApDpN24ChMwObbiyA8O%2BqF0OKnrw9%2Bee7ho2%2FSJ6DCVpo%2BmU5z3EHi4vGrTXJkANpBLR8Zh1eIY2aNI4UuKj1A7WY1v3scMxIESPZ6lWDDb5e157ttAE6GPmqcNkS9ptnGsGMpEVH1Ve8s0gjcp3I2oBDqt2IphLUVKiF0TLsYqT1iGDMVpkQFMrab%2BzkuWA6TMl5GZEcyikr2J9B%2FaNNPSIQ25R8PvU2E53gaBi7kc4vHUntbTI116ijrZKITbWiB5yYDpe0ciViqOtau4T1bqJZoD%2B%2FjVIre%2Bdz2R3VF8xtnbWBZsRwkbKd1Y98fDAqJ%2Bd1a4gYPRyCyUagJZU3vXBNe27sHWw6xh0NK6MgTAdigNTjauKISSGWKtlox%2FJJKSpxP9YlY96Wt75tzVVYOIezeyC2MWS4stCloxfgYaN1OWLSMkDs79giO1QKuOh%2F%2B1xlHSi1j24ugmeOh1qrF8O6sMclx8%2B3adw9HIbwl76UyrrkQLl7g8C0ZKK25LH4UtoWuo3ETlnWMw3%2FzIwgY6sQHiMfOX7lkxJ5c7gJ0WVwyx4HKqGg2MwK2P0dBx57K6SV1XSUXhTBrXEQMzKSxNEhXUmG5DAE57GQ%2FMbQQA8Kabswzhib8Z6EyeVVP2T2D1SZ2B5GeyCoA3zNeWfmsmbeMUX%2FKJQAtamI7sd6Bnpgrb5WaAWQ%2FQE0NcQsLEKFKedXcrt3rxbsU9BhDtRFeUfx%2B4e%2FLWzELMPIqH8kG2KU7%2FyzDqwlKfDVrvEfq%2BSHsItas%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250618T051308Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYSBZO6MQK%2F20250618%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d927fe21c975ce375237d0a1d53981288ff47802fe657c7194a6f2ad15c4c15e&hash=63198443d48ae91a9a451c105c0738352e43ec113a34023afd291cdaaff213d4&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0031320325000366&tid=spdf-5e903aef-1860-48c4-8b82-30fa656d5d24&sid=d503315d974ce54ca08bf6254eff022f94cegxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=11145b5b5e5c540501&rr=95184bb02b32ea2b&cc=kr) <a href='https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=RcVbUFgAAAAJ&authuser=1&citation_for_view=RcVbUFgAAAAJ:2osOgNQ5qMEC'><img src="https://img.shields.io/badge/Google%20Scholar-View-blue?logo=Google%20Scholar&style=flat"></a>

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
- *2026.06*: Ranked <strong>5th</strong> in the Real-world Challenge at the [ICRA 2026 LeHome Challenge](https://lehome-challenge.com/).
- *2026.06*: Ranked <strong>8th</strong> in the Simulation Challenge at the [ICRA 2026 LeHome Challenge](https://lehome-challenge.com/).
- *2025.11*: Selected as <strong>a recipient of the AI SeoulTech Graduate Scholarship</strong>, awarded for outstanding research potential in AI.
- *2022.02*: <strong>Excellence Award</strong>, Inha Artificial Intelligence Challenge.

# 🔍 Academic Activities
- Pattern Recognition 2026 Reviewer

# 📖 Educations
- *<strong>2024.03 - Present</strong>*: Sungkyunkwan University, Ph.D. Student, Department of Immersive Media Engineering.
- *<strong>2024.09 - 2025.02</strong>*: Purdue University, Visiting Scholar @ [SMART LAB](https://www.smart-laboratory.org/).
- *<strong>2021.09 - 2024.02</strong>*: Inha University, M.S., Department of Electrical and Computer Engineering.
- *<strong>2016.03 - 2020.02</strong>*: Andong National University, B.E., Department of Information and Communication Engineering.

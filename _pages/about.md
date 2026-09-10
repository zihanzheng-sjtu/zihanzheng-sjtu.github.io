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

<p>I am currently a second-year PhD candidate at <a href="https://mediax.sjtu.edu.cn/">MediaX Lab</a>, <a href="https://cmic.sjtu.edu.cn/EN/Default.aspx">Cooperative Medianet Innovation Center</a>, <a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a>, where I am supervised by Prof. Xiaoyun Zhang and Prof. <a href="https://qianghu-huber.github.io/qianghuhomepage/">Qiang Hu</a>. My research focuses on 3D reconstruction and 3D generation.</p>

# 🔥 News
- *2026.09*: GenSplatCodec was accepted to TMM 2026.
- *2026.05*: Won first place in the Dynamic Gaussian Splatting Compression Challenge at ICME 2026.
- *2026.03*: Joined <a href="https://acrab.ai/">Acrab.ai</a>  Agentic Labs as an intern.
- *2025.12*: Attended SIGGRAPH Asia 2025 and gave an oral presentation at the Volumetric Video Workshop.
- *2025.12*: Won second place in the Compression Track of the SIGGRAPH Asia 2025 Volumetric Video Challenge.
- *2025.09*: PrismGS was accepted to VCIP 2025.
- *2025.09*: 4DGCPro was accepted to NeurIPS 2025.
- *2025.03*: 4DGC was accepted to CVPR 2025.
- *2024.12*: VRVVC was accepted to AAAI 2025.
- *2024.10*: Attended ACM MM 2024 and gave an oral presentation.

<details>
<summary><strong>Earlier News</strong></summary>
<div markdown="1">

- *2024.08*: HPC was accepted to ACM MM 2024 as an oral presentation.
- *2024.06*: JointRF was accepted to ICIP 2024 and was recognized among the **top 5% of accepted papers**.

</div>
</details>


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2026</div><img src='images/gensplatcodec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](https://arxiv.org/abs/2607.24403)

[Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/), Zhenlong Wu, Lei Huang, **Zihan Zheng**,  Xiaoyun Zhang, Wenjun Zhang 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VCIP 2025</div><img src='images/PrismGS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PrismGS: Physically-Grounded Anti-Aliasing for High-Fidelity Large-Scale 3D Gaussian Splatting](https://arxiv.org/pdf/2510.07830)

[Houqiang Zhong](https://waveviewer.github.io/)<sup>*</sup>, Zhenlong Wu<sup>*</sup>, Sihua Fu<sup>*</sup>, **Zihan Zheng**, Xin Jin, Xiaoyun Zhang, Li Song, [Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/4dgcpro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[4DGCPro: Efficient Hierarchical 4D Gaussian Compression for Progressive Volumetric Video Streaming](https://arxiv.org/pdf/2509.17513)

**Zihan Zheng**, Zhenlong Wu, [Houqiang Zhong](https://waveviewer.github.io/), Yuan Tian, Ning Cao, Lan Xu, Jiangchao Yao, Xiaoyun Zhang, [Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/), Wenjun Zhang

[**Project Page**](https://mediax-sjtu.github.io/4DGCPro/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/4dgc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[4DGC: Rate-Aware 4D Gaussian Compression for Efficient Streamable Free-Viewpoint Video](https://arxiv.org/pdf/2503.18421)

[Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/)<sup>*</sup>, **Zihan Zheng**<sup>*</sup>, [Houqiang Zhong](https://waveviewer.github.io/), Sihua Fu, Li Song, Xiaoyun Zhang, Guangtao Zhai, Yanfeng Wang

[**Project Page**](https://mediax-sjtu.github.io/4dgc/), [**Code**](https://github.com/zihanzheng-sjtu/4DGC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/VRVVC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VRVVC: Variable-Rate NeRF-Based Volumetric Video Compression](https://arxiv.org/pdf/2412.11362)

[Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/)<sup>*</sup>, [Houqiang Zhong](https://waveviewer.github.io/)<sup>*</sup>, **Zihan Zheng**, Xiaoyun Zhang, Zhengxue Cheng, Li Song, Guangtao Zhai, Yanfeng Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM-MM 2024</div><img src='images/HPC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HPC: Hierarchical Progressive Coding Framework for Volumetric Video](https://arxiv.org/pdf/2407.09026)

 **Zihan Zheng**<sup>*</sup>, [Houqiang Zhong](https://waveviewer.github.io/)<sup>*</sup>, [Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/), Xiaoyun Zhang, Li Song, Ya Zhang, Yanfeng Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIP 2024</div><img src='images/JointRF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JointRF: End-to-End Joint Optimization for Dynamic Neural Radiance Field Representation and Compression](https://arxiv.org/pdf/2405.14452)

 **Zihan Zheng**<sup>*</sup>, [Houqiang Zhong](https://waveviewer.github.io/)<sup>*</sup>, [Qiang Hu](https://qianghu-huber.github.io/qianghuhomepage/), Xiaoyun Zhang, Li Song, Ya Zhang, Yanfeng Wang

</div>
</div>

# 💼 Experience

## Industry Experience
- **Intern**, Agentic Labs, <a href="https://acrab.ai/">Acrab.ai</a>  
  *Mar. 2026 - Present*  
  **Mentors:** Chunlei Cai and Yichen Gong

## Research Experience
- **PhD Student**, <a href="https://mediax.sjtu.edu.cn/">MediaX Lab</a>, <a href="https://cmic.sjtu.edu.cn/EN/Default.aspx">Cooperative Medianet Innovation Center</a>, Shanghai Jiao Tong University  
  *Sep. 2024 - Present*  
  **Supervisors:** Prof. Xiaoyun Zhang and Prof. <a href="https://qianghu-huber.github.io/qianghuhomepage/">Qiang Hu</a>  
  Research on 3D/4D Gaussian Splatting, volumetric video compression, and efficient streaming.

- **Undergraduate Research Intern**, <a href="https://mediabrain.sjtu.edu.cn/">MediaBrain</a>, <a href="https://cmic.sjtu.edu.cn/EN/Default.aspx">Cooperative Medianet Innovation Center</a>, Shanghai Jiao Tong University  
  *Mar. 2022 - Jun.2023*  
  **Supervisors:** Prof. <a href="https://siheng-chen.github.io/">Siheng Chen</a>  
  Research on autonomous driving and cooperative perception.

# 🤝 Services

## Reviewer
- **Conferences:** CVPR, NeurIPS, ICIP
- **Journals:** IEEE TVCG, IEEE TCSVT

## Student Counselor
- Counselor for students majoring in Artificial Intelligence, Class of 2024, School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University.
- Counselor for students in the IEEE Pilot Classes in Information Engineering, Classes of 2022-2025, School of Information and Electronic Engineering, Shanghai Jiao Tong University.

# 🏆 Honors and Awards
- *2024.04* Outstanding Graduate of Shanghai Jiao Tong University.
- *2025.12* Second Place, SIGGRAPH Asia 2025 Volumetric Video Challenge - Compression Track
- *2025.12* 2025 Academic Year Outstanding Graduate Student Scholarship, Shanghai Jiao Tong University
- *2026.05*: First place, ICME 2026 Dynamic Gaussian Splatting Compression Challenge

# 🎓 Education
- *2024.09 - now*, PhD Student, Electronic Science and Technology, Shanghai Jiao Tong University.
- *2020.09 - 2024.06*, Undergraduate, Artificial Intelligence, Shanghai Jiao Tong University.

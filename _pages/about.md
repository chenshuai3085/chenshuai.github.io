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

I am a Master's student at [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) and the [Shanghai Institute of Technical Physics (SITP), Chinese Academy of Sciences](http://www.sitp.ac.cn/), advised by [Prof. Shengli Sun](http://www.sitp.ac.cn/) (Academician of CAS). I also served as a Research Assistant at the [HKUST (Guangzhou)](https://www.hkust-gz.edu.cn/), focusing on Embodied Intelligence. Prior to this, I received my Bachelor's degree from [Nantong University](https://www.ntu.edu.cn/) in 2023, ranked **1st/45** in my cohort.

My research focuses on **Embodied Intelligence**, with a particular interest in building intelligent robotic systems that can perceive, reason, and act in the physical world. My current work centers around **Vision-Language-Action (VLA) models** and **World Models** for robotic manipulation, exploring how to bridge the gap between multimodal understanding and reliable physical interaction. I am interested in developing efficient and generalizable approaches for robot learning, including discrete diffusion-based action generation, flow matching for action refinement, and representation alignment for world-aware policies.

If you are interested in collaborating or discussing research ideas, please feel free to reach out to me via email at [chenshuai2024@shanghaitech.edu.cn](mailto:chenshuai2024@shanghaitech.edu.cn).


# 🔥 News
- *2026.04*: One paper submitted to **ECCV 2026** (Fast-dVLA), and two more papers on VLA under review (DFM-VLA, FRAPPE)!
- *2026.03*: Joined **Xiaomi Robotics** as an Embodied Intelligence Algorithm Intern.
- *2025.09*: Started as a Research Assistant at **HKUST (Guangzhou)**.
- *2024.09*: Started my M.S. studies at ShanghaiTech University & SITP, CAS.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026 (Submitted)</div><img src='images/fast-dvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fast-dVLA: Accelerating Discrete Diffusion VLA to Real-Time Performance](https://arxiv.org/abs/2603.25661)

Wenxuan Song\*, Jiayi Chen\*, **Shuai Chen\***, Jingbo Wang, Pengxiang Ding, Han Zhao, Yikai Qin, Xinhu Zheng, Donglin Wang, Yan Wang†, Haoang Li†

*\*Equal Contribution, †Corresponding Author*

[**Project**](https://chris1220313648.github.io/Fast-dVLA/)

- We propose Fast-dVLA, a novel block-wise diffusion strategy that achieves the **first breakthrough in accelerating discrete diffusion VLAs to a real-time regime**.
- Fast-dVLA consistently achieves **2.8x-4.1x speedup** (up to **402 Tokens/s**) while preserving action performance across CALVIN, LIBERO, and SIMPLER benchmarks.
- We reveal an implicit block-wise AR decoding tendency in dVLAs and design a pipelined parallel decoding algorithm for inter-block parallelism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026 (Submitted)</div><img src='images/dfm-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DFM-VLA: Iterative Action Refinement for Robot Manipulation via Discrete Flow Matching](https://arxiv.org/abs/2603.26320)

Jiayi Chen\*, Wenxuan Song\*, **Shuai Chen**, Jingbo Wang, Zhijun Li†, Haoang Li†

*\*Equal Contribution, †Corresponding Author*

[**Project**](https://chris1220313648.github.io/DFM-VLA/)

- We identify the **irreversible commitment** problem in existing AR and discrete diffusion VLA decoding, and propose DFM-VLA based on discrete flow matching for iterative action refinement.
- DFM-VLA models a token-level probability velocity field that dynamically updates the full action sequence across refinement iterations.
- Achieves an average success length of **4.44 on CALVIN** and **95.7% on LIBERO**, consistently outperforming strong baselines.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2026 (Submitted)</div><img src='images/frappe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FRAPPE: Infusing World Modeling into Generalist Policies via Multiple Future Representation Alignment](https://arxiv.org/abs/2602.17259)

Han Zhao†‡, Jingbo Wang†, Wenxuan Song†, **Shuai Chen**, Yang Liu, Yan Wang, Haoang Li\*, Donglin Wang\*

*†Equal Contribution, ‡Project Lead, \*Corresponding Authors*

[**Project**](https://h-zhao1997.github.io/frappe) \| [**Code**](https://github.com/Jbo-Wang/frappe)

- We propose FRAPPE, a scalable and data-efficient approach to enhance **world-awareness in generalist robotic policies** via future representation alignment with multiple visual foundation models.
- Outperforms state-of-the-art approaches on RoboTwin benchmark and real-world tasks, with strong generalization in long-horizon and unseen scenarios.
- The world-modeling training process can significantly benefit from **action-free data**, reducing dependence on expert teleoperation data.
</div>
</div>


# 💻 Internships
- *2026.03 - Present*, Embodied Intelligence Algorithm Intern, <img src='./images/xiaomi_logo.svg' style="height: 1.2em; vertical-align: -0.15em;"> [Xiaomi Robotics](https://www.mi.com/), Beijing, China.
  - Research on tactile sensing for robotic manipulation policies.
- *2025.09 - 2026.01*, Research Assistant, [HKUST (Guangzhou)](https://www.hkust-gz.edu.cn/), Guangzhou, China.
  - Embodied intelligence research. Contributed to Fast-dVLA and FRAPPE projects involving VLA model acceleration and world modeling.
- *2025.12 - 2026.02*, Embodied Intelligence Algorithm Intern, <img src='./images/cowarobot_logo.png' style="height: 1.2em; vertical-align: -0.15em;"> [COWAROBOT](https://www.cowarobot.com/), Shanghai, China.
  - Dual-arm robot manipulation using GR00T/π₀ policy models for industrial pick-and-place tasks. Built end-to-end pipelines from training to real-robot deployment on Realman and AgileX platforms.


# 📖 Educations
- *2024.09 - 2027.06 (Expected)*, M.S. in Electronic Science and Technology, [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) & [Shanghai Institute of Technical Physics, CAS](http://www.sitp.ac.cn/), Shanghai, China. Advised by [Prof. Shengli Sun](http://www.sitp.ac.cn/) (Academician of CAS).
- *2019.09 - 2023.06*, B.E. in Measurement & Control Technology, [Nantong University](https://www.ntu.edu.cn/), Nantong, China. **Ranked 1st/45**. 7 national awards, 6 provincial awards. Led Jiangsu Province College Students Innovation Training Project.


# 🎖 Honors and Awards
- *2023* National 2nd Prize, the 16th China College Students Computer Design Competition (1st Author)
- *2021* **National 1st Prize**, the 9th National College Students Mechanical Innovation Design Competition
- *2021* **National Special Prize**, the 14th Digital Mathematical Modeling Competition (3/1289, 1st Author)
- *2021* Provincial 1st Prize, the 7th National College Students Engineering Capability Competition, Jiangsu Region (1st Author)
- *2020* National 2nd Prize, China Engineering Robot Competition (1st Author)
- *2021* Provincial 1st Prize, Mathematics Modeling Competition, Jiangsu Province (1st Author)
- *2021* Provincial 1st Prize, the 6th Jiangsu Smart Instrument Competition (1st Author)


# 📄 Patents
- **6 granted Chinese invention patents**, including multiple as **first author**:
  - Embedded Machine Learning-based Intelligent Data Analysis and Processing System (ZL 2021 10675140.9, **1st Author**)
  - Intelligent Health Detection and Epidemic Prevention Security Gate (CN202011059276.9, **1st Author**)
  - Embedded Intelligent Face Detection and Tracking System (ZL 2021 10555455.X, 2nd Author)
  - and 3 more patents on robotic assistive devices and autonomous logistics.


<!-- # 💬 Invited Talks
- *20XX.XX*, Talk Title  -->

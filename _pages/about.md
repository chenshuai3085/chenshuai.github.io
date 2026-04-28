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

I am a Master's student at [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) and the [Shanghai Institute of Technical Physics (SITP), Chinese Academy of Sciences](http://www.sitp.ac.cn/), advised by [Prof. Shengli Sun](http://www.sitp.ac.cn/) (Academician of CAS). I also served as a Research Assistant at [HKUST (Guangzhou)](https://www.hkust-gz.edu.cn/). Prior to this, I received my Bachelor's degree from [Nantong University](https://www.ntu.edu.cn/) in 2023, ranked **1st/45** in my cohort.

My research focuses on **Embodied Intelligence**, particularly on building intelligent robotic systems that can perceive, reason, and act in the physical world. I am interested in:
- **Vision-Language-Action (VLA) Models**: efficient discrete diffusion and flow matching approaches for robotic action generation
- **World Models**: representation alignment for world-aware generalist policies
- **Real-Robot Deployment**: bridging sim-to-real transfer for manipulation tasks

If you are interested in collaborating, please feel free to email me at [chenshuai2024@shanghaitech.edu.cn](mailto:chenshuai2024@shanghaitech.edu.cn).


# 🔥 News
- *2026.04*: Two papers submitted to **ECCV 2026** (Fast-dVLA, DFM-VLA) and one to **RSS 2026** (FRAPPE)!
- *2026.03*: Joined <img src='./images/xiaomi_logo.svg' style="height: 1.0em; vertical-align: -0.1em;"> **Xiaomi Robotics** as an Embodied Intelligence Algorithm Intern.
- *2025.09*: Started as a Research Assistant at **HKUST (Guangzhou)**.
- *2024.09*: Started M.S. at ShanghaiTech University & SITP, CAS.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026 (Submitted)</div><img src='images/fast-dvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fast-dVLA: Accelerating Discrete Diffusion VLA to Real-Time Performance](https://arxiv.org/abs/2603.25661)

Wenxuan Song\*, Jiayi Chen\*, **Shuai Chen\***, Jingbo Wang, Pengxiang Ding, Han Zhao, Yikai Qin, Xinhu Zheng, Donglin Wang, Yan Wang†, Haoang Li†

*\*Equal Contribution, †Corresponding Author*

[**Project**](https://chris1220313648.github.io/Fast-dVLA/)

- First breakthrough in accelerating discrete diffusion VLAs to **real-time** (**2.8x–4.1x** speedup, up to **402 Tokens/s**).
- Novel block-wise causal attention and pipelined parallel decoding for inter-block parallelism.
- Validated on CALVIN, LIBERO, and SIMPLER benchmarks with preserved action performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026 (Submitted)</div><img src='images/dfm-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DFM-VLA: Iterative Action Refinement for Robot Manipulation via Discrete Flow Matching](https://arxiv.org/abs/2603.26320)

Jiayi Chen\*, Wenxuan Song\*, **Shuai Chen**, Jingbo Wang, Zhijun Li†, Haoang Li†

*\*Equal Contribution, †Corresponding Author*

[**Project**](https://chris1220313648.github.io/DFM-VLA/)

- Identifies the **irreversible commitment** problem in AR and discrete diffusion VLA decoding.
- Proposes discrete flow matching for full-sequence iterative action refinement at token level.
- Achieves **4.44 avg. success length on CALVIN** and **95.7% on LIBERO**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2026 (Submitted)</div><img src='images/frappe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FRAPPE: Infusing World Modeling into Generalist Policies via Multiple Future Representation Alignment](https://arxiv.org/abs/2602.17259)

Han Zhao†‡, Jingbo Wang†, Wenxuan Song†, **Shuai Chen**, Yang Liu, Yan Wang, Haoang Li\*, Donglin Wang\*

*†Equal Contribution, ‡Project Lead, \*Corresponding Authors*

[**Project**](https://h-zhao1997.github.io/frappe) \| [**Code**](https://github.com/Jbo-Wang/frappe)

- Enhances **world-awareness** in generalist robotic policies via future representation alignment with multiple visual foundation models.
- SOTA on RoboTwin and real-world tasks; strong generalization in long-horizon and unseen scenarios.
- Benefits from **action-free data**, reducing dependence on expert teleoperation.
</div>
</div>


# 💻 Internships
- *2026.03 - Present*, Embodied Intelligence Algorithm Intern, <img src='./images/xiaomi_logo.svg' style="height: 1.2em; vertical-align: -0.15em;"> [Xiaomi Robotics](https://www.mi.com/), Beijing, China.
  - Research on tactile sensing for robotic manipulation policies.
- *2025.12 - 2026.02*, Embodied Intelligence Algorithm Intern, <img src='./images/cowarobot_logo.png' style="height: 1.2em; vertical-align: -0.15em;"> [COWAROBOT](https://www.cowarobot.com/), Shanghai, China.
  - Dual-arm robot manipulation with GR00T/π₀ policy models. End-to-end pipeline from training to real-robot deployment on Realman and AgileX platforms.
- *2025.09 - 2026.01*, Research Assistant, [HKUST (Guangzhou)](https://www.hkust-gz.edu.cn/), Guangzhou, China.
  - Contributed to Fast-dVLA and FRAPPE projects on VLA acceleration and world modeling.


# 📖 Educations
- *2024.09 - 2027.06 (Expected)*, M.S. in Electronic Science and Technology, [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/) & [Shanghai Institute of Technical Physics, CAS](http://www.sitp.ac.cn/), Shanghai.
  - Advisor: Prof. Shengli Sun (Academician of CAS)
- *2019.09 - 2023.06*, B.E. in Measurement & Control Technology, [Nantong University](https://www.ntu.edu.cn/), Nantong.
  - **Ranked 1st/45**. 7 national awards, 6 provincial awards. Led Jiangsu Province Innovation Training Project.


# 🎖 Honors and Awards

**National Awards**
- *2021* **National 1st Prize**, the 9th National College Students Mechanical Innovation Design Competition
- *2021* **National Special Prize**, the 14th Digital Mathematical Modeling Competition (Ranked 3/1289, 1st Author)
- *2023* National 2nd Prize, the 16th China College Students Computer Design Competition (1st Author)
- *2020* National 2nd Prize, China Engineering Robot Competition (1st Author)
- *2021* National 2nd Prize, the 16th China Computer Game Competition (1st Author)

**Provincial Awards**
- *2021* Provincial 1st Prize, National College Students Engineering Capability Competition, Jiangsu (1st Author)
- *2021* Provincial 1st Prize, Mathematics Modeling Competition, Jiangsu (1st Author)
- *2021* Provincial 1st Prize, the 6th Jiangsu Smart Instrument Competition (1st Author)


# 📄 Patents
- Granted **6 Chinese invention patents**, multiple as first author, covering intelligent data analysis, embedded face detection, robotic assistive devices, and autonomous logistics systems.

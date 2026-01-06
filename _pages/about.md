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

I am a Fifth-year Ph.D. candidate in the [Department of Electronic Engineering](https://www.ee.tsinghua.edu.cn/), [Tsinghua University](https://www.tsinghua.edu.cn/) (THU) since 2021, under the supervision of [Prof. Jian Wang](https://web.ee.tsinghua.edu.cn/wangjian1/zh_CN/index.htm).
I am also very fortunate to collaborate with [Prof. Jintao Wang](https://scholar.google.com/citations?user=0VH0ULYAAAAJ&hl=zh-CN&oi=ao) and [Prof. Yuan Shen](https://oa.ee.tsinghua.edu.cn/~shenyuan/) during my Ph.D. study.
Before that, I also received my Bachelor's degree from the [Department of Electronic Engineering](https://www.ee.tsinghua.edu.cn/), [Tsinghua University](https://www.tsinghua.edu.cn/).

My current research interests and past experience can be summarized as follows:
- 1️⃣ Generative Models: Visual Representation and Generation;
- 2️⃣ Low-level Vision: Visual Low-level Understanding, Processing, and Enhancement;
- 3️⃣ Wireless Communications: AI for Physical Layer.1111


# 📝 Publications

### Visual Generation and Enhancement
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/varsr.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**ICML 2025**] [Visual Autoregressive Modeling for Image Super-Resolution](https://arxiv.org/abs/2501.18993) \\
**Yunpeng Qu**, Kun Yuan, Jinhua Hao, Kai Zhao, Qizhi Xie, Ming Sun, Chao Zhou

[**Code**](https://github.com/quyp2000/VARSR) &nbsp;
[![](https://img.shields.io/github/stars/quyp2000/VARSR?style=social&label=Code+Stars)](https://github.com/quyp2000/VARSR)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/xpsr.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**ECCV 2024**] [XPSR: Cross-modal Priors for Diffusion-based Image Super-resolution](https://link.springer.com/chapter/10.1007/978-3-031-73247-8_17) \\
**Yunpeng Qu**, Kun Yuan, Kai Zhao, Qizhi Xie, Jinhua Hao, Ming Sun, Chao Zhou

[**Code**](https://github.com/quyp2000/XPSR) &nbsp;
[![](https://img.shields.io/github/stars/quyp2000/XPSR?style=social&label=Code+Stars)](https://github.com/quyp2000/XPSR)

</div>
</div>

### Low-level Understanding

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/kvq.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**CVPR 2025**] [KVQ: Boosting Video Quality Assessment via Saliency-guided Local Perception](https://openaccess.thecvf.com/content/CVPR2025/html/Qu_KVQ_Boosting_Video_Quality_Assessment_via_Saliency-guided_Local_Perception_CVPR_2025_paper.html) \\
**Yunpeng Qu**, Kun Yuan, Qizhi Xie, Ming Sun, Chao Zhou, Jian Wang

[**Code**](https://github.com/qyp2000/KVQ) &nbsp;
[![](https://img.shields.io/github/stars/qyp2000/KVQ?style=social&label=Code+Stars)](https://github.com/qyp2000/KVQ)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/qptv2.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**ACM MM 2024**] [QPT V2: Masked Image Modeling Advances Visual Scoring](https://dl.acm.org/doi/jpg/10.1145/3664647.3680721) \\
Qizhi Xie, Kun Yuan, **Yunpeng Qu**, Mingda Wu, Ming Sun, Chao Zhou, Jihong Zhu

[**Code**](https://github.com/KeiChiTse/QPT-V2) &nbsp;
[![](https://img.shields.io/github/stars/KeiChiTse/QPT-V2?style=social&label=Code+Stars)](https://github.com/KeiChiTse/QPT-V2)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/kvqdata.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**CVPR 2024**] [KVQ: Kwai Video Quality Assessment for Short-form Videos](https://openaccess.thecvf.com/content/CVPR2024/papers/Lu_KVQ_Kwai_Video_Quality_Assessment_for_Short-form_Videos_CVPR_2024_paper.jpg) \\
Yiting Lu, Xin Li, Yajing Pei, Kun Yuan, Qizhi Xie, **Yunpeng Qu**, Ming Sun, Chao Zhou, Zhibo Chen

[**Code**](https://lixinustc.github.io/projects/KVQ/) &nbsp;
[![](https://img.shields.io/github/stars/lixinustc/KVQ-Challenge-CVPR-NTIRE2024?style=social&label=Code+Stars)](https://github.com/lixinustc/KVQ-Challenge-CVPR-NTIRE2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/score.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**Preprint**] [Bridging Video Quality Scoring and Justification via Large Multimodal Models](https://arxiv.org/jpg/2506.21011) \\
Qizhi Xie, Kun Yuan, **Yunpeng Qu**, Jiachao Gong, Mingda Wu, Ming Sun, Chao Zhou, Jihong Zhu

</div>
</div>

### AI for Wireless Communications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT 2024</div><img src='images/tldnn.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**IEEE Transactions on Vehicular Technology**] [Enhancing automatic modulation recognition through robust global feature extraction](https://ieeexplore.ieee.org/abstract/document/10744587/) \\
**Yunpeng Qu**, Zhilin Lu, Rui Zeng, Jintao Wang, Jian Wang

[**Code**](https://github.com/qyp2000/TLDNN) &nbsp;
[![](https://img.shields.io/github/stars/qyp2000/TLDNN?style=social&label=Code+Stars)](https://github.com/qyp2000/TLDNN)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WCL 2024</div><img src='images/clasp.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**IEEE Wireless Communications Letters**] [Contrastive Language-Signal Prediction for Automatic Modulation Recognition](https://ieeexplore.ieee.org/abstract/document/10684251) \\
**Yunpeng Qu**, Zhilin Lu, Bingyu Hui, Jintao Wang, Jian Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WCL 2025</div><img src='images/cacd.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**IEEE Wireless Communications Letters**] [Channel-Aware Multi-Domain Feature Extraction for Automatic Modulation Recognition in MIMO Systems](https://arxiv.org/jpg/2512.04899) \\
**Yunpeng Qu**, Yazhou Sun, Bingyu Hui, Jintao Wang, Jian Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VTC 2025-Fall</div><img src='images/hifi.jpg' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[**IEEE Conference on Vehicular Technology**] [Hierarchical Feature Integration for Multi-Signal Automatic Modulation Recognition](https://arxiv.org/jpg/2511.23258) \\
**Yunpeng Qu**, Yazhou Sun, Bingyu Hui, Jian Wang

</div>
</div>

### 📑 Other Papers
- ``AAAI 2026`` [Efficient Reinforcement Learning for Zero-Shot Coordination in Evolving Games](https://arxiv.org/abs/2511.11083) <span style="color:red"></span> <br>
Bingyu Hui, Lebin Yu, Quanming Yao, **Yunpeng Qu**, Xudong Zhang, Jian Wang

# 📖 Educations
- *2021.09 - now:*  Ph.D. Candidate in the Department of Electronic Engineering, Tsinghua University, China.
- *2017.09 - 2021.06:* B.Eng in the Department of Electronic Engineering, Tsinghua University, China.


# 🎖 Honors and Awards
- *2022,2024,2025* Comprehensive Scholarship for Ph.D. Student, Tsinghua University.
- *2022* Finalist Prize at the 1st Construction Robot Innovation Competition, Guoqiang Research Institute, Tsinghua University.
- *2020* **🥈Second place** at the Drone Challenge, 21st China Robot Competition & RoboCup China Open.
- *2020* Comprehensive Scholarship for Undergraduate Student, Tsinghua University.
- *2019* “Hao Du Shu” Scholarship for Undergraduate Student, Tsinghua University.
- *2019* Bronze Award for Student Social Practice, Tsinghua University.
- *2019* Third-class Award of North China Regional Competition, National University Students' Intelligent Car Race.
- *2018,2019* Arts and Cultural Excellence Scholarship for Undergraduate Student, Tsinghua University. 


# 🎓 Service 
- Reviewer (Conferences): CVPR, ICCV, ACM MM, and ICML.
- Reviewer (Journals): IEEE WCL, TVT, and IoT.


# 💻 Internships
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/kuaishou.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[**Kuaishou Technology**] 
Research Intern @ Kuaishou Technology. Focus on Low-level Vision.
</div>
</div>

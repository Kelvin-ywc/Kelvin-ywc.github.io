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

I’m a second-year master’s student at Zhejiang University, supervised by [Prof. Tao Jin](https://person.zju.edu.cn/31402183), and work closely with  [Prof. Zhou Zhao](https://person.zju.edu.cn/zhaozhou). I have published several papers as the first author at top conferences such as ICML, ICLR, ACL and ACM MM. Previously, I was fortunate to intern at the Social Computing Group at Microsoft Research Asia (MSRA), where I worked on streaming video understanding under the mentorship of [Dr. Jianxun Lian](https://www.microsoft.com/en-us/research/people/jialia/).

My research focuses on Multimodal Large Language Models, especially the applications of Vision-Language Models and effective fine-tuning strategies. Recently, I’ve been particularly interested in streaming video understanding, aiming to enable models to continuously interpret live video streams with strong temporal reasoning and timely responses. My long-term goal is to build a truly user-friendly AI assistant—reliable, practical, and proactive—that can understand visual content, communicate naturally, and help users accomplish real-world tasks with a consistently solid experience.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - 2027.06 (now)*, Master Student, Software School, Software Engineer, Zhejiang University. 
- *2020.09 - 2024.06*, Undergraduate, Software College, Software Engineering (International (English)), Northeastern University. 

# 💻 Internships
<!-- - *2026.05 - now*, Tencent Project UP, Hunyuan Multimodal Model Department, Shanghai. -->
- *2026.05 - now*, Tencent Project UP, Hunyuan Foundation Model Department, audio group, Shanghai.
- *2025.08 - 2026.02*, [MSRA, Social Computing Group](https://www.microsoft.com/en-us/research/group/social-computing-beijing/), Beijing.

# 🎖 Honors and Awards
- *2026.02* MSRA Stars of Tomorrow Award.
- *2025.10* National Scholarship.

# 📝 Publications (First Author)

## Streaming Video Understanding
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/proact-vl/framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Proact-VL: A Proactive VideoLLM for Real-Time AI Companions](https://arxiv.org/pdf/2603.03447)

Weicai Yan, Yuhong Dai, Qi Ran, Haodong Li, Wang Lin, Tao Jin, Xing Xie, Hao Liao, Jianxun Lian

- [**Page**](https://proact-vl.github.io/)
- [**Code**](https://aka.ms/proact-vl)

</div>
</div>

<!-- [**Project**](https://github.com/Kelvin-ywc/diff-prompt) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - [**Code**](https://github.com/Kelvin-ywc/diff-prompt). 
</div>
</div> -->


## Parameter-Efficient Fine-Tuning
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/freqadapter/framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Text-Guided Multi-Scale Frequency Representation Adaptation

Weicai Yan, Xinhua Ma, Wang Lin, Tao Jin
- [**Code**](https://github.com/Kelvin-ywc/FreqAdapter)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/diff-prompt/diff-prompt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diff-Prompt: Diffusion-Driven Prompt Generator with Mask Supervision](https://arxiv.org/pdf/2504.21423)

Weicai Yan, Wang Lin, Zirun Guo, Ye Wang, Fangming Feng, Xiaoda Yang, Zehan Wang, Tao Jin

<!-- [**Project**](https://github.com/Kelvin-ywc/diff-prompt) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- [**Code**](https://github.com/Kelvin-ywc/diff-prompt). 
- Prompt Visualization.
<img src='images/diff-prompt/prompt_visualization.png' alt="sym" width="100%">
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/lpi/framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Low-rank Prompt Interaction for Continual Vision-Language Retrieval](https://arxiv.org/pdf/2501.14369)

Weicai Yan, Ye Wang, Wang Lin, Zirun Guo, Zhou Zhao, Tao Jin

<!-- [**Project**](https://github.com/Kelvin-ywc/diff-prompt) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- [**Code**](https://github.com/Kelvin-ywc/LPI). 
<!-- - Demo.
<img src='images/lpi/demo.png' alt="sym" width="60%"> -->
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<span id="-services"></span>
# Services
Reviewer: ICLR 2025, ACM MM 2025, ICLR 2026, ACM MM 2026, NeurIPS 2026, ACL ARR 2026, ICLR 2027



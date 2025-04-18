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

Hello, this is Yingchaojie Feng (封颖超杰). I am currently a Ph.D. candidate in Computer Engineering at Zhejiang University under the supervision of [Prof. Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/) in VAI group.
Before that, I received my B.S. degree from Zhejiang University of Technology.

My research interests include **visual analytics** and **natural language interaction**. Specifically, I design and develop visual and interactive systems to facilitate the understanding and utility of NLP models for downstream tasks, including creative tasks (e.g., text-to-image, painting-to-poetry) and analytical tasks (e.g., NLI-based data analysis).


# 🔥 News
- *2024.11*: &nbsp;🎉 Our paper about [LLM-powered business intelligence platform](https://luoxuanweng.site/pdfs/DataLab.pdf) is accepted by IEEE ICDE, 2025!
- *2024.11*: &nbsp;🎉 Our paper about [insight exploration for LLM-powered data analysis](https://luoxuanweng.site/pdfs/InsightLens.pdf) is accepted by IEEE TVCG, (Proc. of PacificVis 2025)!
- *2024.04*: &nbsp;🎉 Our paper about visual analysis of LLM-based Autonomous Systems ([AgentLens](https://ieeexplore.ieee.org/document/10520238)) is accepted by IEEE TVCG, 2024!
- *2023.07*: &nbsp;📢 I presented "PromptMagician: Interactive Prompt Engineering for Text-to-Image Creation" at [ChinaVis 2023](https://chinavis.org/2023/) in Chongqing.
- *2023.07*: &nbsp;🎉 Our paper "PromptMagician: Interactive Prompt Engineering for Text-to-Image Creation" is finally accepted by IEEE VIS 2023!
- *2023.01*: &nbsp;🎉 Our paper "XNLI: Explaining and Diagnosing NLI-based Visual Data Analysis" is finally accepted by IEEE TVCG, 2023!
<!-- - *2021.07*: &nbsp;📢 I presented "iPoet: interactive painting poetry creation with visual multimodal analysis" at ChinaVis 2021 in Wuhan. -->

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2025</div><img src='images/DataLab.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DataLab: A Unified Platform for LLM-Powered Business Intelligence](https://luoxuanweng.site/pdfs/DataLab.pdf)

Luoxuan Weng, Yinghao Tang, **Yingchaojie Feng**, Zhuo Chang, Peng Chen, Ruiqin Chen, Haozhe Feng, Chen Hou, Danqing Huang, Yang Li, Huaming Rao, Haonan Wang, Canshi Wei, Xiaofeng Yang, Yuhui Zhang, Yifeng Zheng, Xiuqi Huang, Minfeng Zhu, Yuxin Ma, Bin Cui, Wei Chen

IEEE International Conference on Data Engineering, 2025

[PDF](https://luoxuanweng.site/pdfs/DataLab.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2025</div><img src='images/InsightLens.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InsightLens: Augmenting LLM-Powered Data Analysis with Interactive Insight Management and Navigation](https://luoxuanweng.site/pdfs/InsightLens.pdf)

Luoxuan Weng, Xingbo Wang, Junyu Lu, **Yingchaojie Feng**, Yihan Liu, Haozhe Feng, Danqing Huang, Wei Chen

IEEE Transactions on Visualization and Computer Graphics (Proc. of PacificVis), 2025

[PDF](https://luoxuanweng.site/pdfs/InsightLens.pdf) \| [Video](https://luoxuanweng.site/videos/InsightLens.mp4)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/jailbreaklens.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JailbreakLens: Visual Analysis of Jailbreak Attacks Against Large Language Models](https://arxiv.org/abs/2404.08793)

**Yingchaojie Feng**, Zhizhang Chen, Zhining Kang, Sijia Wang, Minfeng Zhu, Wei Zhang, and Wei Chen

arXiv Preprint, 2024

[arXiv](https://arxiv.org/abs/2404.08793)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2024</div><img src='images/agentLens.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AgentLens: Visual Analysis for Agent Behaviors in LLM-based Autonomous Systems](https://ieeexplore.ieee.org/document/10520238)

Jiaying Lu, Bo Pan, Jieyi Chen, **Yingchaojie Feng**, Jingyuan Hu, Yuchen Peng, Wei Chen

IEEE Transactions on Visualization and Computer Graphics, 2024.

[IEEEXplore](https://ieeexplore.ieee.org/document/10520238) \| [arXiv](https://arxiv.org/abs/2402.08995) \| [Video](https://www.youtube.com/watch?v=gq0006YQx4M)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VIS 2023</div><img src='images/promptmagician.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PromptMagician: Interactive Prompt Engineering for Text-to-Image Creation](https://ieeexplore.ieee.org/abstract/document/10296017)

**Yingchaojie Feng**, Xingbo Wang, Kam Kwai Wong, Sijia Wang, Yuhong Lu, Minfeng Zhu, Baicheng Wang, Wei Chen

IEEE VIS Conference 2023

[IEEEXplore](https://ieeexplore.ieee.org/abstract/document/10296017) \| [arXiv](https://arxiv.org/abs/2307.09036) \| [Github](https://github.com/YingchaojieFeng/PromptMagician) \| [Video](https://youtu.be/QEqHAFhAWRI)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2023</div><img src='images/xnli.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[XNLI: Explaining and Diagnosing NLI-based Visual Data Analysis](https://ieeexplore.ieee.org/abstract/document/10026499)

**Yingchaojie Feng**, Xingbo Wang, Bo Pan, Kam Kwai Wong, Yi Ren, Shi Liu, Zihan Yan, Yuxin Ma, Huamin Qu, Wei Chen

IEEE Transactions on Visualization and Computer Graphics, 2023.

[IEEEXplore](https://ieeexplore.ieee.org/abstract/document/10026499) \| [arXiv](https://arxiv.org/abs/2301.10385) \| [Video](https://youtu.be/zj1arPjEYI8)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ChinaVis 2021</div><img src='images/ipoet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[iPoet: interactive painting poetry creation with visual multimodal analysis](https://link.springer.com/article/10.1007/s12650-021-00780-0)

**Yingchaojie Feng**, Jiazhou Chen, Keyu Huang, Jason K. Wong, Hui Ye, Wei Zhang, Rongchen Zhu, Xiaonan Luo, Wei Chen

Journal of Visualization, 2021

[PDF](https://doi.org/10.1007/s12650-021-00780-0) \| [DOI](https://doi.org/10.1007/s12650-021-00780-0)

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- - ``ICML 2023`` [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->
- ``arXiv`` [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943), Bo Pan, Jiaying Lu, Ke Wang, Li Zheng, Zhen Wen, **Yingchaojie Feng**, Minfeng Zhu, Wei Chen
- ``arXiv`` [CultiVerse: Towards Cross-Cultural Understanding for Paintings with Large Language Model](https://arxiv.org/abs/2405.00435), Wei Zhang, Wong Kam-Kwai, Biying Xu, Yiwen Ren, Yuhuai Li, Minfeng Zhu, **Yingchaojie Feng**, Wei Chen
- ``JCST 2023`` [Computational Approaches for Traditional Chinese Painting: From the "Six Principles of Painting" Perspective](https://arxiv.org/abs/2307.14227), Wei Zhang, Jianwei Zhang, Kam Kwai Wong, Yifang Wang, **Yingchaojie Feng**, Luwei Wang, Wei Chen
- ``FITEE 2023`` [A visual analysis approach for data imputation via multi-party tabular data correlation strategies](https://link.springer.com/article/10.1631/FITEE.2300480), Haiyang Zhu, Dongmin Han, Jiacheng Pan, Yating Wei, **Yingchaojie Feng**, Luoxuan Weng, Ketian Mao, Yuankai Xing, Jianshu Lv, Qiucheng Wan, Wei Chen
- ``VI 2021`` [Visualizing large-scale high-dimensional data via hierarchical embedding of KNN graphs](https://doi.org/10.1016/j.visinf.2021.06.002), Haiyang Zhu, Minfeng Zhu, **Yingchaojie Feng**, Deng Cai, Yuanzhe Hu, Shilong Wu, Xiangyang Wu, Wei Chen
- ``VI 2021`` [G6: A web-based library for graph visualization](https://doi.org/10.1016/j.visinf.2021.12.003), Yanyan Wang, Zhanning Bai, Zhifeng Lin, Xiaoqing Dong, **Yingchaojie Feng**, Jiacheng Pan, Wei Chen


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
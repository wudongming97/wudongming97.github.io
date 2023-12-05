---
permalink: /
title: "Dongming Wu"
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
From 2019 to present, I am a PhD student in Department of Computer Science, Beijing Institute of Technology, advised by <a href="https://shenjianbing.github.io/">Prof. Jianbing Shen</a>. 

From 2022 to present, I am a research intern at Foundation model group in MEGVII Technology, supervised by <a href="https://scholar.google.com.hk/citations?user=YI0sRroAAAAJ&hl=zh-CN">Tiancai Wang</a> and <a href="https://scholar.google.com/citations?user=yuB-cfoAAAAJ&hl=zh-CN&oi=ao">Xiangyu Zhang</a>. 

In 2021-2022, I was a research intern at Inception Institute of Artificial Intelligence, UAE, supervised by <a href="https://xingpingdong.github.io/">Xingping Dong</a> and <a href="https://scholar.google.com/citations?user=z84rLjoAAAAJ&hl=zh-CN&oi=ao">Prof. Ling Shao</a>.

In 2019, I recevied my Bachelor's degree from the Class of Xu, Beijing Institute of Technology. 

My current research interests are in the areas of (1) **vision-language learning** and (2) **autonomous driving**.


<span class='anchor' id='-news'></span>

# News
- 2023.10: I'm awarded National Scholarship!
- 2023.07: One paper (OnlineRefer) is accepted by ICCV2023.
- 2023.06: We rank the 1st place at [OpenLane Topology](https://opendrivelab.com/AD23Challenge.html#openlane_topology) in CVPR2023 Autonomous Driving Challenge. [Solution](https://arxiv.org/pdf/2306.09590.pdf) is released.
- 2023.03: One paper (Refering Multi-Object Tracking) is accepted by CVPR2023.
- 2023.03: My personal homepage is created! Welcome!


<span class='anchor' id='-publications'></span>
# Publications

## Preprint Papers:

- **Merlin:Empowering Multimodal LLMs with Foresight Minds**\\
En Yu, Liang Zhao, Yana Wei, Jinrong Yang, Dongming Wu, Lingyu Kong, Haoran Wei, Tiancai Wang, Zheng Ge, Xiangyu Zhang, Wenbing Tao\\
|2023|[Paper](https://arxiv.org/abs/2312.00589)|

- **Language prompt for autonomous driving**\\
Dongming Wu, Wencheng Han, Tiancai Wang, Yingfei Liu, Xiangyu Zhang, Jianbing Shen\\
|2023|[Paper](https://arxiv.org/pdf/2309.04379.pdf)|

- **TopoMLP: A Simple yet Strong Pipeline for Driving Topology Reasoning**\\
Dongming Wu, Jiahao Chang, Fan Jia, Yingfei Liu, Tiancai Wang, Jianbing Shen\\
|2023|[Paper](https://arxiv.org/pdf/2310.06753.pdf)|[Code](https://github.com/wudongming97/TopoMLP)|


- **The 1st-place Solution for CVPR 2023 OpenLane Topology in Autonomous Driving Challenge**\\
Dongming Wu, Fan Jia, Jiahao Chang, Zhuoling Li, Jianjian Sun, Chunrui Han, Shuailin Li, Yingfei Liu, Zheng Ge, Tiancai Wang\\
|2023|[Paper](https://arxiv.org/pdf/2306.09590.pdf)|[Code](https://github.com/wudongming97/TopoMLP)|

## Conference Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/onlinerefer.jpg' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**OnlineRefer: A Simple Online Baseline for Referring Video Object Segmentation**\\
|**ICCV 2023**|[Paper](https://arxiv.org/abs/2307.09356)|[Code](https://github.com/wudongming97/OnlineRefer)|

Dongming Wu, Tiancai Wang, Yuang Zhang, Xiangyu Zhang, Jianbing Shen

- <strong style="color:green"> OnlineRefer is the first to challenge the widespread belief that only offline models can deal well with RVOS and makes online RVOS great again.</strong>
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/rmot.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Referring Multi-Object Tracking** \\
|**CVPR 2023**|[Paper](https://arxiv.org/abs/2303.03366)|[Code](https://github.com/wudongming97/RMOT)|

Dongming Wu, Wencheng Han, Tiancai Wang, Xingping Dong, Xiangyu Zhang, Jianbing Shen

- <strong style="color:green">RMOT is a new referring understanding task that can detect and track an arbitrary number of objects following human instruction. We propose the first RMOT benckmark Refer-KITTI, and a baseline model TransRMOT.</strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/msla.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-Level Representation Learning with Semantic Alignment for Referring Video Object Segmentation** \\
|**CVPR 2022**|[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Multi-Level_Representation_Learning_With_Semantic_Alignment_for_Referring_Video_Object_CVPR_2022_paper.pdf)|

Dongming Wu, Xingping Dong, Ling Shao, Jianbing Shen 

</div>
</div>



## Journal Papers:

- **Person re-identification by context-aware part attention and multi-head collaborative learning**(**TIFS**)\\
Dongming Wu, Mang Ye, Gaojie Lin, Xin Gao, Jianbing Shen \\
|2021|[Paper](https://repository.kaust.edu.sa/bitstream/handle/10754/668975/tifs21cpa-vrid-v5_Xin-comments%20deleted.pdf?sequence=4)|

- **Reducing estimation bias via triplet-average deep deterministic policy gradient**(**TNNLS**) \\
Dongming Wu, Xingping Dong, Jianbing Shen, Steven CH Hoi \\
|2020|[Paper](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=6923&context=sis_research)|



<span class='anchor' id='-honors'></span>
# Honors

* National Scholarship, Ministry of Education China.
* The 1st place at [OpenLane Topology](https://opendrivelab.com/AD23Challenge.html#openlane_topology) in CVPR2023 Autonomous Driving Challenge ($15,000), Shanghai AI Lab and Huawei.
* HuaRuiShiJi(华瑞世纪) Scholarship, Beijing Institute of Technology.

<span class='anchor' id='-service'></span>
# Service

Reviewer for CVPR'2023, ICCV'2023

Reviewer for TIP, TNNLS, TMM, PR, etc






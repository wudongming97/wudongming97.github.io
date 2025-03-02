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
From 2019.09 to present, I am a PhD student in Department of Computer Science, Beijing Institute of Technology, advised by <a href="https://scholar.google.com/citations?user=_Q3NTToAAAAJ&hl=en">Prof. Jianbing Shen</a>. 

From 2022.06 to present, I am a research intern at Foundation model group in MEGVII Technology, supervised by <a href="https://scholar.google.com.hk/citations?user=YI0sRroAAAAJ&hl=zh-CN">Tiancai Wang</a> and <a href="https://scholar.google.com/citations?user=yuB-cfoAAAAJ&hl=zh-CN&oi=ao">Xiangyu Zhang</a>. 

From 2024.09 to 2025.01, I am a visiting student at Mohamed bin Zayed University of Artificial Intelligence, supervised by <a href="https://mbzuai.ac.ae/study/faculty/rao-muhammad-anwer/">Prof. Rao Muhammad Anwer</a> and <a href="https://sites.google.com/view/fahadkhans">Prof. Fahad Shahbaz Khan</a>. 

In 2021.05-2022.05, I was a research intern at Inception Institute of Artificial Intelligence, UAE, supervised by <a href="https://xingpingdong.github.io/">Xingping Dong</a> and <a href="https://scholar.google.com/citations?user=z84rLjoAAAAJ&hl=zh-CN&oi=ao">Prof. Ling Shao</a>.

In 2019.06, I recevied my Bachelor's degree from the Class of Xu, Beijing Institute of Technology. 

My current research interests are in the areas of (1) **Vision-language learning**, (2) **Multi-modal LLM** and (3) **Embodied Agent**. My ultimate goal is to build a human-like agent for perceiving real-life environments and performing decision-making.


<span class='anchor' id='-news'></span>

# News
- 2025.02: One paper (DrivingSphere) is accepted by CVPR2025.
- 2024.12: One paper (NuPrompt) is accepted by AAAI2025.
- 2024.07: One paper (Merlin) is accepted by ECCV2024.
- 2024.05: I'm awarded Excellent Doctoral Thesis Seedling Fund (优秀博士论文育苗基金).
- 2024.01: One paper (TopoMLP) is accepted by ICLR2024.
- 2023.10: I'm awarded National Scholarship!


<span class='anchor' id='-publications'></span>
# Publications

## Preprint Papers:

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Submission</div><img src='images/ragnet.jpg' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RAGNet: Large-scale Reasoning-based Affordance Segmentation Benchmark towards General Grasping** \\
|**In Submission**|

Dongming Wu, Yanping Fu, Saike Huang, Yingfei Liu, Fan Jia, Nian Liu, Feng Dai, Tiancai Wang, Rao Muhammad Anwer, Fahad Shahbaz Khan, Jianbing Shen

- <strong style="color:green"> We present a large-scale reasoning-based affordance segmentation benchmark RAGNet and introduce a comprehensive affordance-based grasping framework AffordanceNet.</strong>
</div>
</div>


- **Is a 3D-Tokenized LLM the Key to Reliable Autonomous Driving?**\\
Yifan Bai\*, Dongming Wu\*, Yingfei Liu, Fan Jia, Weixin Mao, Ziheng Zhang, Yucheng Zhao, Jianbing Shen, Xing Wei, Tiancai Wang, Xiangyu Zhang (*Equal Contributions) \\
|2024|[Paper](https://arxiv.org/pdf/2405.18361)|

- **Bootstrapping Referring Multi-Object Tracking**\\
Yani Zhang, Dongming Wu, Wencheng Han, Xingping Dong \\
|2024|[Paper](https://arxiv.org/pdf/2406.05039)|[Code](https://github.com/zyn213/TempRMOT)|


## Conference Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/drivingsphere.jpg' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DrivingSphere: Building a High-fidelity 4D World for Closed-loop Simulation** \\
|**CVPR 2025**|[Paper](https://arxiv.org/abs/2411.11252)|[Code](https://yanty123.github.io/DrivingSphere/)|

Tianyi Yan, Dongming Wu, Wencheng Han, Junpeng Jiang, Xia Zhou, Kun Zhan, Cheng-zhong Xu, Jianbing Shen

- <strong style="color:green"> DrivingSphere is a novel geometry-aware closed-loop simulation framework that captures 2D visual and 3D geometric properties while seamlessly integrating with vision-based end-to-end driving agents.</strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/nuprompt.jpg' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Language prompt for autonomous driving** \\
|**AAAI 2025**|[Paper](https://arxiv.org/pdf/2309.04379.pdf)|[Code](https://github.com/wudongming97/Prompt4Driving)|

Dongming Wu, Wencheng Han, Tiancai Wang, Yingfei Liu, Xiangyu Zhang, Jianbing Shen

- <strong style="color:green"> NuPrompt is the first dataset specializing in multiple 3D objects of interest from video domain for autonomous driving.</strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/merlin.png' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Merlin:Empowering Multimodal LLMs with Foresight Minds**\\
|**ECCV 2024**|[Paper](https://arxiv.org/abs/2312.00589)|[Code](https://github.com/Ahnsun/merlin)|

En Yu, Liang Zhao, Yana Wei, Jinrong Yang, Dongming Wu, Lingyu Kong, Haoran Wei, Tiancai Wang, Zheng Ge, Xiangyu Zhang, Wenbing Tao

- <strong style="color:green"> Merlin is a groundbreaking model capable of generating natural language responses that are intricately linked with object trajectories of multiple images.</strong>
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/topomlp.jpg' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TopoMLP: A Simple yet Strong Pipeline for Driving Topology Reasoning**\\
|**ICLR 2024**|[Paper](https://arxiv.org/pdf/2310.06753.pdf)|[Code](https://github.com/wudongming97/TopoMLP)|

Dongming Wu, Jiahao Chang, Fan Jia, Yingfei Liu, Tiancai Wang, Jianbing Shen

- <strong style="color:green"> TopoMLP is the 1st solution for 1st OpenLane Topology in Autonomous Driving Challenge. It suggests a first-detect-then-reason philosophy for better topology prediction.</strong>
</div>
</div>



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


## Technical Report:

- **The 1st-place Solution for CVPR 2023 OpenLane Topology in Autonomous Driving Challenge**\\
Dongming Wu, Fan Jia, Jiahao Chang, Zhuoling Li, Jianjian Sun, Chunrui Han, Shuailin Li, Yingfei Liu, Zheng Ge, Tiancai Wang\\
|2023|[Paper](https://arxiv.org/pdf/2306.09590.pdf)|[Code](https://github.com/wudongming97/TopoMLP)|



<span class='anchor' id='-honors'></span>
# Honors

* Excellent Doctoral Thesis Seedling Fund(优秀博士论文育苗基金), Beijing Institute of Technology.
* National Scholarship, Ministry of Education China.
* The 1st place at [OpenLane Topology](https://opendrivelab.com/AD23Challenge.html#openlane_topology) in CVPR2023 Autonomous Driving Challenge ($15,000), Shanghai AI Lab and Huawei.
* ChinaCentury(华瑞世纪) Scholarship, Beijing Institute of Technology.

<span class='anchor' id='-service'></span>
# Service
Invited Reviewer for conferences:
* CVPR 2023,2024,2025
* ICCV 2023
* ECCV 2024
* ICLR 2025
* AAAI 2025

Invited Reviewer for journals:
* International Journal of Computer Vision (IJCV) 
* IEEE Transactions on Image Processing (TIP)
* IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
* IEEE Transactions on Multimedia (TMM)
* IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
* IEEE Transactions on Intelligent Vehicles (TIV)
* Pattern Recognition (PR)
* Neurocomputing






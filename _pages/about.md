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

I am currently a Postdoctoral Fellow at MMLab, the Chinese University of Hong Kong, and at CPII, working with Prof. Xiangyu Yue.

<!-- In 2025.06, I received my PhD degree in Department of Computer Science, Beijing Institute of Technology, advised by [Prof. Jianbing Shen](https://scholar.google.com/citations?user=_Q3NTToAAAAJ&hl=en). 

In 2019.06, I received my Bachelor degree from the Class of Xu at the same university. -->

My current research interests lie in vision-language learning, multimodal large language models (MLLMs), and embodied agents. (1) During my graduate studies, I focused on building intelligent perception models that understand visual and linguistic information. (2) More recently, I've been exploring decision-making systems capable of actively interacting with both humans and dynamic environments. Ultimately, my goal is to develop human-like agents that can perceive real-world environments and make autonomous decisions, moving us closer to achieving artificial general intelligence (AGI). Two articles that have deeply inspired my thinking are [The Bitter Lesson](https://www.cs.utexas.edu/~eunsol/courses/data/bitter_lesson.pdf) and [The Second Half](https://ysymyth.github.io/The-Second-Half/).

**I am always open to collaboration and discussions about the latest advancements in the field. Feel free to reach out!**

# 🔥 News
<div style="height: 200px; overflow-y: auto; border: 1px solid #ddd; border-radius: 8px; padding: 1rem; background: #fdfdfd;">
<ul>
<li><em>2026.04</em>: &nbsp;🎉 🎉 One paper (SpaceVista) is accpeted by ICML 2026. Congrats to Peiwen!</li>
<li><em>2026.02</em>: &nbsp;🎉 🎉 One paper (GEGround) is accpeted by CVPR Findings 2026. It ranks first on EmbodiedScan Challenge.</li>
<li><em>2026.01</em>: &nbsp;🎉 🎉 One paper (AutoFly) is accpeted by ICLR 2026.</li>
<li><em>2025.09</em>: I join in CUHK MMLab and CPII as a Postdoctoral Fellow.</li>
<li><em>2025.06</em>: One paper (RAGNet) is accepted by ICCV2025.</li>
<li><em>2025.06</em>: I successfully defended my Ph.D. thesis. I'm awarded Outstanding Graduates of Beijing (北京市优秀毕业生).</li>
<li><em>2025.02</em>: One paper (DrivingSphere) is accepted by CVPR2025.</li>
<li><em>2024.12</em>: One paper (NuPrompt) is accepted by AAAI2025.</li>
<li><em>2024.05</em>: I'm awarded Excellent Doctoral Thesis Seedling Fund (优秀博士论文育苗基金).</li>
<li><em>2024.01</em>: One paper (TopoMLP) is accepted by ICLR2024.</li>
</ul>
</div>

# 📝 Publications


**Conference & Preprint**


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/spatialvista.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpaceVista: All-Scale Visual Spatial Reasoning from mm to km](https://arxiv.org/abs/2510.09606)

Peiwen Sun, Shiqiang Lang, **Dongming Wu**, Yi Ding, Kaituo Feng, Huadai Liu, Zhen Ye, Rui Liu, Yun-Hui Liu, Jianan Wang, Xiangyu Yue

\|[**Paper**](https://arxiv.org/abs/2510.09606)\|
- It is the first attempt to broaden the all-scale spatial intelligence of MLLMs to the best of our knowledge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src='images/deground.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEGround: An Effective Baseline for Ego-centric 3D Visual Grounding With a Homogeneous Framework](https://arxiv.org/abs/2506.05199)

Yani Zhang\*, **Dongming Wu**\*, Yingfei Liu, Hao Shi, Tiancai Wang, Xingping Dong (\*Equal Contributions)

\|[**Paper**](https://arxiv.org/abs/2506.05199)\|[**Code**](https://github.com/zyn213/DEGround)\|
- DEGround ranks first on EmbodiedScan Challenge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/autofly.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoFly: Vision-Language-Action Model for UAV Autonomous Navigation in the Wild](https://arxiv.org/abs/2602.09657)

Xiaolou Sun, Wufei Si, Wenhui Ni, Yuntian Li, **Dongming Wu**, Fei Xie, Runwei Guan, He-Yang Xu, Henghui Ding, Yuan Wu, Yutao Yue, Yongming Huang, Hui Xiong

\|[**Paper**](https://arxiv.org/abs/2602.09657)\|[**Project**](https://xiaolousun.github.io/AutoFly)\|
- AutoFly is a Vision-Language-Action (VLA) model for autonomous UAV navigation in real-world environments, with a pseudo-depth encoder and progressive two-stage training.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/ragnet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAGNet: Large-scale Reasoning-based Affordance Segmentation Benchmark towards General Grasping](https://arxiv.org/abs/2507.23734)

**Dongming Wu**, Yanping Fu, Saike Huang, Yingfei Liu, Fan Jia, Nian Liu, Feng Dai, Tiancai Wang, Rao Muhammad Anwer, Fahad Shahbaz Khan, Jianbing Shen

\|[**Paper**](https://arxiv.org/abs/2507.23734)\|[**Code**](https://github.com/wudongming97/AffordanceNet)\|
- We present a large-scale reasoning-based affordance segmentation benchmark RAGNet and introduce a comprehensive affordance-based grasping framework AffordanceNet.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/drivingsphere.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DrivingSphere: Building a High-fidelity 4D World for Closed-loop Simulation](https://arxiv.org/abs/2411.11252)

Tianyi Yan, **Dongming Wu**, Wencheng Han, Junpeng Jiang, Xia Zhou, Kun Zhan, Cheng-zhong Xu, Jianbing Shen

\|[**Paper**](https://arxiv.org/abs/2411.11252)\|[**Project**](https://yanty123.github.io/DrivingSphere/)\|
- DrivingSphere is a novel geometry-aware closed-loop simulation framework that captures 2D visual and 3D geometric properties while seamlessly integrating with vision-based end-to-end driving agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/3dllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Is a 3D-Tokenized LLM the Key to Reliable Autonomous Driving?](https://arxiv.org/pdf/2405.18361)

Yifan Bai\*, **Dongming Wu**\*, Yingfei Liu, Fan Jia, Weixin Mao, Ziheng Zhang, Yucheng Zhao, Jianbing Shen, Xing Wei, Tiancai Wang, Xiangyu Zhang (\*Equal Contributions)

\|[**Paper**](https://arxiv.org/pdf/2405.18361)\|
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/nuprompt.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Language prompt for autonomous driving](https://arxiv.org/pdf/2309.04379.pdf)

**Dongming Wu**, Wencheng Han, Tiancai Wang, Yingfei Liu, Xiangyu Zhang, Jianbing Shen

\|[**Paper**](https://arxiv.org/pdf/2309.04379.pdf)\|[**Code**](https://github.com/wudongming97/Prompt4Driving)\|
- We propose a new large-scale language prompt set for driving scenes, named NuPrompt. As far as we know, it is the first dataset specializing in multiple 3D objects of interest from video domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/rmotv2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bootstrapping Referring Multi-Object Tracking](https://arxiv.org/pdf/2406.05039)

Yani Zhang\*, **Dongming Wu**\*, Wencheng Han, Xingping Dong  (\*Equal Contributions)

\|[**Paper**](https://arxiv.org/pdf/2406.05039)\|[**Code**](https://github.com/zyn213/TempRMOT)\|
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/merlin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Merlin: Empowering Multimodal LLMs with Foresight Minds](https://arxiv.org/abs/2312.00589)

En Yu, Liang Zhao, Yana Wei, Jinrong Yang, **Dongming Wu**, Lingyu Kong, Haoran Wei, Tiancai Wang, Zheng Ge, Xiangyu Zhang, Wenbing Tao

\|[**Paper**](https://arxiv.org/abs/2312.00589)\|[**Code**](https://github.com/Ahnsun/merlin)\|
- Merlin is a groundbreaking model capable of generating natural language responses that are intricately linked with object trajectories of multiple images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/topomlp.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TopoMLP: A Simple yet Strong Pipeline for Driving Topology Reasoning](https://arxiv.org/pdf/2310.06753.pdf)

**Dongming Wu**, Jiahao Chang, Fan Jia, Yingfei Liu, Tiancai Wang, Jianbing Shen

\|[**Paper**](https://arxiv.org/pdf/2310.06753.pdf)\|[**Code**](https://github.com/wudongming97/TopoMLP)\|
- TopoMLP is the 1st solution for 1st OpenLane Topology in Autonomous Driving Challenge. It suggests a first-detect-then-reason philosophy for better topology prediction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/onlinerefer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OnlineRefer: A Simple Online Baseline for Referring Video Object Segmentation](https://arxiv.org/abs/2307.09356)

**Dongming Wu**, Tiancai Wang, Yuang Zhang, Xiangyu Zhang, Jianbing Shen

\|[**Paper**](https://arxiv.org/abs/2307.09356)\|[**Code**](https://github.com/wudongming97/OnlineRefer)\|
- OnlineRefer is the first to challenge the widespread belief that only offline models can deal well with RVOS and makes online RVOS great again.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/rmot.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Referring Multi-Object Tracking](https://arxiv.org/abs/2303.03366)

**Dongming Wu**, Wencheng Han, Tiancai Wang, Xingping Dong, Xiangyu Zhang, Jianbing Shen

\|[**Paper**](https://arxiv.org/abs/2303.03366)\|[**Code**](https://github.com/wudongming97/RMOT)\|
- RMOT is a new referring understanding task that can detect and track an arbitrary number of objects following human instruction. We propose the first RMOT benchmark Refer-KITTI, and a baseline model TransRMOT.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/msla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Level Representation Learning with Semantic Alignment for Referring Video Object Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Multi-Level_Representation_Learning_With_Semantic_Alignment_for_Referring_Video_Object_CVPR_2022_paper.pdf)

**Dongming Wu**, Xingping Dong, Ling Shao, Jianbing Shen

\|[**Paper**](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_Multi-Level_Representation_Learning_With_Semantic_Alignment_for_Referring_Video_Object_CVPR_2022_paper.pdf)\|
</div>
</div>

**Journal**
- **Person re-identification by context-aware part attention and multi-head collaborative learning** (TIFS). Dongming Wu, Mang Ye, Gaojie Lin, Xin Gao, Jianbing Shen. 2021. [Paper](https://repository.kaust.edu.sa/bitstream/handle/10754/668975/tifs21cpa-vrid-v5_Xin-comments%20deleted.pdf?sequence=4)
- **Reducing estimation bias via triplet-average deep deterministic policy gradient** (TNNLS). Dongming Wu, Xingping Dong, Jianbing Shen, Steven CH Hoi. 2020. [Paper](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=6923&context=sis_research)

**Technical Report**
- **The 1st-place Solution for CVPR 2023 OpenLane Topology in Autonomous Driving Challenge**. Dongming Wu, Fan Jia, Jiahao Chang, Zhuoling Li, Jianjian Sun, Chunrui Han, Shuailin Li, Yingfei Liu, Zheng Ge, Tiancai Wang. 2023. [Paper](https://arxiv.org/pdf/2306.09590.pdf) \| [Code](https://github.com/wudongming97/TopoMLP)

# 🎖 Honors
<div style="display:flex; flex-direction:column; gap:10px; margin-top:10px;">
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">Excellent Doctoral Dissertation Beijing Institute of Technology (北京理工大学优秀博士论文)</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">Outstanding Graduates of Beijing (北京市优秀毕业生)</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">Outstanding Graduates of Beijing Institute of Technology (北京理工大学优秀毕业生)</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">Excellent Doctoral Dissertation Seedling Fund of Beijing Institute of Technology (北京理工大学优秀博士论文育苗基金)</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">National Scholarship (国家奖学金), Ministry of Education China</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">ChinaCentury Scholarship (华瑞世纪奖学金), Beijing Institute of Technology</div>
</div>

# 🏆 Challenge Awards
<div style="display:flex; flex-direction:column; gap:10px; margin-top:10px;">
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">The 1st place at EmbodiedScan Challenge, Shanghai AI Lab</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">The 1st place at OpenLane Topology in CVPR2023 Autonomous Driving Challenge ($15,000), Shanghai AI Lab and Huawei</div>
</div>

# 📖 Educations
<div style="display:flex; flex-direction:column; gap:10px; margin-top:10px;">
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;"><strong style="font-style:italic;">2025.06</strong> &nbsp;PhD, Department of Computer Science, Beijing Institute of Technology, advised by <a href="https://scholar.google.com/citations?user=_Q3NTToAAAAJ&hl=en">Prof. Jianbing Shen</a>.</div>
  <div style="padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;"><strong style="font-style:italic;">2019.06</strong> &nbsp;Bachelor, Class of Xu, Beijing Institute of Technology.</div>
</div>

# 💻 Internships
<div style="display:flex; flex-direction:column; gap:12px; margin-top:10px;">
  <div style="display:flex; align-items:center; gap:14px; padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">
    <img src="images/logo_dexmal.png" alt="Dexmal" width="56" height="56" style="border-radius:8px; object-fit:contain; background:#fff; padding:2px;" />
    <div><strong>Dexmal</strong>, Research Intern. Mentor: <a href="https://scholar.google.com.hk/citations?user=pF9KA1sAAAAJ&hl=zh-CN">Yingfei Liu</a>, <a href="https://scholar.google.com.hk/citations?user=YI0sRroAAAAJ&hl=zh-CN">Tiancai Wang</a>.</div>
  </div>
  <div style="display:flex; align-items:center; gap:14px; padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">
    <img src="images/logo_mbzuai.png" alt="MBZUAI" width="56" height="56" style="border-radius:8px; object-fit:contain; background:#fff; padding:2px;" />
    <div><strong>MBZUAI</strong>, Visiting Student. Mentor: <a href="https://mbzuai.ac.ae/study/faculty/rao-muhammad-anwer/">Prof. Rao Muhammad Anwer</a>, <a href="https://sites.google.com/view/fahadkhans">Prof. Fahad Shahbaz Khan</a>.</div>
  </div>
  <div style="display:flex; align-items:center; gap:14px; padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">
    <img src="images/logo_megvii.jpeg" alt="MEGVII" width="56" height="56" style="border-radius:8px; object-fit:contain; background:#fff; padding:2px;" />
    <div><strong>MEGVII</strong>, Research Intern. Mentor: <a href="https://scholar.google.com.hk/citations?user=YI0sRroAAAAJ&hl=zh-CN">Tiancai Wang</a>, <a href="https://scholar.google.com/citations?user=yuB-cfoAAAAJ&hl=zh-CN&oi=ao">Xiangyu Zhang</a>.</div>
  </div>
  <div style="display:flex; align-items:center; gap:14px; padding:10px 12px; border:1px solid #e8e8e8; border-radius:10px; background:#fafafa;">
    <img src="images/logo_IIAI.png" alt="IIAI" width="56" height="56" style="border-radius:8px; object-fit:contain; background:#fff; padding:2px;" />
    <div><strong>IIAI</strong>, Research Intern. Mentor: <a href="https://xingpingdong.github.io/">Xingping Dong</a>, <a href="https://scholar.google.com/citations?user=z84rLjoAAAAJ&hl=zh-CN&oi=ao">Prof. Ling Shao</a>.</div>
  </div>
</div>

# 🔧 Service
**Conferences:** 
<ul>
  <li>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) </li>
  <li>IEEE International Conference on Computer Vision (ICCV)</li>
  <li>European Conference on Computer Vision (ECCV)</li>
  <li>Conference on Neural Information Processing Systems (NeurIPS)</li>
  <li>International Conference on Learning Representations (ICLR)</li>
  <li>AAAI Conference on Artificial Intelligence (AAAI) </li>
</ul>

**Journals:** 
<ul>
  <li>International Journal of Computer Vision (IJCV)</li>
  <li>IEEE Transactions on Image Processing (TIP)</li>
  <li>IEEE Transactions on Neural Networks and Learning Systems (TNNLS)</li>
  <li>IEEE Transactions on Multimedia (TMM)</li>
  <li>IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)</li>
  <li>IEEE Transactions on Intelligent Vehicles (TIV)</li>
  <li>Pattern Recognition (PR)</li>
  <li>Neurocomputing</li>
</ul>
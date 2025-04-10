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

I'm an incoming CSE Ph.D. student at [The Chinese University of Hong Kong (CUHK)](https://www.cse.cuhk.edu.hk/), under the supervision of [Pheng-Ann Heng](https://www.cse.cuhk.edu.hk/~pheng/). I hold research internships at [Alibaba Tongyi Lab](https://tongyi.aliyun.com/welcome) and [Tencent YouTu Lab](https://jarvislab.tencent.com/index-en.html). I am also privileged to work closely with Prof. [Xiaojiang Peng](https://scholar.google.com/citations?user=7oRD67kAAAAJ&hl=zh-CN), Dr. [Xiao Luo](https://scholar.google.com.hk/citations?user=yJgX8agAAAAJ&hl=zh-CN), and Prof. [Yefeng Zheng](https://scholar.google.com/citations?user=vAIECxgAAAAJ&hl=zh-CN).  

My research interests lie at the intersection of foundation models and scientific problems. Recently, I have a special focus on:  
* **Foundation Models**: Large Language Models (LLMs)/Multimodal LLMs (MLLMs) Post-training.  
* **AI for Science**: Foundation Models (LLMs/MLLMs) for Scientific Problems, including Biology and Healthcare.  

**Email**: <u>fanzhang@gatech.edu</u> or <u>zfkarl1998@gmail.com</u>

<span style="color:red;">Please feel free to contact me for communication and collaboration.</span>

<h1 id='news'>News</h1>
<!--
- *2025.04:* I start my internship at Tongyi Lab, Alibaba Group.
- *2024.12:* One paper is accepted by **AAAI 2025** (First Author).
- *2024.09:* One paper is accepted by **NeurIPS 2024** (First Author).
- *2024.08:* I start my internship at Tencent YouTu Lab.
- *2024.06:* One paper is accepted by **TPAMI 2024** (First Author). 
- *2024.05:* One paper is accepted by **TIP 2024** (First Author). 
- *2024.03:* One paper is accepted by **NAACL 2024** (First Author). 
- *2024.02:* One paper is accepted by **CVPR 2024** (First Author).  
-->
<style>
  .scrollable {
    max-height: 260px; /* 设置最大高度 */
    overflow-y: scroll; /* 设置垂直滚动条 */
  }
</style>

<div class="scrollable">
  <ul>
    <li><strong>2025.04</strong>: I start my internship at Tongyi Lab, Alibaba Group.
    <li><strong>2024.12</strong>: One paper is accepted by AAAI 2025 (First Author). </li>
    <li><strong>2024.09</strong>: One paper is accepted by NeurIPS 2024 (First Author). </li>
    <li><strong>2024.08</strong>: I start my internship at Tencent YouTu Lab. </li>
    <li><strong>2024.06</strong>: One paper is accepted by TPAMI 2024 (First Author). </li>
    <li><strong>2024.05</strong>: One paper is accepted by TIP 2024 (First Author). </li>
    <li><strong>2024.03</strong>: One paper is accepted by NAACL 2024 (First Author). </li>
    <li><strong>2024.02</strong>: One paper is accepted by CVPR 2024 (First Author). </li>
  </ul>
</div>

<h1 id='publications'>Selected Publications</h1>

For **full** publications, please refer to my [Google Scholar](https://scholar.google.com.hk/citations?user=KbC_-7cAAAAJ&hl=zh-CN&oi=ao).

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/AAAI25-DREAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DREAM: Decoupled Discriminative Learning with Bigraph-aware Alignment for Semi-supervised 2D-3D Cross-modal Retrieval](https://zfkarl.github.io/)  

**Fan Zhang**, Changhu Wang, Zebang Cheng, Xiaojiang Peng, Dongjie Wang, Yijia Xiao, Chong Chen, Xian-Sheng Hua, Xiao Luo     

*Annual AAAI Conference on Artificial Intelligence (AAAI), 2025*  

<span style="color:red;">*(CCF Rank A)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/NeurIPS24-DANCE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Semi-supervised Knowledge Transfer Across Multi-omic Single-cell Data](https://proceedings.neurips.cc/paper_files/paper/2024/file/47f30d67bce3e9824928267e9355420f-Paper-Conference.pdf)  

**Fan Zhang**, Tianyu Liu, Zihao Chen, Xiaojiang Peng, Chong Chen, Xian-Sheng Hua, Xiao Luo, Hongyu Zhao     

*Annual Conference on Neural Information Processing Systems (NeurIPS), 2024*  

<span style="color:red;">*(CCF Rank A)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/TPAMI-HOPE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HOPE: A Hierarchical Perspective for Semi-supervised 2D-3D Cross-Modal Retrieval](https://ieeexplore.ieee.org/document/10553262)  

**Fan Zhang**, Hang Zhou, Xian-Sheng Hua, Chong Chen, Xiao Luo  

*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024*  

<span style="color:red;">*(CCF Rank A, JCR Q1, IF=23.6)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2024</div><img src='images/TIP_FATE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FATE: Learning Effective Binary Descriptors with Group Fairness](https://ieeexplore.ieee.org/document/10547662)  

**Fan Zhang**, Chong Chen, Xian-Sheng Hua, Xiao Luo  

*IEEE Transactions on Image Processing (TIP), 2024*  

<span style="color:red;">*(CCF Rank A, JCR Q1, IF=10.6)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2024</div><img src='images/NAACL24_DEMO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEMO: A Statistical Perspective for Efficient Image-Text Matching](https://arxiv.org/pdf/2405.11496)  

**Fan Zhang**, Xian-Sheng Hua, Chong Chen, Xiao Luo  

*North American Chapter of the Association for Computational Linguistics (NAACL), 2024*  

<span style="color:red;">*(CCF Rank B)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR24_FIVE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Prototypical Voting with Heterogeneous Mixup for Semi-supervised 2D-3D Cross-modal Retrieval](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Fine-grained_Prototypical_Voting_with_Heterogeneous_Mixup_for_Semi-supervised_2D-3D_Cross-modal_CVPR_2024_paper.pdf)  

**Fan Zhang**, Xian-Sheng Hua, Chong Chen, Xiao Luo  

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024*  

<span style="color:red;">*(CCF Rank A)*</span>  
</div>
</div>


<h1 id='experience'>Experience</h1>
<div class='exp-box'> <div class='exp-box-image'><div><img src='images/logo_tongyi.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">
  
[**Alibaba Group**](https://tongyi.aliyun.com/welcome), Hangzhou, China

**Research Intern** @ Tongyi Lab

2025.04 - 2025.07

</div>
</div>

<div class='exp-box'> <div class='exp-box-image'><div><img src='images/logo_YouTu.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">
  
[**Tencent YouTu Lab**](https://open.youtu.qq.com/), Shenzhen, China

**Research Intern** @ Jarvis Research Center

2024.08 - 2025.04

</div>
</div>

<h1 id='services'>Academic Services</h1>

### Conference Reviewer / PC Member
* ICML 2025, ICLR 2025, NeurIPS 2024, KDD 2024-2025, CIKM 2024, MM 2024, ACL ARR 2023-2025    

### Journal Reviewer
* IEEE TNNLS, IEEE TMM, PLOS ONE  

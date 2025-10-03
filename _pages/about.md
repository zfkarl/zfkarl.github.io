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

I'm currently a Ph.D. student at [Department of Computer Science and Engineering (CSE), The Chinese University of Hong Kong (CUHK)](https://www.cse.cuhk.edu.hk/), supervised by [Prof. Pheng-Ann Heng](https://scholar.google.com/citations?user=OFdytjoAAAAJ&hl=zh-CN). Previously, I gained valuable experience as a research intern at [Alibaba Group](https://tongyi.aliyun.com/welcome) and [Tencent](https://jarvislab.tencent.com/index-en.html).

My research interests lie at the intersection of artificial Intelligence (AI) and its applications in the scientific domain, with an emphasis on:    
* **Foundation Models**: Understanding, Reasoning, Post-training, Evaluation, and Agentic Techniques of Large Language Models (LLMs)/Large Multimodal Models (LMMs).    
* **AI for Science**: Scientific Foundation Models, particularly in Healthcare, Life Science, and Cognitive Science.    

**Email**: <u>fzhang@link.cuhk.edu.hk</u>  &nbsp; &nbsp;  **Wechat**: ZF_Karl

<span style="color:red;">Please feel free to contact me for communication and collaboration.</span>

<h1 id='news'>News</h1>
<style>
  .scrollable {
    max-height: 260px; /* 设置最大高度 */
    overflow-y: scroll; /* 设置垂直滚动条 */
  }
</style>

<div class="scrollable">
  <ul>
    <li><strong>2025.09</strong>: One paper about LLM for Biology is accepted by NeurIPS 2025 Datasets and Benchmarks Track. </li>
    <li><strong>2025.08</strong>: I joined CUHK CSE Department as a PhD student, under the supervision of Prof. Pheng-Ann Heng. </li>
    <li><strong>2025.05</strong>: Two survey papers about foundation models for biology and healthcare are accepted by ACL 2025 (1 main paper and 1 findings). </li>
    <li><strong>2025.04</strong>: I start my internship at Tongyi Lab, Alibaba Group. </li>
    <li><strong>2024.12</strong>: One paper about multimodal representation learning is accepted by AAAI 2025. </li>
    <li><strong>2024.09</strong>: One paper about AI for Biology is accepted by NeurIPS 2024. </li>
    <li><strong>2024.08</strong>: I start my internship at Tencent YouTu Lab. </li>
    <li><strong>2024.06</strong>: One paper about multimodal representation learning is accepted by TPAMI 2024. </li>
    <li><strong>2024.05</strong>: One paper about trustworthy information retrieval is accepted by TIP 2024. </li>
    <li><strong>2024.03</strong>: One paper about multimodal representation learning is accepted by NAACL 2024. </li>
    <li><strong>2024.02</strong>: One paper about multimodal representation learning is accepted by CVPR 2024. </li>
  </ul>
</div>

<h1 id='publications'>Selected Publications</h1>

For **full** publications, please refer to my [Google Scholar](https://scholar.google.com.hk/citations?user=KbC_-7cAAAAJ&hl=zh-CN&oi=ao).

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/NeurIPS25-CellVerse.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CellVerse: Do Large Language Models Really Understand Cell Biology?](https://cellverse-cuhk.github.io/)    

**Fan Zhang**, Tianyu Liu, Zhihong Zhu, Hao Wu, Haixin Wang, Donghao Zhou, Yefeng Zheng, Kun Wang, Xian Wu, Pheng-Ann Heng     

*Annual Conference on Neural Information Processing Systems (NeurIPS) Datasets and Benchmarks Track, 2025*  

<span style="color:red;">*(CCF Rank A)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/ACL25-scFLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Foundation Language Models for Single-cell Biology](https://aclanthology.org/2025.acl-long.26/)    

**Fan Zhang**, Hao Chen, Zhihong Zhu, Ziheng Zhang, Zhenxi Lin, Ziyue Qiao, Yefeng Zheng, Xian Wu     

*Annual Meeting of the Association for Computational Linguistics (ACL), 2025*  

<span style="color:red;">*(CCF Rank A)*</span>  
</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/AAAI25-DREAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[DREAM: Decoupled Discriminative Learning with Bigraph-aware Alignment for Semi-supervised 2D-3D Cross-modal Retrieval](https://ojs.aaai.org/index.php/AAAI/article/view/33441)  

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
  
[**Tencent**](https://open.youtu.qq.com/), Shenzhen, China

**Research Intern** @ YouTu Lab

2024.08 - 2025.04

</div>
</div>

<h1 id='services'>Academic Services</h1>

### Conference Reviewer / PC Member
* ICML, ICLR, NeurIPS, ICCV, KDD, AAAI, CIKM, ACM MM, ACL ARR    

### Journal Reviewer
* IEEE TNNLS, IEEE TMM, PLOS ONE  

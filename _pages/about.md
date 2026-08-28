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

# About Me

Hello! This is Honglei Zhang (张洪磊, E-mail: honglei.zhang@bjtu.edu.cn). Now I'm a Lecturer in School of Computer Science and Technology, Beijing Jiaotong University and Key Laboratory of Big Data and Artificial Intelligence in Transportation, Ministry of Education. I got my Ph.D. degree in School of Computer Science and Technology, Beijing Jiaotong University (SCST, BJTU), advised by [Prof. Yidong Li (李浥东)](https://faculty.bjtu.edu.cn/8408/). Before that, I got my Master degree in SCST of BJTU, advised by [Prof. Jun Wu (邬俊)](https://faculty.bjtu.edu.cn/8620/). From October 2023 to October 2024, I am a visiting Ph.D. in [Prof. Zhiqi Shen](https://personal.ntu.edu.sg/zqshen/) and [Xin Zhou](https://xinzhou.me/)'s group at Nanyang Technological University (NTU), Singapore.

<!-- 
 and [Dr. Zhenyi Wang](https://sites.google.com/view/zhenyiwang)
-->

My research interests lie in recommender system and federated learning. More specifically, I focus on:
- **Recommender System:** trustworthy recommendation, privacy-preserving/federated recommendation, debiased recommendation
- **Federated Learning:** personalized federated learning, on-device learning, local adaptation, global aggregation
- **Large Language Models:** privacy-preserving large models, defense and attacks on large models, efficient large models


🔥 <font color="red"> Our team is seeking self-motivated students (including remote internships, undergraduates, graduate students, and other candidates) to join research on recommender systems, federated learning and foundation models, with the goal of publishing high-quality academic papers. If interested, please email me your resume. </font>

<!-- 
&nbsp;🎉 
&nbsp;🎓 
&nbsp;🏅
&nbsp;👏
-->

# ✨ Repositories

Comments and contributions are welcome. 
- [RSTutorials-RSPapers](https://github.com/hongleizhang/RSPapers) [![](https://img.shields.io/github/stars/hongleizhang/RSPapers?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/hongleizhang/RSPapers) \
  This repository collects a curated list of must-read papers on recommender system. 
- [RSTutorials-RSAlgorithms](https://github.com/hongleizhang/RSAlgorithms) [![](https://img.shields.io/github/stars/hongleizhang/RSAlgorithms?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/hongleizhang/RSAlgorithms) \
  This repository collects a set of algorithms about traditional and social recommender system


# 📝 Selected Publications and Preprints 

Including conference papers, journal papers and survey papers. 

<!-- 
<a href="https://www.ccf.org.cn/Academic_Evaluation/By_category/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCF-Rank]</a>
<a href="https://www.caai.cn/index.php?s=/home/article/detail/id/3445.html" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCAI-Rank]</a>
<a href="http://portal.core.edu.au/conf-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (conf)]</a>
<a href="http://portal.core.edu.au/jnl-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (jnl)]</a>
-->

[comment]: <> (<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>)
[comment]: <> (<div class='paper-box-text' markdown="1">)
[comment]: <> ([Deep Residual Learning for Image Recognition]&#40;https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf&#41;)
[comment]: <> (**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun)
[comment]: <> ([**Project**]&#40;https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC&#41; <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>)
[comment]: <> (- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )
[comment]: <> (</div>)
[comment]: <> (</div>)

<!-- 
$^{\ast}$ indicates equal contribution, $^{\dagger}$ indicates corresponding author
-->

## Conference Papers

- [From Transfer to Collaboration: A Federated Framework for Cross-Market Sequential Recommendation](https://arxiv.org/abs/2604.13573) \
  `MM 2026` | [Paper](https://arxiv.org/abs/2604.13573)   \
  Jundong Chen, **Honglei Zhang**, Xiangmou Qu, Haoxuan Li, Han Yu, Yidong Li.
  
- [TransFR: Transferable Federated Recommendation with Adapter Tuning on Pre-trained Language Models](https://ojs.aaai.org/index.php/AAAI/article/view/40048) \
  `AAAI 2026` | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/40048)\
  **Honglei Zhang**, Zhiwei Li, Haoxuan Li, Xin Zhou, Jie Zhang, Yidong Li.

- [Breaking the Aggregation Bottleneck in Federated Recommendation: A Personalized Model Merging Approach](https://ojs.aaai.org/index.php/AAAI/article/view/38472) \
  `AAAI 2026` | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/38472)\
  Jundong Chen, **Honglei Zhang**, Chunxu Zhang, Fangyuan Luo, Yidong Li.
  
- [CoDTS: Enhancing Sparsely Supervised Collaborative Perception with a Dual Teacher-Student Framework](https://ojs.aaai.org/index.php/AAAI/article/view/32348) \
  `AAAI 2025` |[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32348)  [Code](https://github.com/CatOneTwo/CoDTS) \
  Yushan Han, Hui Zhang, **Honglei Zhang**, Jing Wang, Yidong Li.
  
- [A Tutorial of Personalized Federated Recommender Systems: Recent Advances and Future Directions](https://dl.acm.org/doi/10.1145/3701716.3715860) \
  `WWW 2025` | [Paper](https://dl.acm.org/doi/10.1145/3701716.3715860) \
  Jing Jiang, Chunxu Zhang, **Honglei Zhang**, Zhiwei Li, Yidong Li, Bo Yang.
  
- [Uncovering the Propensity Identification Problem in Debiased Recommendations](https://ieeexplore.ieee.org/abstract/document/10597923/) \
  `ICDE 2024` | [Paper](https://ieeexplore.ieee.org/abstract/document/10597923/)  \
  **Honglei Zhang**, Shuyi Wang, Haoxuan Li, Chunyuan Zheng, Xu Chen, Li Liu, Shanshan Luo, Peng Wu.
  
- [Robust Watermarking using Inverse Gradient Attention](https://arxiv.org/abs/2011.10850) \
  `BESC 2022` | [Paper](https://arxiv.org/abs/2011.10850)  \
  **Honglei Zhang**, Hu Wang, Yuanzhouhan Cao, Chunhua Shen, Yidong Li.
  
- [Integrating Dual User Network Embedding with Matrix Factorization for Social Recommender Systems](https://ieeexplore.ieee.org/abstract/document/8851715/) \
  `IJCNN 2019` | [Paper](https://ieeexplore.ieee.org/abstract/document/8851715/)  \
  Liying Chen$^{\ast}$, **Honglei Zhang**$^{\ast}$ ($^{\ast}$ *indicates co-first authors*), Jun Wu.
  
- [Social Collaborative Filtering Ensemble](https://link.springer.com/chapter/10.1007/978-3-319-97304-3_77) \
  `PRICAI 2018` | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-97304-3_77)  \
  **Honglei Zhang**, Gangdu Liu, Jun Wu.

<!-- $^{\dagger}$ ($^{\dagger}$ *indicates corresponding authors*) -->

## Journal Papers

- [FedUTR: Federated Recommendation with Augmented Universal Textual Representation for Sparse Interaction Scenarios](https://arxiv.org/abs/2604.07351) \
  `TMM 2026` | [Paper](https://arxiv.org/abs/2604.07351)  \
  Kang Fu, **Honglei Zhang**, Zikai Zhang, Jundong Chen, Xin Zhou, Zhiqi Shen, Dusit Niyato, Yidong Li.

- [Beyond Personalization: Federated Recommendation with Calibration via Low-rank Decomposition](https://arxiv.org/abs/2506.09525) \
  `Arxiv 2026` | [Paper](https://arxiv.org/pdf/2506.09525)   \
  Jundong Chen, **Honglei Zhang**, Haoxuan Li, Chunxu Zhang, Zhiwei Li, Yidong Li.

- [MDiffFR: Modality-Guided Diffusion Generation for Cold-start Items in Federated Recommendation](https://dl.acm.org/doi/10.1145/3843228) \
  `TOIS 2026` | [Paper](https://dl.acm.org/doi/10.1145/3843228)  \
  Kang Fu, **Honglei Zhang**, Xuechao Zou, Yidong Li.

- [Beyond Similarity: Personalized Federated Recommendation with Composite Aggregation](https://dl.acm.org/doi/10.1145/3779442) \
  `TOIS 2026` | [Paper](https://dl.acm.org/doi/10.1145/3779442)  [Code](https://github.com/hongleizhang/FedCA)\
  **Honglei Zhang**, Haoxuan Li, Jundong Chen, Sen Cui, Kunda Yan, Abudukelimu Wuerkaixi, Xin Zhou, Zhiqi Shen, Yidong Li.

- [Bridging Graph Learning and Federated Optimization for Recommendations](https://journal.hep.com.cn/fcs/EN/10.1007/s11704-026-51383-7) \
  `FCS 2026` | [Paper](https://journal.hep.com.cn/fcs/EN/10.1007/s11704-026-51383-7) \
  Chunxu Zhang, Zonghan Wu, **Honglei Zhang**, Jiaxu Cui, Bo Yang.

- [Efficient Federated Metric Learning and Machine Unlearning Based on Prototype Distillation](https://ieeexplore.ieee.org/document/11304257/) \
  `TSC 2026` | [Paper](https://ieeexplore.ieee.org/document/11304257/)  \
  Jingyi Li, Zikai Zhang, **Honglei Zhang**, Yidong Li.

- [CoDS: Enhancing Collaborative Perception in Heterogeneous Scenarios via Domain Separation](https://ieeexplore.ieee.org/document/11206456) \
 `TMC 2025` | [Paper](https://ieeexplore.ieee.org/document/11206456) \
  Yushan Han, Hui Zhang, **Honglei Zhang**, Chuntao Ding, Yuanzhouhan Cao, Yidong Li.

- [Debiased Recommendation via Wasserstein Causal Balancing](https://dl.acm.org/doi/pdf/10.1145/3725731) \
 `TOIS 2025` | [Paper](https://dl.acm.org/doi/pdf/10.1145/3725731) \
  Hao Wang, Zhichao Chen, **Honglei Zhang**, Zhengnan Li, Licheng Pan, Haoxuan Li, Mingming Gong.
  
- [Learning to Unlearn for Bayesian Personalized Ranking via Influence Function](https://cje.ejournal.org.cn/article/doi/10.23919/cje.2023.00.417) \
 `电子学报 2025` | [Paper](https://cje.ejournal.org.cn/article/doi/10.23919/cje.2023.00.417)\
  Jundong Chen$^{\ast}$, **Honglei Zhang**$^{\ast}$ ($^{\ast}$ *indicates co-first authors*), Haoxuan Li, Yidong Li.
 
- [PrivFR: Privacy-Enhanced Federated Recommendation with Shared Hash Embedding](https://ieeexplore.ieee.org/abstract/document/10506199) \
  `TNNLS 2025` | [Paper](https://ieeexplore.ieee.org/abstract/document/10506199) \
  **Honglei Zhang**, Xin Zhou, Zhiqi Shen, Yidong Li.
  
- [On Robustness of Neural ODEs Image Classifiers](https://www.sciencedirect.com/science/article/pii/S0020025523003444) \
  `INS 2024` | [Paper](https://www.sciencedirect.com/science/article/pii/S0020025523003444) \
  Wenjun Cui, **Honglei Zhang**, Haoyu Chu, Pipi Hu, Yidong Li.

- [LightFR: Lightweight Federated Recommendation with Privacy-preserving Matrix Factorization](https://dl.acm.org/doi/full/10.1145/3578361) \
  `TOIS 2023` | [Paper](https://dl.acm.org/doi/full/10.1145/3578361)\
  **Honglei Zhang**, Fangyuan Luo, Jun Wu, Xiangnan He, Yidong Li.
  

## Survey Papers

- [A Survey of Personalized Federated Foundation Models for Privacy-Preserving Recommendation](https://arxiv.org/pdf/2506.11563) \
  `IJCAI 2026` | [Paper](https://arxiv.org/pdf/2506.11563) \
  Zhiwei Li, Guodong Long, Chunxu Zhang, **Honglei Zhang**, Jing Jiang, Chengqi Zhang.

- [Learning to Hash for Recommendation: A Survey](https://arxiv.org/abs/2412.03875) \
  `Arxiv 2024` | [Paper](https://arxiv.org/abs/2412.03875) [Code](https://github.com/Luo-Fangyuan/HashRec)  \
  Fangyuan Luo, **Honglei Zhang**, Tong Li, Jun Wu.

- [Advancing Sustainability via Recommender Systems: A Survey](https://arxiv.org/pdf/2411.07658) \
  `Arxiv 2024` | [Paper](https://arxiv.org/pdf/2411.07658) [Code](https://github.com/enoche/SusRec) \
  Xin Zhou, Lei Zhang, **Honglei Zhang**, Yixin Zhang, Xiaoxiong Zhang, Jie Zhang, Zhiqi Shen.
  
- [Personalized Recommendation Models in Federated Settings: A Survey](https://ieeexplore.ieee.org/document/11151823/) \
  `TKDE 2025` | [Paper](https://ieeexplore.ieee.org/document/11151823/) [Code](https://anonymous.4open.science/r/Personalized_FedRecSys) \
  Chunxu Zhang, Guodong Long, Zijian Zhang, Zhiwei Li, **Honglei Zhang**, Qiang Yang, Bo Yang.
 
 - [面向可信联邦学习公平性的研究综述](https://www.ejournal.org.cn/CN/10.12263/DZXB.20230139) \
  `电子学报 2023` | [Paper](https://www.ejournal.org.cn/CN/10.12263/DZXB.20230139) \
  陈颢瑜, 李浥东, **张洪磊**, 陈乃月.
 
 - [基于隐私保护的联邦推荐算法综述](http://www.aas.net.cn/article/doi/10.16383/j.aas.c211189) \
  `自动化学报 2022` | [Paper](http://www.aas.net.cn/article/doi/10.16383/j.aas.c211189) \
  **张洪磊**, 李浥东, 邬俊, 陈乃月, 董海荣.

<!--Just accepted -->
<!-- [**Paper**]() [**Code**]()  -->

# 📖 Educations

- 2023.10 - 2024.10: Visiting Ph.D. Student at Nanyang Technological University, Singapore.
- 2020.09 - 2025.03 Ph.D. Student at Beijing Jiaotong University, China.
- 2016.09 - 2019.06 M.S. Student at Beijing Jiaotong University, China.
- 2012.09 - 2016.06 B.S. Student at Hebei Normal University, China.

<!--
- 2018.09 - 2021.07: M.S. Student at [Northeastern University, China](https://www.neu.edu.cn/).
-->


# 💬 Invited Talks

- 2025.11: "Towards Efficient Privacy-Preserving Techniques for Recommender Systems"; Inviter: CCF ITSC 2025
- 2025.04: "A Tutorial of Personalized Federated Recommender Systems: Recent Advances and Future Directions"; Inviter: WWW 2025
- 2024.07: "How to Identify Innovation Opportunities in Recommender Systems"; Inviter: Xijing University


# 🏆 Honors and Awards

- 2025.11: Outstanding Doctoral Dissertation Incentive Program (优秀博士学位论文激励计划), CCF Intelligent Transportation Committee (中国计算机学会智慧交通分会)



# 🔖 Services

## Conference Reviewers
  - International Conference on Learning Representations (ICLR) 2027
  - ACM International Conference on Web Search and Data Mining (WSDM) 2027
  - AAAI Conference on Artificial Intelligence (AAAI) 2027
  - ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2026
  - International ACM Conference on Knowledge and Information Management (CIKM) 2026
  - ACM International Conference on Multimedia (MM) 2026
  - International Conference on Learning Representations (ICLR) 2026
  - AAAI Conference on Artificial Intelligence (AAAI) 2026
  - ACM International Conference on Web Search and Data Mining (WSDM) 2026
  - Conference on Neural Information Processing Systems (NeurIPS) 2025
  - International Conference on Machine Learning (ICML) 2025
  - International Conference on Learning Representations (ICLR) 2025
  - International World Wide Web Conference (WWW) 2025
  - ACM Special Interest Group on Information Retrieval (SIGIR) 2025
  - ACM SIGIR Conference on Information Retrieval in the Asia Pacific (SIGIR-AP) 2025
  - ACM International Conference on Multimedia (MM) 2025
  - Conference on Neural Information Processing Systems (NeurIPS) 2024
  - International Conference on Machine Learning (ICML) 2024
  - International World Wide Web Conference (WWW) 2024
  - ACM International Conference on Multimedia (MM) 2024
    
## Journal Reviewers
  - ACM Transactions on Information Systems (TOIS)
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - IEEE Transactions on Multimedia (TMM)
  - IEEE Transactions on Image Processing (TIP)
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
  - IEEE Transactions on Intelligent Transportation Systems (TITS)
  - IEEE Transactions on Industrial Informatics (TII)
  - IEEE Internet of Things Journal (IOTJ)
  - Information Sciences (INS)
  - Neurocomputing (NEUCOM)
  - Knowledge-Based Systems (KNOSYS)
  - 自动化学报
  
## Organizers

  - MM2026 Workshop on [Efficient Representation Learning for Multimodal Information Retrieval](https://erel-mir.github.io/), Publicity Chair
  - WWW2025 Tutorials on [Federated Recommender Systems](https://www2025.thewebconf.org/accepted-tutorials), Speaker
  - SIGKDD2022 Workshop on [Trustworthy Recommender Systems](https://rrs2022.github.io/), Publicity Chair
  - Official Account on [Machine Learning and Recommender Systems](https://mp.weixin.qq.com/s/WqpRxKBUHYBeuTh6AETpTQ), Founder


<!--
# 💬 Contact
- Address 1: Northeastern University, No.195, Chuangxin Road, Hunnan District, Shenyang City, Liaoning Province, P.R.China, 110169.
- Address 2: Nanyang Technological University, 50 Nanyang Avenue, Singapore, 639798. (Current Address)
- Email: ennengyang(at)stumail.neu.edu.cn / n2308949l(at)e.ntu.edu.sg
-->

<!--
 <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
   <tbody>
    <tr>
      <td style="padding:20px;width:100%;vertical-align:middle">
	 <ul>
        <a href="https://clustrmaps.com/site/1c198"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=VpGBneeI-MwDastez2HedbbwUkUbavdcRS1CXm0GcfA&cl=ffffff" /> </a>
	     </ul>
      </td>
   </tr>
  </tbody>
 </table>
-->


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

Hello! This is Honglei Zhang (张洪磊, E-mail: honglei.zhang@bjtu.edu.cn). Now I'm a Siyuan Postdoc Fellow in School of Computer Science and Technology, Beijing Jiaotong University and Key Laboratory of Big Data and Artificial Intelligence in Transportation, Ministry of Education. I got my Ph.D. degree in School of Computer Science and Technology, Beijing Jiaotong University (SCST, BJTU), advised by [Prof. Yidong Li (李浥东)](https://faculty.bjtu.edu.cn/8408/). Before that, I got my Master degree in SCST of BJTU, advised by [Prof. Jun Wu (邬俊)](https://faculty.bjtu.edu.cn/8620/). From October 2024 to October 2025, I am a visiting Ph.D. in [Prof. Zhiqi Shen](https://personal.ntu.edu.sg/zqshen/) and [Xin Zhou](https://xinzhou.me/)'s group at Nanyang Technological University (NTU), Singapore.

<!-- 
 and [Dr. Zhenyi Wang](https://sites.google.com/view/zhenyiwang)
-->

My research interests lie in recommender system and federated learning. More specifically, I focus on:
- **Recommender System:** trustworthy recommendation, privacy-preserving/federated recommendation, debiased recommendation
- **Federated Learning:** personalized federated learning, on-device learning, local elastic adaptation, global composite aggregation



<!-- 
&nbsp;🎉 
&nbsp;🎓 
&nbsp;🏅
&nbsp;👏
-->

# ✨ Repositories

Comments and contributions are welcome. 
- [**RSTutorials-RSPapers**](https://github.com/hongleizhang/RSPapers) [![](https://img.shields.io/github/stars/hongleizhang/RSPapers?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/hongleizhang/RSPapers) \
  This repository collects a curated list of must-read papers on recommender system. 
- [**RSTutorials-RSAlgorithms**](https://github.com/hongleizhang/RSAlgorithms) [![](https://img.shields.io/github/stars/hongleizhang/RSAlgorithms?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/hongleizhang/RSAlgorithms) \
  This repository collects a set of algorithms about traditional and social recommender system


# 📝 Selected Preprints and Publications 

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

## Survey Papers

- Learn to Preserve Personality: Federated Foundation Models in Recommendations \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2506.11563) \
  Zhiwei Li, Guodong Long, Chunxu Zhang, **Honglei Zhang**, Jing Jiang, Chengqi Zhang.
  
- Personalized Recommendation Models in Federated Settings: A Survey \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2504.07101) [**Code**](https://anonymous.4open.science/r/Personalized_FedRecSys) \
  Chunxu Zhang, Guodong Long, Zijian Zhang, Zhiwei Li, **Honglei Zhang**, Qiang Yang, Bo Yang.

- Learning to Hash for Recommendation: A Survey \
  `Arxiv 2024` | [**Paper**](https://arxiv.org/abs/2412.03875) [**Code**](https://github.com/Luo-Fangyuan/HashRec)  \
  Fangyuan Luo, **Honglei Zhang**, Tong Li, Jun Wu.

- Advancing Sustainability via Recommender Systems: A Survey \
  `Arxiv 2024` | [**Paper**](https://arxiv.org/pdf/2411.07658) [**Code**](https://github.com/enoche/SusRec) \
  Xin Zhou, Lei Zhang, **Honglei Zhang**, Yixin Zhang, Xiaoxiong Zhang, Jie Zhang, Zhiqi Shen.
 
 - 面向可信联邦学习公平性的研究综述 \
  `电子学报 2023` | [**Paper**](https://www.ejournal.org.cn/CN/10.12263/DZXB.20230139) \
  陈颢瑜, 李浥东, **张洪磊**, 陈乃月.
 
 - 基于隐私保护的联邦推荐算法综述 \
  `自动化学报 2022` | [**Paper**](http://www.aas.net.cn/article/doi/10.16383/j.aas.c211189) \
  **张洪磊**, 李浥东, 邬俊, 陈乃月, 董海荣.

<!--Just accepted -->
<!-- [**Paper**]() [**Code**]()  -->

## Conference Papers

- Beyond Personalization: Federated Recommendation with Calibration via Low-rank Decomposition \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2506.09525)   \
  Jundong Chen, **Honglei Zhang**, Haoxuan Li, Chunxu Zhang, Zhiwei Li, Yidong Li.
  
- CoDTS: Enhancing Sparsely Supervised Collaborative Perception with a Dual Teacher-Student Framework \
  `AAAI 2025` |[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/32348)  [**Code**](https://github.com/CatOneTwo/CoDTS) \
  Yushan Han, Hui Zhang, **Honglei Zhang**, Jing Wang, Yidong Li.
  
- A Tutorial of Personalized Federated Recommender Systems: Recent Advances and Future Directions \
  `WWW 2025` | [**Paper**](https://arxiv.org/pdf/2412.08071) \
  Jing Jiang, Chunxu Zhang, **Honglei Zhang**, Zhiwei Li, Yidong Li, Bo Yang.
  
- Uncovering the Propensity Identification Problem in Debiased Recommendations \
  `ICDE 2025` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/10597923/)  \
  **Honglei Zhang**, Shuyi Wang, Haoxuan Li, Chunyuan Zheng, Xu Chen, Li Liu, Shanshan Luo, Peng Wu.
  
- Robust Watermarking using Inverse Gradient Attention \
  `Arxiv 2022` | [**Paper**](https://arxiv.org/abs/2011.10850)  \
  **Honglei Zhang**, Hu Wang, Yuanzhouhan Cao, Chunhua Shen, Yidong Li.
  
- Integrating Dual User Network Embedding with Matrix Factorization for Social Recommender Systems \
  `IJCNN 2019` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/8851715/)  \
  Liying Chen, **Honglei Zhang**, Jun Wu.
  
- Social Collaborative Filtering Ensemble \
  `PRICAI 2018` | [**Paper**](https://link.springer.com/chapter/10.1007/978-3-319-97304-3_77)  \
  **Honglei Zhang**, Gangdu Liu, Jun Wu.


## Journal Papers

- Debiased Recommendation via Wasserstein Causal Balancing \
 `TOIS 2025` | [**Paper**](https://dl.acm.org/doi/pdf/10.1145/3725731) \
  Hao Wang, Zhichao Chen, **Honglei Zhang**, Zhengnan Li, Licheng Pan, Haoxuan Li, Mingming Gong.
  
- Learning to Unlearn for Bayesian Personalized Ranking via Influence Function \
 `电子学报 2025` | [**Paper**](https://cje.ejournal.org.cn/article/doi/10.23919/cje.2023.00.417)\
  Jundong Chen, **Honglei Zhang**, Haoxuan Li, Yidong Li.
 
- Beyond Similarity: Personalized Federated Recommendation with Composite Aggregation \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2406.03933)  [**Code**](https://github.com/hongleizhang/FedCA)\
  **Honglei Zhang**, Haoxuan Li, Jundong Chen, Sen Cui, Kunda Yan, Abudukelimu Wuerkaixi, Xin Zhou, Zhiqi Shen, Yidong Li.
 
- PrivFR: Privacy-Enhanced Federated Recommendation with Shared Hash Embedding \
  `TNNLS 2024` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/10506199) \
  **Honglei Zhang**, Xin Zhou, Zhiqi Shen, Yidong Li.
  
- TransFR: Transferable Federated Recommendation with Pre-trained Language Models \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2402.01124)\
  **Honglei Zhang**, Zhiwei Li, Haoxuan Li, Yidong Li.
  
- LightFR: Lightweight Federated Recommendation with Privacy-preserving Matrix Factorization \
  `TOIS 2023` | [**Paper**](https://dl.acm.org/doi/full/10.1145/3578361)\
  **Honglei Zhang**, Fangyuan Luo, Jun Wu, Xiangnan He, Yidong Li.
  
- On Robustness of Neural ODEs Image Classifiers \
  `INS 2024` | [**Paper**](https://www.sciencedirect.com/science/article/pii/S0020025523003444) \
  Wenjun Cui, **Honglei Zhang**, Haoyu Chu, Pipi Hu, Yidong Li.


# 📖 Educations

- 2023.10 - 2024.10: Visiting Ph.D. Student at Nanyang Technological University, Singapore.
- 2020.09 - 2025.03 Ph.D. Student at Beijing Jiaotong University, China.

<!--
- 2018.09 - 2021.07: M.S. Student at [Northeastern University, China](https://www.neu.edu.cn/).
-->


# 💻 Internships

- 2023.05 - 2023.09: Intern at [Digital China Group Co., Ltd](https://www.digitalchina.com/).
- 2022.01 - 2022.06: Research Intern at [Tencent Inc](https://www.tencent.com/), mentored by [Junwei Pan](https://scholar.google.com/citations?user=sUaBkFkAAAAJ&hl=zh-TW).
- 2020.05 - 2021.02: Research Intern at [Tencent Inc](https://www.tencent.com/), mentored by [Junwei Pan](https://scholar.google.com/citations?user=sUaBkFkAAAAJ&hl=zh-TW) and Dr. Xiaoqing Cao.


# 🏆 Honors and Awards

- 2025.01: Youth Talents Support Project - Doctoral Student Special Program (First Session)
- 2024.10: National Scholarship (Top 1%)
- 2023.10: National Scholarship (Top 1%)
- 2020.05: Tencent Rhino-Bird Elite Talent Training Program (51 People Worldwide)
- 2019.10: National Scholarship (Top 1%)
- 2017.10: National Scholarship (Top 1%)


# 💬 Invited Talks

- 2025.01: "Model Merging for Multi-task Learning"; Inviter: CCF·Shenzhen University
- 2024.07: "Representation Surgery for Multi-task Model Merging"; Inviter: Wiztalk ICML 2024 Paper Sharing
- 2021.05: "Opportunities and Challenges of Data Sparsity in Recommender Systems"; Inviter: CCF·YEF·2021 


# 🔖 Services

## Conference Reviewers
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
  - ACM Transactions on Information Systems (TOIS) 2025
  - IEEE Transactions on Knowledge and Data Engineering (TKDE) 2025
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS) 2024
  - IEEE Transactions on Image Processing (TIP) 2022


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


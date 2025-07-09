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

# 👋 About Me
Hello! This is Enneng Yang. 
I'm currently a fourth-year Ph.D. student in Software College, [Northeastern University, China](https://www.neu.edu.cn/), advised by [Prof. Guibing Guo](https://guoguibing.github.io/cn/). I am honored to work closely with [Assoc. Prof. Li Shen](https://sites.google.com/site/mathshenli/home) of [Sun Yat-sen University, China](https://shenzhen.sysu.edu.cn/). From March 2024 to March 2025, I am a visiting Ph.D. student in [Prof. Jie Zhang](https://personal.ntu.edu.sg/zhangj/)'s group at [Nanyang Technological University, Singapore](https://www.ntu.edu.sg/).

<!-- 
 and [Dr. Zhenyi Wang](https://sites.google.com/view/zhenyiwang)
-->

My research interests lie in machine learning and recommender systems. More specifically, I focus on:
- **Machine Learning:** foundation models, model merging, multi-task learning, continual/incremental learning, data-free learning, dataset/knowledge distillation
- **Recommendation System:** multi-task/multi-scenario recommendation, sequential recommendation, robust recommendation, CTR/CVR prediction, discrete recommendation


# 🔥 News

<ul class="projects-box" id="projects-box">
<li> 2025.05: Our one paper about knowledge editing is accepted to ACL (main) 2025.</li>
<li> 2025.05: Our one paper about model merging is accepted to ICML 2025.</li>
<li> 2025.04: Our one paper about explainable recommendations is accepted to TOIS 2025.</li>
<li> 2025.04: Our two papers about sequential recommendations are accepted to SIGIR 2025.</li>
<li> 2025.02: Our one paper about out-of-distribution recommendation is accepted to TOIS 2025.</li>
<li> 2025.01: Our one paper about flatness-aware continual learning is accepted to TPAMI 2025.</li>
<li> 2025.01: Our two papers about out-of-distribution recommendations are accepted to WWW 2025.</li>
<li> 2024.12: Our two papers about LLMs fine-tuning and sequential recommendation are accepted to AAAI 2025.</li>
<li> 2024.11: Our one paper about recommendation unlearning is accepted to TOIS 2024.</li>
<li> 2024.11: Our one survey paper about forgetting in deep learning is accepted to TPAMI 2024.</li>
<li> 2024.09: Our one paper about continual learning is accepted to TPAMI 2024.</li>
<li> 2024.05: Our one paper about model merging is accepted to ICML 2024.</li>
<li> 2024.01: Our one paper about model merging is accepted to ICLR 2024.</li>
<li> 2023.10: Our one paper about sequential recommendation is accepted to TKDE 2023.</li>
<li> 2023.09: Our one paper about dataset condensation is accepted to NeurIPS 2023.</li>
<li> 2023.07: Our one paper about flatness-aware continual learning is accepted to ICCV 2023.</li>
<li> 2023.04: Our one paper about next-basket recommendation is accepted to IJCAI 2023.</li>
<p class="projects-show" id="projects-show"><span class="projects-show-text" id="projects-show-text">More</span></p>
</ul>

<!-- 
- 2025.01: Our one paper about LLMs fine-tuning is accepted to NAACL 2025.
- 2025.01: Our one paper about medication recommendation is accepted to DASFAA 2025. 
- 2024.12: Our one paper about multimodal recommendation is accepted to ICASSP 2025.
- 2024.07: Our one paper about sequential recommendation is accepted to RecSys 2024.
- 2024.06: Our one paper about de-confounding recommendation is accepted to ACM TKDD 2024.
- 2024.02: Our one paper about multi-task recommendation is accepted to ACM TKDD 2024.
- 2023.10: Our one paper about explanation recommendation is accepted to KBS 2023.
-->


<!-- 
&nbsp;🎉 
&nbsp;🎓 
&nbsp;🏅
&nbsp;👏
-->

# ✨ Repositories

Comments and contributions are welcome. 
- [**Awesome-Model-Merging-Methods-Theories-Applications**](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) [![](https://img.shields.io/github/stars/ennengyang/Awesome-Model-Merging-Methods-Theories-Applications?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) \
  This repository collects the latest research on Model Merging in Machine Learning. 
- [**Awesome-Forgetting-in-Deep-Learning**](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) [![](https://img.shields.io/github/stars/ennengyang/Awesome-Forgetting-in-Deep-Learning?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) \
  This repository collects the latest research on Catastrophic Forgetting in Deep Learning.
  
<!-- 
- [**DA-CL-4Rec**](https://github.com/KingGugu/DA-CL-4Rec) [![](https://img.shields.io/github/stars/KingGugu/DA-CL-4Rec?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12)](https://github.com/KingGugu/DA-CL-4Rec) ([Yizhou Dang](https://kinggugu.github.io/) is the owner) \
  The repository collects the latest research progress on Data Augmentation and Contrastive Learning in Recommender Systems.
-->

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

- Unifying Multimodal Large Language Model Capabilities and Modalities via Model Merging \
  `Arxiv 2025` | [**Paper**](https://arxiv.org/pdf/2505.19892) [**Code**](https://github.com/WalkerWorldPeace/MLLMerging) \
  Yongxian Wei, Runxi Cheng, Weike Jin, **Enneng Yang**, Li Shen, Lu Hou, Sinan Du, Chun Yuan, Xiaochun Cao, Dacheng Tao.
  
- Model Merging in LLMs, MLLMs, and Beyond: Methods, Theories, Applications and Opportunities \
  `Arxiv 2024` | [**Paper**](https://arxiv.org/pdf/2408.07666) [**Code**](https://github.com/EnnengYang/Awesome-Model-Merging-Methods-Theories-Applications) \
  **Enneng Yang**, Li Shen, Guibing Guo, Xingwei Wang, Xiaochun Cao, Jie Zhang, Dacheng Tao.

- Data Augmentation for Sequential Recommendation: A Survey \
  `Arxiv 2024` | [**Paper**](https://arxiv.org/pdf/2409.13545) [**Code**](https://github.com/KingGugu/DA-CL-4Rec)  \
  Yizhou Dang, **Enneng Yang**, Yuting Liu, Guibing Guo, Linying Jiang, Jianzhe Zhao, Xingwei Wang.
<!-- ([Yizhou Dang](https://kinggugu.github.io/) provides maintenance.) -->

- A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning \
  `TPAMI 2024` | [**Paper**](https://arxiv.org/pdf/2307.09218) [**Code**](https://github.com/EnnengYang/Awesome-Forgetting-in-Deep-Learning) \
  Zhenyi Wang, **Enneng Yang**, Li Shen, Heng Huang.

<!--Just accepted -->
<!-- [**Paper**]() [**Code**]()  -->

## Conference Papers

- Knowledge Decoupling via Orthogonal Projection for Lifelong Editing of Large Language Models \
  `ACL 2025` | Just Accepted   \
  Haoyu Xu, Pengxiang Lan, **Enneng Yang**, Guibing Guo, Jianzhe Zhao, Linying Jiang, Xingwei Wang.
  
- Representation Surgery in Model Merging with Probabilistic Modeling \
  `ICML 2025` |[**Paper**](https://openreview.net/pdf?id=a02CH43z1G)  [**Code**](https://github.com/1998v7/ProbSurgery) \
  Qi Wei, Shuo He, **Enneng Yang**, Tingcong Liu, Haobo Wang, Lei Feng, Bo An.
  
- Denoising Multi-Interest-Aware Logical Reasoning for Long-Sequence Recommendation \
  `SIGIR 2025` | Just Accepted [**Code**](https://github.com/muzi1998/Denoising-Multi-Interest-Aware-Logical-Reasoning) \
  Fei Li, Qingyun Gao, Yizhou Dang, **Enneng Yang**, Guibing Guo, Jianzhe Zhao and Xingwei Wang.
  
- Data Augmentation as Free Lunch: Exploring the Test-Time Augmentation for Sequential Recommendation \
  `SIGIR 2025` | [**Paper**](https://arxiv.org/pdf/2504.04843)  [**Code**](https://github.com/KingGugu/TTA4SR) \
  Yizhou Dang, Yuting Liu, **Enneng Yang**, Minhan Huang, Guibing Guo, Jianzhe Zhao and Xingwei Wang.

- Distributionally Robust Graph Out-of-Distribution Recommendation via Diffusion Model \
  `WWW 2025` | [**Paper**](https://arxiv.org/pdf/2501.15555)  [**Code**](https://github.com/user683/DRGO) \
  Chu Zhao, **Enneng Yang**, Yuliang Liang, Jianzhe Zhao, Guibing Guo, Xingwei Wang.

- Graph Representation Learning via Causal Diffusion for Out-of-Distribution Recommendation \
  `WWW 2025` (<font color="red">Oral</font>) | [**Paper**](https://arxiv.org/pdf/2408.00490v1) [**Code**](https://github.com/user683/CausalDiffRec)\
  Chu Zhao, **Enneng Yang**, Yuliang Liang, Pengxiang Lan, Yuting Liu, Jianzhe Zhao, Guibing Guo, Xingwei Wang.
  
- Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion \
  `AAAI 2025` (<font color="red">Oral</font>) | [**Paper**](https://arxiv.org/pdf/2405.11464)   [**Appendix**](https://arxiv.org/pdf/2405.11464)\
  Pengxiang Lan, **Enneng Yang**, Yuting Liu, Guibing Guo, Linying Jiang, Jianzhe Zhao, Xingwei Wang.
  
- Augmenting Sequential Recommendation with Balanced Relevance and Diversity\
  `AAAI 2025` (<font color="red">Oral</font>) | [**Paper**](https://arxiv.org/pdf/2412.08300) [**Appendix**](https://arxiv.org/pdf/2412.08300) [**Code**](https://github.com/KingGugu/BASRec) \
   Yizhou Dang, Jiahui Zhang, Yuting Liu, **Enneng Yang**, Yuliang Liang, Guibing Guo, Jianzhe Zhao, Xingwei Wang.

- Representation Surgery for Multi-Task Model Merging\
  `ICML 2024` | [**Paper**](https://openreview.net/pdf?id=Sbl2keQEML) [**Code**](https://github.com/EnnengYang/RepresentationSurgery)  \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Guibing Guo, Xiaojun Chen, Xingwei Wang, Dacheng Tao.

- AdaMerging: Adaptive Model Merging for Multi-Task Learning\
  `ICLR 2024` | [**Paper**](https://openreview.net/pdf?id=nZP6NgD3QY) [**Code**](https://github.com/EnnengYang/AdaMerging)  \
  **Enneng Yang**, Zhenyi Wang, Li Shen, Shiwei Liu, Guibing Guo, Xingwei Wang, Dacheng Tao.

- An Efficient Dataset Condensation Plugin and Its Application to Continual Learning\
  `NeurIPS 2023` | [**Paper**](https://openreview.net/pdf?id=Murj6wcjRw) [**Code**](https://github.com/EnnengYang/An-Efficient-Dataset-Condensation-Plugin)  \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Tongliang Liu, Guibing Guo.

- Data Augmented Flatness-aware Gradient Projection for Continual Learning\
  `ICCV 2023` | [**Paper**](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_Data_Augmented_Flatness-aware_Gradient_Projection_for_Continual_Learning_ICCV_2023_paper.pdf)  [**Appendix**](https://openaccess.thecvf.com/content/ICCV2023/supplemental/Yang_Data_Augmented_Flatness-aware_ICCV_2023_supplemental.pdf) [**Code**](https://github.com/EnnengYang/DFGP)   \
  **Enneng Yang**, Li Shen, Zhenyi Wang, Shiwei Liu, Guibing Guo, Xingwei Wang.

- AdaTask: A Task-aware Adaptive Learning Rate Approach to Multi-task Learning\
  `AAAI 2023` (<font color="red">Oral</font>) | [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/26275)  [**Appendix**](https://arxiv.org/pdf/2211.15055)  [**Code**](https://github.com/EnnengYang/AdaTask)  \
  **Enneng Yang**, Junwei Pan, Ximei Wang, Haibin Yu, Li Shen, Xihua Chen, Lei Xiao, Jie Jiang, Guibing Guo.

- Basket Representation Learning by Hypergraph Convolution on Repeated Items for Next-basket Recommendation\
  `IJCAI 2023` (<font color="red">Oral</font>) | [**Paper**](https://www.ijcai.org/proceedings/2023/0268.pdf) \
  Yalin Yu$^{\ast}$, **Enneng Yang**$^{\ast}$ ($^{\ast}$ *indicates co-first authors*), Guibing Guo, Linying Jiang, Xingwei Wang.

- Uniform Sequence Better: Time Interval Aware Data Augmentation for Sequential Recommendation\
  `AAAI 2023` (<font color="red">Oral</font>) | [**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/25540) [**Code**](https://github.com/KingGugu/TiCoSeRec)\
 Yizhou Dang, **Enneng Yang**, Guibing Guo, Linying Jiang, Xingwei Wang, Xiaoxiao Xu, Qinghui Sun, Hong Liu.

- Discrete Trust-aware Matrix Factorization for Fast Recommendation\
  `IJCAI 2019` (<font color="red">Oral</font>) | [**Paper**](https://www.ijcai.org/proceedings/2019/0191.pdf) [**Code**](https://github.com/EnnengYang/DTMF)\
 Guibing Guo, **Enneng Yang**$^{\dagger}$ ($^{\dagger}$ *indicates corresponding authors*), Li Shen$^{\dagger}$, Xiaochun Yang, Xiaodong He.

## Journal Papers

- Preference Logical Reasoning with Preference Operators for Explainable Recommendations \
 `TOIS 2025` | [**Paper**](https://dl.acm.org/doi/10.1145/3733596)  [**Code**](https://github.com/muzi1998/preference_operator)\
  Fei Li, **Enneng Yang**, Guibing Guo, Linying Jiang, Jianzhe Zhao, and Xingwei Wang.
  
- Symmetric Graph Contrastive Learning against Noisy Views for Recommendation \
 `TOIS 2025` | [**Paper**](https://arxiv.org/pdf/2408.02691)  [**Code**](https://github.com/user683/SGCL)\
  Chu Zhao, **Enneng Yang**, Yuliang Liang, Jianzhe Zhao, Guibing Guo, and Xingwei Wang.
 
- Revisiting Flatness-aware Optimization in Continual Learning with Orthogonal Gradient Projection \
  `TPAMI 2025` | [**Paper**](https://ieeexplore.ieee.org/abstract/document/10874188)  [**Code**](https://github.com/EnnengYang/Revisiting-Flatness-aware-Optimization-in-Continual-Learning-with-Orthogonal-Gradient-Projection)\
  **Enneng Yang**, Li Shen, Zhenyi Wang, Shiwei Liu, Guibing Guo, Xingwei Wang, and Dacheng Tao.
 
- Continual Learning From a Stream of APIs \
  `TPAMI 2024` | [**Paper**](https://ieeexplore.ieee.org/iel8/34/4359286/10684743.pdf) \
  **Enneng Yang**, Zhenyi Wang, Li Shen, Nan Yin, Tongliang Liu, Guibing Guo, Xingwei Wang, Dacheng Tao.
    
- Efficient and Adaptive Recommendation Unlearning: A Guided Filtering Framework to Erase Outdated Preferences \
  `TOIS 2024` | [**Paper**](https://dl.acm.org/doi/pdf/10.1145/3706633) [**Code**](https://github.com/KingGugu/GFEraser) \
  Yizhou Dang, Yuting Liu, **Enneng Yang**, Guibing Guo, Linying Jiang, Jianzhe Zhao, Xingwei Wang.
  
- TiCoSeRec: Augmenting Data to Uniform Sequences by Time Intervals for Effective Recommendation\
  `TKDE 2023` | [**Paper**](https://ieeexplore.ieee.org/document/10285049) [**Code**](https://github.com/KingGugu/TiCoSeRec)\
  Yizhou Dang, **Enneng Yang**, Guibing Guo, Linying Jiang, Xingwei Wang, Xiaoxiao Xu, Qinghui Sun, Hong Liu.


# 📖 Educations

- 2024.03 - 2025.03: Visiting Ph.D. Student at [Nanyang Technological University, Singapore](https://www.ntu.edu.sg/).
- 2021.09 - 2025.07 (Expected): Ph.D. Student at [Northeastern University, China](https://www.neu.edu.cn/).

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
  - Conference on Neural Information Processing Systems (NeurIPS) 2025
  - International Conference on Computer Vision (ICCV) 2025
  - International Conference on Machine Learning (ICML) 2025
  - International World Wide Web Conference (WWW) 2025
  - International Conference on Learning Representations (ICLR) 2025
  - AAAI Conference on Artificial Intelligence (AAAI) 2025
  - Conference on Neural Information Processing Systems (NeurIPS) 2024
  - International Conference on Machine Learning (ICML) 2024
  - ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2024
  - AAAI Conference on Artificial Intelligence (AAAI) 2024
  - International World Wide Web Conference (WWW) 2023
  - ACM International Conference on Web Search and Data Mining (WSDM) 2023
    
## Journal Reviewers
  - Transactions on Machine Learning Research (TMLR) 2024
  - IEEE Transactions on Services Computing (TSC) 2024
  - IEEE Transactions on Big Data (TBD) 2024
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) 2024
  - Neural Computing and Applications (NCAA) 2024
  - ACM Transactions on Recommender Systems (TORS) 2022



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


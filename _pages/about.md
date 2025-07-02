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

Hi, I am currently a postdoctoral research fellow in the Intelligent Machine Perception Lab leaded by Prof. [Na Zhao](https://impl2023.github.io/) in the Singapore University of Technology and Design (SUTD). I received my Ph.D. degree from the University of Electronic Science and Technology of China (UESTC) in Dec 2024, supervised by Prof. [Xiaofeng Zhu](https://scholar.google.com/citations?user=-bk1CrcAAAAJ&hl=en). Since 2023, I have been working closely with the RIKEN Center for Advanced Intelligence Project (RIKEN-AIP)  mentored by Prof. [Gang Niu](https://niug1984.github.io/) and Prof. [Masashi Sugiyama](https://scholar.google.com/citations?user=GkYIrlIAAAAJ&hl=en). Before that, I received my B.Eng. degree from the UESTC in Jul 2020, supervised by Prof. [Yazhou Ren](https://yazhou-ren.github.io/). I am grateful to all the teachers who have helped me.

**My close collaborators**: [Xiaorui Jiang](https://xiaorui-jiang.github.io/), [Liang Peng](https://scholar.google.com/citations?user=GuKZfakAAAAJ&hl=en), [Yujie Mo](https://yujiemo.github.io/), [Jincheng Huang](https://huangjc0429.github.io/JinchengHuang.github.io/), [Zongqian Wu](https://zongqianwu.github.io/), [Yonghua Zhu](https://scholar.google.com/citations?user=CVP8vGEAAAAJ&hl=en&oi=ao),[Jiangzhang Gan](https://scholar.google.com/citations?user=FMVDBN0AAAAJ&hl=en&oi=ao), [Jianpeng Chen](https://cjpcool.github.io/), Huayi Tang.

<span style="color: red;">
I am currently working on multi-view machine learning and multi-view 3D computer vision. I am seeking extensive cooperation opportunities with self-motivated students and if you are interested in our research topics or just want to have a chat, please feel free to contact me via email.
</span>

I am excited about the ongoing developments in the field of artificial intelligence represented by machine learning and deep learning. The research topics that I am currently working on include:
1. 3D scene understanding with semi-/weakly supervised learning for real-world applications.
2. General and robust self-supervised learning methods across multi-view/modal/graph/omics.

Before that, the research during my Ph.D. was machine learning and self-supervised learning on irregular multi-view/modal/graph/omics data. These areas can be unified into multi-view machine learning, and I am focusing on providing novel insights to the community, such as:
1. **Model robustness** (TKDE2022, CVPR2024). First try to theoretically investigate consistency/complementarity/noise robustness for multi-view learning, and suggest to consider the side effects of noisy views for algorithm designs in practical scenarios.
2. **Model interpretability** (ICCV2021, Inf.Fus.2023). First to disentangle view-common and view-private information with deep generative models, which can produce human-understandable multi-view representations to increase the model interpretability.
3. **Data heterogeneity** (CVPR2022, NeurIPS2023). Propose a multi-level framework to promote contrastive learning in multi-view learning, and a general theory-driven self-weighting contrastive learning method that is adaptive to heterogeneous data.
4. **Data incompleteness** (AAAI2021, TIP2023). Propose the first imputation-free deep framework for handling incomplete multi-view data, and establish the connection between domain adaptation and multi-view by incorporating distribution discrepancy.

Fortunately, my research has gained the attention of scholars in the same field and has been successfully applied by others in practical application fields, such as medical data analysis, internet data analysis, etc. However, the practical multi-view application scenarios still face many challenges that need to be further studied. I summarized some application-related [papers](https://github.com/SubmissionsIn/MVC4Applications) hoping to promote academic research and application as well as for the reference of future work.

# 🤗 News

- *2025.06*, Two papers are accepted by ICCV 2025.
- *2025.04*, One paper is accepted by IJCAI 2025.
- *2024.12*, I have obtained my doctoral degree from UESTC.

# 📖 Publications

**Under-Review Papers:**
1. Shangbo Yuan, **Jie Xu**, Na Zhao, Ping Hu, Xiaofeng Zhu. Geometric-Aware Feature Aggregation with Graph Smoothing for Point Cloud Analysis.
1. Jincheng Huang, **Jie Xu**, Xiaoshuang Shi, Ping Hu, Lei Feng, Xiaofeng Zhu. The Final Layer Holds the Key: A Unified and Efficient GNN Calibration Framework.

**Published Papers (\*corresponding author; $^\ddagger$equal contribution):**

1. **Jie Xu**, Na Zhao, Gang Niu, Masashi Sugiyama, Xiaofeng Zhu. Robust Multi-View Learning via Representation Fusion of Sample-Level Attention and Alignment of Simulated Perturbation. IEEE/CVF International Conference on Computer Vision (ICCV), 2025.
1. Xiaorui Jiang, Buyun He, Peng Yuan Zhou, Xinyue Chen, Jingcai Guo, **Jie Xu**\*, Yong Liao\*. A Unified Framework to BRIDGE Complete and Incomplete Deep Multi-View Clustering under Non-IID Missing Patterns. IEEE/CVF International Conference on Computer Vision (ICCV), 2025.
1. Hongqing He, **Jie Xu**\*, Guoqiu Wen\*, Yazhou Ren, Na Zhao, Xiaofeng Zhu. Graph Embedded Contrastive Learning for Multi-View Clustering. International Joint Conference on Artificial Intelligence (IJCAI), 2025.
1. Yuanyang Zhang, Yijie Lin, Weiqing Yan, Li Yao, Xinhang Wan, Guangyuan Li, Chao Zhang, Guanzhou Ke, **Jie Xu**. Incomplete Multi-view Clustering via Diffusion Contrastive Generation. AAAI Conference on Artificial Intelligence (AAAI), 2024.
1. Caixuan Luo, **Jie Xu**\*, Yazhou Ren, Junbo Ma, Xiaofeng Zhu. Simple Contrastive Multi-View Clustering with Data-Level Fusion. International Joint Conference on Artificial Intelligence (IJCAI), 2024.
1. **Jie Xu**, Yazhou Ren, Xiaolong Wang, Lei Feng, Zheng Zhang, Gang Niu, Xiaofeng Zhu. Investigating and Mitigating the Side Effects of Noisy Views in Self-Supervised Clustering Algorithms in Practical Multi-View Scenarios. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024.
1. **Jie Xu**, Shuo Chen, Yazhou Ren, Xiaoshuang Shi, Heng Tao Shen, Gang Niu, Xiaofeng Zhu. Self-Weighted Contrastive Learning among Multiple Views for Mitigating Representation Degeneration. Annual Conference on Neural Information Processing Systems (NeurIPS), 2023.
1. **Jie Xu**, Yazhou Ren, Xiaoshuang Shi, Heng Tao Shen, Xiaofeng Zhu. UNTIE: Clustering Analysis with Disentanglement in Multi-view Information Fusion. Information Fusion (Inf.Fus., IF=18.6), 2023.
1. **Jie Xu**, Chao Li, Liang Peng, Yazhou Ren, Xiaoshuang Shi, Heng Tao Shen, Xiaofeng Zhu. Adaptive Feature Projection with Distribution Alignment for Deep Incomplete Multi-view Clustering. IEEE Transactions on Image Processing (TIP, IF=10.6), <span style="color: red;">**ESI highly cited paper**</span>, 2023.
1. **Jie Xu**, Yazhou Ren, Huayi Tang, Zhimeng Yang, Lili Pan, Yang Yang, Xiaorong Pu, Philip S. Yu, Lifang He. Self-Supervised Discriminative Feature Learning for Deep Multi-View Clustering. IEEE Transactions on Knowledge and Data Engineering (TKDE, IF=8.9), <span style="color: red;">**ESI highly cited paper**</span>, 2023.
1. **Jie Xu**$^\ddagger$, Huayi Tang$^\ddagger$, Yazhou Ren, Liang Peng, Xiaofeng Zhu, Lifang He. Multi-Level Feature Learning for Contrastive Multi-View Clustering. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), <span style="color: red;">**Oral presentation paper**</span>, 2022.
1. **Jie Xu**, Chao Li, Yazhou Ren, Liang Peng, Yujie Mo, Xiaoshuang Shi, Xiaofeng Zhu. Deep Incomplete Multi-view Clustering via Mining Cluster Complementarity. AAAI Conference on Artificial Intelligence (AAAI), 2022.
1. **Jie Xu**, Yazhou Ren, Huayi Tang, Xiaorong Pu, Xiaofeng Zhu, Ming Zeng, Lifang He. Multi-VAE: Learning Disentangled View-common and View-peculiar Visual Representations for Multi-view Clustering. IEEE/CVF International Conference on Computer Vision (ICCV), 2021.
1. **Jie Xu**, Yazhou Ren, Guofeng Li, Lili Pan, Ce Zhu, Zenglin Xu. Deep Embedded Multi-View Clustering with Collaborative Training. Information Sciences (Inf.Sci., IF=8.1), 2021.
1. Fangfei Lin, **Jie Xu**, Yazhou Ren, Junjie Chen, Irwin King, Zenglin Xu. Multi-modal Hierarchical Clustering for Cancer Subtype Identification using Multi-omics Data. International Joint Conference on Neural Networks (IJCNN), 2025.
1. Jianpeng Chen, Yawen Ling, **Jie Xu**, Yazhou Ren, Shudong Huang, Xiaorong Pu, Lifang He. Variational Graph Generator for Multi-View Graph Clustering. IEEE Transactions on Neural Networks and Learning Systems (TNNLS, IF=10.2), 2024.
1. Xinyue Chen, Yazhou Ren, **Jie Xu**, Fangfei Lin, Xiaorong Pu, Lifang He. Bridging Gaps: Federated Multi-View Clustering in Heterogeneous Hybrid Views. Annual Conference on Neural Information Processing Systems (NeurIPS), 2024.
1. Yazhou Ren, Jingyu Pu, Zhimeng Yang, **Jie Xu**, Guofeng Li, Xiaorong Pu, Philip S Yu, Lifang He. Deep Clustering: A Comprehensive Survey. IEEE Transactions on Neural Networks and Learning Systems (TNNLS, IF=10.4), 2024.
1. Yazhou Ren, Xinyue Chen, **Jie Xu**, Jingyu Pu, Yonghao Huang, Xiaorong Pu, Ce Zhu, Xiaofeng Zhu, Zhifeng Hao, Lifang He. A Novel Federated Multi-View Clustering Method for Unaligned and Incomplete Data Fusion. Information Fusion (Inf.Fus., IF=14.7), 2024.
1. Liang Peng, Yujie Mo, **Jie Xu**, Jialie Shen, Xiaoshuang Shi, Xiaoxiao Li, Heng Tao Shen, Xiaofeng Zhu. GRLC: Graph Representation Learning with Constraints. IEEE Transactions on Neural Networks and Learning Systems (TNNLS, IF=14.2), 2024.
1. Xinyue Chen, **Jie Xu**, Yazhou Ren, Xiaorong Pu, Ce Zhu, Xiaofeng Zhu, Zhifeng Hao, Lifang He. Federated Deep Multi-View Clustering with Global Self-Supervision. ACM International Conference on Multimedia (ACM MM), 2023.
1. Yawen Ling, Jianpeng Chen, Yazhou Ren, Xiaorong Pu, **Jie Xu**, Xiaofeng Zhu, Lifang He. Dual Label-Guided Graph Refinement for Multi-View Graph Clustering. AAAI Conference on Artificial Intelligence (AAAI), 2023.
1. Zhimeng Yang, Yazhou Ren, Zirui Wu, Ming Zeng, **Jie Xu**, Yang Yang, Xiaorong Pu, Philip S. Yu, Lifang He. DC-FUDA: Improving Deep Clustering via Fully Unsupervised Domain Adaptation. Neurocomputing (NEUCOM, IF=6.0), 2023.
1. Liang Peng, Nan Wang, **Jie Xu**, Xiaofeng Zhu, Xiaoxiao Li. GATE: Graph CCA for Temporal SElf-supervised Learning for Label-efficient fMRI Analysis. IEEE Transactions on Medical Imaging (TMI, IF=11.0), 2022.
1. Yujie Mo, Liang Peng, **Jie Xu**, Xiaoshuang Shi, Xiaofeng Zhu. Simple Unsupervised Graph Representation Learning. AAAI Conference on Artificial Intelligence (AAAI), <span style="color: red;">**Oral presentation paper**</span>, 2022.
1. Lujing Wang, Weifeng Yuan, Lu Zeng, **Jie Xu**, Yujie Mo, Xinxiang Zhao, Liang Peng. Dementia Analysis from Functional Connectivity Network with Graph Neural Networks. Information Processing and Management (IPM, IF=8.6), 2022.

# 🏆 Honors and Awards

- UESTC Outstanding Doctor Graduate Thesis Award 2025
- UESTC Outstanding Doctor Graduate Students 2024
- National Scholarship 2019, 2022
- UESTC Academic Newcomer Award 2022
- UESTC Outstanding Bachelor Graduate Thesis Award 2020
- UESTC Outstanding Bachelor Graduate Students 2020
- UESTC Annual Scholarship for Outstanding Students 2017, 2018, 2019, 2021, 2022, 2023, 2024

# ✨ Talks

- *2024.11.28*, Research on Deep Multi-View Clustering Method for Realistic Complex Data Application Scenarios, invited by Prof. Xiao-Ning Li at Sichuan Normal University.
- *2024.05.02*, Deep Multi-View Learning towards Noisy Data, invited by Prof. [Zeyu Zhang](https://alex-zeyu.github.io/) at Huazhong Agricultural University.

# 🏫 Educations

- *2020.09 - 2024.12*, University of Electronic Science and Technology of China, Chengdu, China, Ph.D. of Computer Science and Technology.
- *2016.09 - 2020.06*, University of Electronic Science and Technology of China, Chengdu, China, B.Eng. of Computer Science and Technology.

# 💬 Services

- Program Committee Member of Conferences for CVPR 2022-2025, ICCV 2023-2025, ECCV 2022-2024, NeurIPS 2024-2025, ICML 2024-2025, ICLR 2025, AISTATS 2025, IJCAI 2025, AAAI 2024-2025, ACM MM 2023-2025, KDD 2022-2023, CIKM 2022-2025, SDM 2024 etc.
- Journal Reviewer for TPAMI, TIP, TKDE, TCYB, TNNLS, TCSVT, TCSS, TKDD, Pattern Recognition, Information Fusion, Information Sciences, IPM, ESWA, Neural Networks, Neurocomputing etc.

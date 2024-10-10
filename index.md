---
layout: home
title: Ziwen Zhao (Newiz)
permalink: /
---

\| <img align="center" height="17" src="https://imaginethatcreative.net/blog/wp-content/uploads/2023/06/2250206.png"> [Email](mailto:zwzhao@hust.edu.cn) \| 
<img align="center" height="14" src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg"> [Gmail](mailto:newiz1825@gmail.com) \|
<img align="center" height="18" src="https://github.githubassets.com/assets/apple-touch-icon-144x144-b882e354c005.png"> [GitHub](https://github.com/Newiz430) \|
<img align="center" height="18" src="https://scholar.google.com/favicon.ico"> [Google Scholar](https://scholar.google.com/citations?user=Um4uQawAAAAJ) \|
<img align="center" height="18" src="https://dblp.org/img/favicon.ico"> [DBLP](https://dblp.org/pid/194/6903.html) \|
<img align="center" height="18" src="https://static.licdn.com/aero-v1/sc/h/3loy7tajf3n0cho89wgg0fjre"> [LinkedIn](https://www.linkedin.com/in/ziwen-zhao-2454b2301) \|
<img align="center" height="16" src="https://static.zhihu.com/heifetz/favicon.ico"> [Zhihu](https://www.zhihu.com/people/just-now-18) \|

I am now a master student at the Intelligent and Distributed Computing Laboratory ([IDC-Lab](https://idc.hust.edu.cn/)), [Huazhong University of Science and Technology (HUST), Wuhan](https://cs.hust.edu.cn) (advised by [Prof. Yuhua Li](http://english.cs.hust.edu.cn/info/1701/1581.htm)), majoring in Computer Science. My research interest lies in deep learning, graph mining, weakly- and self-supervised pre-training, especially the task generalization ability of graph knowledge.

## News

* 2024.10: Got the 2024-2025 National Scholarship for postgraduates!
* 2024.08: The survey "[A Survey on Self-Supervised Graph Foundation Models: Knowledge-Based Perspective](https://arxiv.org/abs/2403.16137)" gets an update!
* 2024.03: My first survey paper "[A Survey on Self-Supervised Pre-Training of Graph Foundation Models: A Knowledge-Based Perspective](https://arxiv.org/abs/2403.16137)" is uploaded to <img align="center" height="18" src="https://arxiv.org/static/browse/0.3.4/images/arxiv-logo-one-color-white.svg"> as an ongoing project! Feel free to make suggestions!
* 2024.01: My paper "[Masked Graph Autoencoder with Non-discrete Bandwidths](https://arxiv.org/abs/2402.03814)" is accepted as a research track in TheWebConf (WWW)'24! Read my [Chinese blog](https://zhuanlan.zhihu.com/p/681841195) for more!
* 2023.04: My first paper "[CSGCL: Community-Strength-Enhanced Graph Contrastive Learning](https://arxiv.org/abs/2305.04658)" w/ [Dr. Han Chen](https://github.com/HanChen-HUST) is accepted as a main track in IJCAI'23! Read my [Chinese blog](https://zhuanlan.zhihu.com/p/628116694) for more!
* 2022.09: I'm now a master student at School of Computer Science and Technology, HUST, Wuhan.
* 2022.06: I got my double B.E. degree in Bioinformatics & Computer Science at HUST, Wuhan.

## Publications

#### [Masked Graph Autoencoder with Non-discrete Bandwidths](https://arxiv.org/abs/2402.03814) (WWW/TheWebConf'24 research track) ![Static Badge](https://img.shields.io/badge/CCF--A-blue)
**Ziwen Zhao**, Yuhua Li, Yixiong Zou, Jiliang Tang, Ruixuan Li  [[Code]](https://github.com/Newiz430/Bandana) [[Blog]](https://zhuanlan.zhihu.com/p/681841195)

We explore the non-discrete edge masking and prediction as a self-supervised GNN pre-training strategy. 

The discrete edge masking and binary link reconstruction strategy of existing topological masked graph autoencoders (TopoRecs) is insufficient to learn topologically informative representations, including blocked message flows, vulnerability to over-smoothness, and suboptimal neighborhood discriminability. We propose a novel model coined Bandana, which utilizes non-discrete edge masks - "bandwidths" - sampled from a continuous Boltzmann-Gibbs probability distribution. Bandana's bandwidth masking and prediction strategy is theoretically connected to regularized denoising autoencoders and energy-based models (EBMs). Bandana outperforms traditional discrete TopoRecs on node classification, link prediction, as well as graph manifold learning.

#### [CSGCL: Community-Strength-Enhanced Graph Contrastive Learning](https://arxiv.org/abs/2305.04658) (IJCAI'23 main track) ![Static Badge](https://img.shields.io/badge/CCF--A-blue)
Han Chen\*, **Ziwen Zhao\***, Yuhua Li, Yixiong Zou, Ruixuan Li, Rui Zhang  [[Code]](https://github.com/HanChen-HUST/CSGCL) [[Blog]](https://zhuanlan.zhihu.com/p/628116694)

A graph contrastive learning framework aiming to preserve community strength throughout the learning process. 

Firstly, we present two novel graph augmentation methods, Communal Attribute Voting (CAV) and Communal Edge Dropping (CED), where the perturbations of node attributes and edges are guided by community strength. Secondly, we propose a dynamic ''Team-up'' contrastive learning scheme, where community strength is used to progressively fine-tune the contrastive objective. CSGCL performs well on 3 different kinds of downstream graph tasks, indicating the task generalizability of community knowledge for graph models.

#### [A Survey on Self-Supervised Graph Foundation Models: Knowledge-Based Perspective](https://arxiv.org/abs/2403.16137) (<img align="center" height="18" src="https://arxiv.org/static/browse/0.3.4/images/arxiv-logo-one-color-white.svg">'24) ![Static Badge](https://img.shields.io/badge/survey-yellow)
**Ziwen Zhao\***, Yixin Su\*, Yuhua Li, Yixiong Zou, Ruixuan Li, Rui Zhang  [[Paper list]](https://github.com/Newiz430/Pretext)

We present a new graph knowledge-based taxonomy (9 types, 25+ pretexts) to categorize self-supervised GFMs, incl. GNNs, Graph Transformers, graph language models (GLMs), and more.

## Early Open-source Projects

#### Counting is All You Need: Weakly-Supervised Immunohistochemical Cell Segmentation and Localization by Numbers [[Code]](https://github.com/Newiz430/CellSegmentation)

A multi-stage auto-immunoquantitative analytical model based on Multiple Instance Learning for immune cell counting, localization and segmentation. 

Taking immunohistochemistry-stained digital cell images as input, the model is merely supervised by positive cell counting labels and transforms whole-image (bag) level counting results into superpixel (instance) level classification results via the specifically designed adaptive top-k instance selection strategy.

This work has achieved **4th place** in **Lymphocyte Assessment Hackathon** (LYSTO) Challenge. [Leaderboard](https://lysto.grand-challenge.org/evaluation/challenge/leaderboard/)


---

<font color=grey>
This page uses Jekyll theme <a href='http://jekyllthemes.org/themes/gitbook/'>Jekyll Gitbook</a> by <a href='https://github.com/sighingnow'>sighingnow</a>.
</font>

<br/>
<br/>

<div align=center>
<img src="assets/figure/logo.png" style="zoom:10%;" />
</div>

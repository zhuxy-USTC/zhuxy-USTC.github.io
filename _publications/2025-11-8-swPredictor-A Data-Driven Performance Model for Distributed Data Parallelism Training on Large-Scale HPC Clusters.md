---
title: "swPredictor: A Data-Driven Performance Model for Distributed Data Parallelism Training on Large-Scale HPC Clusters"
collection: publications
permalink: /publication/swPredictor
date: 2025-03-06
venue: 'Performance Evaluation: An International Journal (PEVA)'
rank: 2025
badge: 'PEVA 2025'
badge_class: 'badge-journal'
image: 'https://zhuxy-ustc.github.io/images/publications/swformer.jpg'
authors: '<strong>Xianyu Zhu</strong>, Ruohan Wu, Junshi Chen, Hong An'
author_list: '<strong>Xianyu Zhu¹</strong>, Ruohan Wu¹, Junshi Chen¹², Hong An¹²'
affiliations: '¹School of Computer Science and Technology, University of Science and Technology of China, Hefei, China<br>²Laoshan Laboratory, Qingdao, China'
description: 'A framework designed to accelerate foundation models via intra-op tiling and inter-op scheduling on the new Sunway Supercomputer.'
keywords: '<strong>Deep Learning</strong>, <strong>Foundation Model</strong>, <strong>Sunway Architecture</strong>, <strong>Fine-Grained Tiling</strong>,<strong>Operator Scheduling</strong>'
paperurl: 'http://zhuxy-USTC.github.io/files/swPredictor.pdf'
doi: 'https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-025-4761-0'
googlescholar: 'https://scholar.google.com/scholar?q=SwFormer+Enabling+Faster+Foundation+Models+Sunway+Supercomputer'
citation: ' Ruohan Wu,  Xianyu Zhu,  Junshi Chen,  Hong An &quot;SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling.&quot; Journal of Computer Science and Technology(JCST), 2025.'
bibtex: |
  @article{wu2025swformer,
    title={SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling},
    author={Wu, Ruohan and Zhu, Xianyu and Chen, Junshi and An, Hong},
    journal={Journal of Computer Science and Technology},
    year={2025},
    publisher={Springer}
  }
---


**************************************************************

**Keywords: swPredictor, FI-Net, FNO-Inception, Performance Modeling, HPC, Distributed Data Parallelism**


--------

## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">
<p style="text-align: justify;">
Deep learning's continuous evolution has driven the creation of increasingly large foundation models, such as GPT-3, which requires optimized performance on large-scale computing platforms. The new Sunway Supercomputer, equipped with numerous SW26010pro processors, supports AI workloads in both all-shared and single-CG modes. However, existing optimizations primarily target AI operators like Generalized Matrix Multiplication (GEMM) in the single-CG mode, leaving challenges in scaling performance across all 6 CGs in the all-shared mode. This paper introduces SwFormer, a framework designed to accelerate foundation models via intra-op tiling and inter-op scheduling. The intra-op tiling method breaks down operators into fine-grained tiled kernels and employs an offline profiling-based approach to determine the optimal tiling strategy. The inter-op scheduling method employs heuristic graph traversal algorithms to automatically reorder the computation of these tiled kernels, thereby maximizing hardware utilization. Compared with operator libraries for the all-shared mode such as SWDNNv2 and SWattention, SwFormer's intra-op tiling method accelerates end-to-end GPT-3 6.7B and 13B models training by up to 1.27x. Evaluated with GPT-style models, the inter-op scheduling approach further outperforms the intra-op tiling method by up to 1.32x.
</p>
</div>


--------

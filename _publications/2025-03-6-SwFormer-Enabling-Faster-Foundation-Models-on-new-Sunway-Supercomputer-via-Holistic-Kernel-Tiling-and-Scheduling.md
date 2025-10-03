---
title: "SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling"
collection: publications
permalink: /publication/SwFormer-Enabling-Faster-Foundation-Models-on-new-Sunway-Supercomputer-via-Holistic-Kernel-Tiling-and-Scheduling
date: 2025-03-06
venue: 'Journal of Computer Science and Technology (JCST)'
citation: ' Ruohan Wu,  Xianyu Zhu,  Junshi Chen,  Hong An &quot;SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling.&quot; Journal of Computer Science and Technology(JCST), 2025.'
---
 
## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">
<p style="text-align: justify;">
Deep learning's continuous evolution has driven the creation of increasingly large foundation models, such as GPT-3, which requires optimized performance on large-scale computing platforms. The new Sunway Supercomputer, equipped with numerous SW26010pro processors, supports AI workloads in both all-shared and single-CG modes. However, existing optimizations primarily target AI operators like Generalized Matrix Multiplication (GEMM) in the single-CG mode, leaving challenges in scaling performance across all 6 CGs in the all-shared mode. This paper introduces SwFormer, a framework designed to accelerate foundation models via intra-op tiling and inter-op scheduling. The intra-op tiling method breaks down operators into fine-grained tiled kernels and employs an offline profiling-based approach to determine the optimal tiling strategy. The inter-op scheduling method employs heuristic graph traversal algorithms to automatically reorder the computation of these tiled kernels, thereby maximizing hardware utilization. Compared with operator libraries for the all-shared mode such as SWDNNv2 and SWattention, SwFormer's intra-op tiling method accelerates end-to-end GPT-3 6.7B and 13B models training by up to 1.27x. Evaluated with GPT-style models, the inter-op scheduling approach further outperforms the intra-op tiling method by up to 1.32x.
</p>
<div>

<!-- [Original paper](http://zhuxy-USTC.github.io/files/SwFormer.pdf) and [Google Scholar Link](https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-025-4761-0){:target="_blank"} -->



<a href="http://zhuxy-USTC.github.io/files/SwFormer.pdf">Original paper</a> and <a href="https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-025-4761-0" target="_blank">🎓Google Scholar Link</a>

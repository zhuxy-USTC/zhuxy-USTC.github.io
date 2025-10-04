---
title: "SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling"
collection: publications
permalink: /publication/SwFormer-Enabling-Faster-Foundation-Models-on-new-Sunway-Supercomputer-via-Holistic-Kernel-Tiling-and-Scheduling
date: 2025-03-06
venue: 'Journal of Computer Science and Technology (JCST)'
paperbox: true
badge: 'JCST 2025'
badge_class: 'badge-journal'
image: '/images/publications/swformer.png'
citation: ' Ruohan Wu,  Xianyu Zhu,  Junshi Chen,  Hong An &quot;SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling.&quot; Journal of Computer Science and Technology(JCST), 2025.'
---

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge badge-journal">JCST 2025</div>
      <img src="/images/publications/swformer.png" alt="SwFormer Architecture" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><a href="https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-025-4761-0">SwFormer: Enabling Faster Foundation Models on new Sunway Supercomputer via Holistic Kernel Tiling and Scheduling</a></p>

    <p>Ruohan Wu, <strong>Xianyu Zhu</strong>, Junshi Chen, Hong An</p>

    <p>A framework designed to accelerate foundation models via intra-op tiling and inter-op scheduling on the new Sunway Supercomputer. The framework breaks down operators into fine-grained tiled kernels and employs heuristic graph traversal algorithms to maximize hardware utilization.</p>

    <p>Keywords: <strong>foundation models</strong>, <strong>kernel tiling</strong>, <strong>operator scheduling</strong>, <strong>Sunway supercomputer</strong>, <strong>GPT-3 optimization</strong></p>

    <p>
      <a href="http://zhuxy-USTC.github.io/files/SwFormer.pdf"><i class="fas fa-file-pdf"></i> PDF</a>
      <a href="https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-025-4761-0"><i class="fas fa-link"></i> DOI</a>
      <a href="https://scholar.google.com/scholar?q=SwFormer+Enabling+Faster+Foundation+Models+Sunway+Supercomputer"><i class="fas fa-graduation-cap"></i> Google Scholar</a>
    </p>
  </div>
</div>

## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">
<p style="text-align: justify;">
Deep learning's continuous evolution has driven the creation of increasingly large foundation models, such as GPT-3, which requires optimized performance on large-scale computing platforms. The new Sunway Supercomputer, equipped with numerous SW26010pro processors, supports AI workloads in both all-shared and single-CG modes. However, existing optimizations primarily target AI operators like Generalized Matrix Multiplication (GEMM) in the single-CG mode, leaving challenges in scaling performance across all 6 CGs in the all-shared mode. This paper introduces SwFormer, a framework designed to accelerate foundation models via intra-op tiling and inter-op scheduling. The intra-op tiling method breaks down operators into fine-grained tiled kernels and employs an offline profiling-based approach to determine the optimal tiling strategy. The inter-op scheduling method employs heuristic graph traversal algorithms to automatically reorder the computation of these tiled kernels, thereby maximizing hardware utilization. Compared with operator libraries for the all-shared mode such as SWDNNv2 and SWattention, SwFormer's intra-op tiling method accelerates end-to-end GPT-3 6.7B and 13B models training by up to 1.27x. Evaluated with GPT-style models, the inter-op scheduling approach further outperforms the intra-op tiling method by up to 1.32x.
</p>
</div>

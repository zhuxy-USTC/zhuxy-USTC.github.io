---
title: "LAD-Net: A Novel Light Weight Model for Early Apple Leaf Pests and Diseases Classification"
collection: publications
permalink: /publication/2023-03-01-LAD-Net-A-Novel-Light-Weight-Model-for-Early-Apple-Leaf-Pests-and-Diseases-Classification
date: 2023-03-01
venue: 'IEEE/ACM Transactions on Computational Biology and Bioinformatics'
badge: 'IEEE/ACM TCBB 2023'
badge_class: 'badge-journal'
image: '/images/publications/lad-net.jpg'
authors: '<strong>Xianyu Zhu</strong>, Jinjiang Li, Runchang Jia, Bin Liu, Zhuohan Yao, Aihong Yuan, Yingqiu Huo, Haixi Zhang'
author_list: '<strong>Xianyu Zhu¹</strong>, Jinjiang Li¹, Runchang Jia¹, Bin Liu¹, Zhuohan Yao¹, Aihong Yuan², Yingqiu Huo¹, Haixi Zhang¹'
affiliations: '¹College of Information Engineering, Northwest A&F University, Yangling, China<br>²College of Mechanical and Electronic Engineering, Northwest A&F University, Yangling, China'
description: 'A lightweight model achieving 98.58% accuracy for apple leaf disease recognition with only 1.25MB size, enabling real-time diagnosis on mobile devices.'
keywords: '<strong>apple leaf diseases</strong>, <strong>asymmetric convolution</strong>, <strong>real-time inference</strong>, <strong>mobile deployment</strong>'
paperurl: 'http://zhuxy-USTC.github.io/files/LAD-Net.pdf'
doi: 'http://dx.doi.org/10.1109/TCBB.2022.3191854'
googlescholar: 'https://scholar.google.com/citations?view_op=view_citation&hl=en&user=k2ajuuEAAAAJ&citation_for_view=k2ajuuEAAAAJ:9yKSN-GCB0IC'
citation: ' Xianyu Zhu,  Jinjiang Li,  Runchang Jia,  Bin Liu,  Zhuohan Yao,  Aihong Yuan,  Yingqiu Huo,  Haixi Zhang, &quot;LAD-Net: A Novel Light Weight Model for Early Apple Leaf Pests and Diseases Classification.&quot; IEEE/ACM Transactions on Computational Biology and Bioinformatics, 2023.'
bibtex: |
  @article{zhu2023ladnet,
    title={LAD-Net: A Novel Light Weight Model for Early Apple Leaf Pests and Diseases Classification},
    author={Zhu, Xianyu and Li, Jinjiang and Jia, Runchang and Liu, Bin and Yao, Zhuohan and Yuan, Aihong and Huo, Yingqiu and Zhang, Haixi},
    journal={IEEE/ACM Transactions on Computational Biology and Bioinformatics},
    year={2023},
    doi={10.1109/TCBB.2022.3191854},
    publisher={IEEE}
  }
---


**************************************************************

**Keywords: Apple leaf pests and diseases, asymmetric convolution, dilated convolution, real-time inference, convolutional neural networks, deep learning**

**************************************************************

## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">
<p style="text-align: justify;">
Aphids, brown spots, mosaics, rusts, powdery mildew and Alternaria blotches are common types of early apple leaf pests and diseases. These pests and diseases severely affect the yield and quality of apples.
Recently, deep learning has been regarded as the best classification model for apple leaf pests and diseases. However, models with large parameters have difficulty providing an accurate and fast diagnosis of apple leaf pests and diseases on mobile terminals.
This paper proposes a novel and real-time early apple leaf disease recognition model. AD Convolution is firstly utilized to replace standard convolution, which reduces the number of parameters and calculations. Meanwhile, a LAD-Inception is built to enhance the ability of extracting multiscale features of different - sized disease spots. Finally, the LAD-Net model is constructed by the LR-CBAM and the LAD-Inception modules. Global average pooling is used to replace a full connection, further reducing parameters.
The results show that the LAD-Net, with a size of only 1.25MB, can achieve a recognition performance of 98.58%. Additionally, it has a delay of only 15.2ms on HUAWEI P40 and 100.1ms on Jetson Nano. This illustrates that the LAD-Net can accurately recognize early apple leaf pests and diseases on mobile devices in real-time, providing portable technical support.
<p>
<!-- </div> -->



<a href="http://zhuxy-USTC.github.io/files/LAD-Net.pdf">📄Original paper</a>,  <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=k2ajuuEAAAAJ&citation_for_view=k2ajuuEAAAAJ:9yKSN-GCB0IC" target="_blank">🎓Google Scholar Link</a> and <a href="http://zhuxy-USTC.github.io/files/LAD-Net-poster.pdf">🪧Academic poster</a>



--------
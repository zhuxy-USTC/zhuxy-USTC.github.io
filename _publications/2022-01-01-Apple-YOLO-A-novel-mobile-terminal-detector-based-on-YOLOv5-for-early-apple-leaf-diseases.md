---
title: "Apple-YOLO: A novel mobile terminal detector based on YOLOv5 for early apple leaf diseases"
collection: publications
permalink: /publication/2022-01-01-Apple-YOLO-A-novel-mobile-terminal-detector-based-on-YOLOv5-for-early-apple-leaf-diseases
date: 2022-01-01
venue: 'In the proceedings of 2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC)'
badge: 'COMPSAC 2022'
badge_class: 'badge-conference'
image: 'https://zhuxy-ustc.github.io/images/publications/apple-yolo.jpg'
authors: 'Jinjiang Li, <strong>Xianyu Zhu</strong>, Runchang Jia, Bin Liu, Cong Yu'
author_list: 'Jinjiang Li¹, <strong>Xianyu Zhu¹</strong>, Runchang Jia¹, Bin Liu¹, Cong Yu¹'
affiliations: '¹College of Information Engineering, Northwest A&F University, Yangling, China'
description: 'A lightweight YOLOv5-based detector achieving 96.04% mAP with only 5.33MB size for real-time apple leaf disease detection on mobile devices.'
keywords: '<strong>YOLOv5</strong>, <strong>object detection</strong>, <strong>apple leaf diseases</strong>, <strong>mobile deployment</strong>'
paperurl: 'http://zhuxy-USTC.github.io/files/Apple-YOLO.pdf'
googlescholar: 'https://scholar.google.com/scholar?q=Apple+YOLO:+A+novel+mobile+terminal+detector+based+on+YOLOv5+for+early+apple+leaf+diseases'
citation: ' Jinjiang Li,  Xianyu Zhu,  Runchang Jia,  Bin Liu,  Cong Yu, &quot;Apple-YOLO: A novel mobile terminal detector based on YOLOv5 for early apple leaf diseases.&quot; In the proceedings of 2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC), 2022.'
bibtex: |
  @inproceedings{li2022appleyolo,
    title={Apple-YOLO: A novel mobile terminal detector based on YOLOv5 for early apple leaf diseases},
    author={Li, Jinjiang and Zhu, Xianyu and Jia, Runchang and Liu, Bin and Yu, Cong},
    booktitle={2022 IEEE 46th Annual Computers, Software, and Applications Conference (COMPSAC)},
    pages={1234--1241},
    year={2022},
    organization={IEEE}
  }
---


**************************************************************

**Keywords: YOLOv5, object detection, apple leaf diseases, mobile deployment**

--------

## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">

<p style="text-align: justify;">
Early detection of apple leaf diseases is the basis for timely precautions, which can inhibit the spread of the diseases and minimize the severe economic loss. Nowadays, CNN-based models are used for apple leaf diseases detection. However, due to the large model size and inference delay, the model is challenging to be transplanted to mobile terminals with good detection performance. This paper proposes a lightweight detection model Apple-YOLO on mobile terminals for real-time apple leaf diseases detection. First, a dataset named AppleSet8 is constructed using digital image processing and Mosaic data augmentation to improve the robustness and generalization ability of the model. Then the double-branch Apple-CSP module is presented to reduce the model parameters and guarantee feature extraction capability. Furthermore, the improved FDSA (Focus layer with depthwise separable convolution and attention mechanism) module effectively decreases the model's FLOPs and enhances the network's attention to the disease spots. Finally, the Skip-Spp (Skip connection and Spatial pyramid pooling) module is built to strengthen the detection performance for multi-scale disease spots. The experiment results show that mobile-based Apple-YOLO has achieved 96.04% mAP, the inference speed of 34 FPS, and the size is only 5.33 MB, indicating that Apple-YOLO is suitable for the real-time detection of early apple leaf diseases in the real scenario.
</p>
</div>

<!-- [Original paper](http://zhuxy-USTC.github.io/files/Apple-YOLO.pdf) and [Google Scholar Link](https://scholar.google.com/scholar?q=Apple+YOLO:+A+novel+mobile+terminal+detector+based+on+YOLOv5+for+early+apple+leaf+diseases){:target="_blank"} -->

<a href="http://zhuxy-USTC.github.io/files/Apple-YOLO.pdf">📄Original paper</a> and <a href="https://scholar.google.com/scholar?q=Apple+YOLO:+A+novel+mobile+terminal+detector+based+on+YOLOv5+for+early+apple+leaf+diseases" target="_blank">🎓Google Scholar Link</a>


--------
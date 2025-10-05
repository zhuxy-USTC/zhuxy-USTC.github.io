---
title: "Lightweight identification model for apple leaf diseases and pests based on mobile terminals"
collection: publications
permalink: /publication/2022-03-02-Lightweight-identification-model-for-apple-leaf-diseases-and-pests-based-on-mobile-terminals
date: 2022-03-02
venue: 'Transactions of the Chinese Society of Agricultural Engineering (TCSAE)'
badge: 'TCSAE 2022'
badge_class: 'badge-journal'
image: '/images/publications/als-net.jpg'
authors: 'Bin Liu, Runchang Jia, <strong>Xianyu Zhu</strong>, Cong Yu, Zhuohan Yao, Haixi Zhang, Dongjian He'
author_list: 'Bin Liu¹, Runchang Jia¹, <strong>Xianyu Zhu¹</strong>, Cong Yu¹, Zhuohan Yao¹, Haixi Zhang¹, Dongjian He²'
affiliations: '¹College of Information Engineering, Northwest A&F University, Yangling, China<br>²College of Mechanical and Electronic Engineering, Northwest A&F University, Yangling, China'
description: 'ALS-Net model achieving 99.43% accuracy with only 1.64MB size for real-time apple leaf disease identification on mobile terminals.'
keywords: '<strong>lightweight model</strong>, <strong>channel shuffle</strong>, <strong>knowledge distillation</strong>, <strong>mobile deployment</strong>'
paperurl: 'http://zhuxy-USTC.github.io/files/TCSAE.pdf'
googlescholar: 'https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=面向移动端的苹果叶部病虫害轻量级识别模型&btnG=&oq=面向'
citation: ' Bin Liu, Runchang Jia, Xianyu Zhu, Cong Yu, Zhuohan Yao, Haixi Zhang, Dongjian He, &quot;Lightweight identification model for apple leaf diseases and pests based on mobile terminals.&quot; Transactions of the Chinese Society of Agricultural Engineering (TCSAE). 2022'
bibtex: |
  @article{liu2022lightweight,
    title={Lightweight identification model for apple leaf diseases and pests based on mobile terminals},
    author={Liu, Bin and Jia, Runchang and Zhu, Xianyu and Yu, Cong and Yao, Zhuohan and Zhang, Haixi and He, Dongjian},
    journal={Transactions of the Chinese Society of Agricultural Engineering},
    volume={38},
    number={7},
    pages={145--155},
    year={2022}
  }
---


**************************************************************

## Abstract

<div style="font-family: 'Times New Roman', Times, serif;">
<p style="text-align: justify;">
Apple has been one of the most popular cash crops for the development of the agricultural economy. Seven common diseases have posed a serious threat to the yield and quality of apples, including the Mosaic, Alternaria spot, Brown spot, Powdery mildew, Aphid, Leafminer and Spider mite pests of plant leaves. Early diagnosis and control of diseases and pests can greatly contribute to preventing the spread and reducing losses in the apple industry. However, the current lightweight models cannot accurately identify the sparse small lesions in early apple leaves. In this study, a lightweight recognition model, ALS-Net (Apple Leaf Net using channel shuffle) was proposed for the resource-constrained mobile terminals. The specific procedure was as follows: 1) Firstly, 1 881 images of diseased and healthy apple leaves were collected in Qian County, Shaanxi Province in China. Digital image processing was conducted to enhance the original images, particularly for the generalization and robustness of the model. 2) Secondly, the ALS module was constructed using depth-wise separable convolution and channel shuffle technology. The calculations and parameters of the model were significantly reduced, compared with the traditional convolution network. The channel shuffle technology fully shuffled the information between channels, and then randomly assigned it to each channel. As such, the loss of accuracy was alleviated in group convolution. The Inception structure was introduced into the model for the multi-scale feature extraction. The channel attention was selected to strengthen the disease features in the network, while suppressing the natural background. The Exponential Linear Unit (ELU) was selected as the activation function to accelerate the convergence speed of the model. 3) The knowledge distillation strategy was used to train the model, providing the soft label information that the student model cannot learn on the hard label to realize the transfer of knowledge. The accuracy of the student model was approached or exceeded the accuracy of the teacher model. DenseNet-161 with high accuracy was selected as the teacher model, and the ALS-Net was the student model. A high-performance server was utilized to train the model for the generalization of the model. The experimental results were as follows. 1) The comparative experiment showed that the accuracy of ALS-Net reached 99.43%, which was higher than that of classical CNNs, such as AlexNet and ResNet, and the size of the model was only 1.64 MB, which was lower than that of lightweight CNNs, such as MobileNetV2 and ShuffleNetV2. 2) There were two sets of ablation experiments. The first verified the effects of expanding the convolution kernel to adjust the number of blocks on the model accuracy and parameter number. The second verified the effects of Inception structure, attention module, ELU activation function, and channel shuffle on the accuracy of the model. 3) The training of knowledge distillation strategy significantly improved the recognition accuracy, further accelerating the convergence speed during training. 4) Using PyTorch Mobile, the model was deployed on HUAWEI P40 Pro 5G mobile terminal for real-time inference. The inference delay of the mobile terminal was 55 ms, fully meeting the requirements of practical application. The automatic recognition of apple leaf diseases and pests was realized on the mobile terminal. The finding can provide an insightful idea for the early diagnosis of apple leaf diseases and pests.
<p>
<div>

<!-- [Original paper](http://zhuxy-USTC.github.io/files/TCSAE.pdf) and [Google Scholar Link](https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=面向移动端的苹果叶部病虫害轻量级识别模型&btnG=&oq=面向){:target="_blank"} -->

<a href="http://zhuxy-USTC.github.io/files/TCSAE.pdf">Original paper</a> and <a href="https://scholar.google.com/scholar?hl=zh-TW&as_sdt=0%2C5&q=面向移动端的苹果叶部病虫害轻量级识别模型&btnG=&oq=面向" target="_blank">🎓Google Scholar Link</a>


--------
---
title: "Research on early monitoring and warning of apple leaf diseases and development of inspection equipment based on artificial intelligence"
collection: projects
permalink: /projects/Research on early monitoring and warning of apple leaf diseases and development of inspection equipment based on artificial intelligence
# venue: "Testing Institute of America 2014 Annual Conference"
# date: 2014-03-01
# location: "Los Angeles, CA"
project_type: "Member; Provincial Key Research Program(2021 Jan to 2022 Dec)"
---

<h2>Project Content</h2>
* Establishment of Apple Leaf Diseases and Pests Sample Set and Big Data Platform
* Build a new real-time diagnosis model for early-stage diseases and pests of apple leaves.
* Develop an inspection robot for diseases and pests on apple leaves and create a monitoring and early warning platform.
* Construction, Integration and Demonstration Application of the Cloud-based Collaborative Platform


<h2>Project Aim</h2>
* Realize the automatic inspection in the orchard
* Construct monitoring and early warning platform

<h2>Project Difficulties</h2>
The deep convolutional neural network algorithm for diagnosing diseases and pests on apple leaves has become a research hotspot in the field of smart agriculture both at home and abroad. Although significant breakthroughs have been made in model construction and disease and pest diagnosis in previous research work, there are still some technical challenges in the real-time detection of early-stage diseases and pests on apple leaves and the development of related equipment:
* The sample set needs to fully cover the onset characteristics and patterns of early-stage diseases and pests on apple leaves. Given that the models in existing target detection technologies have extremely high requirements for early-stage images of diseases and pests, how to capture and collect sufficient early-stage disease and pest images under natural light conditions, and at the same time use data enhancement technologies such as generative adversarial networks to generate a large number of high-quality samples. Also, how to evaluate the quality of the generated samples from the two aspects of diversity and resolution to ensure the quality of the dataset is the first challenge in this project.
* Under open and complex environments, the diagnosis model for diseases and pests on apple leaves should have an adaptive mechanism. Since different neural network algorithms have their own advantages, how to integrate the advantages of these networks, propose an early-stage disease and pest detection model for apple leaves that takes into account both accuracy and speed, and how to achieve model adaptation in the face of unknown disease and pest situations is the second challenge in this project.
* Under natural conditions such as severe occlusion, the inspection robot should have comprehensive real-time monitoring capabilities. From the perspective of feature analysis, the samples to be detected have situations such as large differences within the same species, small differences between similar species, and serious lack of feature information, making the detection extremely difficult. Based on the research on model optimization and compression technologies for inspection robots of apple leaf diseases with limited resources, how to improve the inference speed of the robot's detection is the third challenge in this project.


## The demo of detection on the web

<div style="text-align: center;">
  <video width="640" height="360" controls 
         poster="http://zhuxy-USTC.github.io/images/apple_disease_thumbnail.jpg" 
         style="display: block; margin: auto;">
    <source src="http://zhuxy-USTC.github.io/videos/apple_disease_detection_web.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

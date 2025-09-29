---
title: "Early Diagnosis of Apple Leaf Pests and Diseases of Artificial Intelligence and Inspection Robots"
collection: projects
permalink: /projects/Early Diagnosis of Apple Leaf Pests and Diseases of Artificial Intelligence and Inspection Robots
# venue: "UC San Francisco, Department of Testing"
# location: "San Francisco, California"
project_type: "Leader; Provincial Innovative Entrepreneurial Training Plan Program (2021 May to 2022 May)"
---

<h2>Simple Introduction</h2>
<div style="text-align: center;">
<ul style="display: inline-block; text-align: left;">
<li>Propose Asymmetric and Dilated convolution, and construct a multi - scale feature extraction module named LAD-Inception.</li>
<li>Develop LAD-Net, achieving comprehensive optimization in terms of size, accuracy, and speed.</li>
<li>Transplant LAD-Net to Jetson TX2. Combine Jetson TX2 with a wheeled chassis to form an inspection robot, enabling the inspection and monitoring of the orchard.</li>
</ul>
</div>

<p style="text-align: justify;">
<div style="font-family: 'Times New Roman', Times, serif;">


This project proposes an identification and detection model based on a deep learning convolutional neural network for various common early diseases and pests of apple leaves. In addition, multiple lightweight models are adopted for the constructed network model, which solves the problem that it is difficult to deploy the model to mobile devices with limited resources due to its large size and high computational load. Moreover, the constructed and trained detection model has been successfully transplanted onto an independently developed inspection robot, enabling the robot to automatically inspect diseased leaves in the apple orchard. At the same time, the real-time detection images and historical detection results of the robot can be viewed remotely, which greatly improves the detection efficiency of early diseases and pests of apple leaves.
(1) Aiming at the problem that most of the current research on apple leaf diseases focuses on late-stage diseases and fails to detect diseases in a timely manner at the early stage of apple leaf diseases, a dataset containing 8 common early diseases of apple leaves, such as powdery mildew, aphids, spider mites, leafminers, rust, brown spot, alternate spot, and mosaic disease, has been constructed by conducting on-site investigations at apple planting bases and taking pictures of diseased leaves. Meanwhile, the dataset has been expanded to 12 times its original size through digital image processing methods, laying a good data foundation for the subsequent training of the deep learning convolutional neural network.
(2) Aiming at the problems that small spot diseases in early apple leaf diseases are difficult to detect and the detection accuracy drops significantly after the model is lightweighted, first, the novel Mosaic data augmentation technology is used. By stitching multiple images to be detected into one image, the dataset is expanded, and the number of small target spots on each image is increased. Then, the advantages of lightweight DW convolution and Ghost BottleNeck are combined with the advantage of CSPNet that can improve the detection accuracy, and the Apple-CSP module is proposed. Based on this, a lightweight apple leaf disease detection model for mobile devices is constructed.
(3) Aiming at the current problems of apple leaf disease models, such as high recognition accuracy but large model size, huge computational load, and high dependence on high-performance servers, a new convolution operation method, asymmetric dilated convolution, is proposed by combining asymmetric convolution and dilated convolution. Under the premise of ensuring that the receptive field remains unchanged and without the need to add Pooling, this convolution reduces the number of parameters to 24% of the original. Aiming at the problem that the recognition model has a poor recognition effect on multi-scale spots on apple leaves, the Inception module is introduced, and all the ordinary convolutions in the original Inception module are replaced with asymmetric dilated convolutions, and a residual module is added to construct the LAD-Inception structure. Based on the above improvements, an early disease and pest recognition model for apple leaves is constructed, which ensures extremely high recognition accuracy while lightweighting the model.
(4) Aiming at the problems that most current convolutional neural networks are difficult to deploy to mobile devices with limited resources and lightweight models cannot accurately recognize sparse small spots on early apple leaves, on the basis of the lightweight model ShuffleNetV2, the ALS module is constructed based on depthwise separable convolution and channel shuffle, which significantly reduces the computational load and the number of parameters of the model. Aiming at the problem that the dataset of early apple leaf diseases constructed is small in size and the trained model has low generalization ability, the knowledge distillation strategy is adopted to train the model, further improving the network accuracy. Based on the above innovative improvements, a lightweight recognition model, ALS-Net, is built.
(5) The constructed lightweight early apple leaf disease detection model has been successfully deployed on the Jetson TX2 embedded development board. After a detailed analysis of the current demand for the monitoring of apple leaf diseases and pests in the apple planting industry, we assembled the development board with a wheeled chassis and developed it into an intelligent automatic inspection robot, and successfully deployed the model on the robot. The robot developed in this project was completed in cooperation with the School of Mechanical and Electronic Engineering of our university. The functions of the robot, such as the autonomous navigation mobile platform, disease information uploading module, and control system, were mainly completed by the School of Mechanical and Electronic Engineering. By installing a LiDAR, data collection is realized to establish an orchard map, and the position of the robot is determined according to the map features around the robot. The control system includes a Raspberry Pi, Arduino, motor drive module, voltage stabilization module, and storage battery. The Raspberry Pi is used to write the robot model, create the basic function nodes of the robot, and establish the orchard map navigation and obstacle avoidance algorithm, while Arduino is used to control the speed of the robot using PWM and control the grass overturning and cleaning device using a relay. The Raspberry Pi and Arduino communicate through a USB serial port. The finally developed robot can detect diseases of apple leaves on both sides of the orchard road and upload the detection results to the cloud server through a wireless network. Moreover, the management personnel can remotely obtain the real-time detection images of the robot and carry out manual control.


<div>
</p>


## The demo of detection in the field experiment

<div style="text-align: center;">
  <video width="640" height="360" controls 
         poster="http://zhuxy-USTC.github.io/images/robot_based_detection_experiment.png" 
         style="display: block; margin: auto;">
    <source src="http://zhuxy-USTC.github.io/videos/robot_experiment.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>


---
title: "Automatic sample injection and image recognition device"
permalink: /Projects/Automatic-sample-injection-device/
excerpt: Cooperation with Suzhou Weimu Intelligent System Co., Ltd.  <br/> <a href="https://jianhua-WANG-BUAA.github.io/Projects/Automatic-sample-injection-device/"><img src="https://jianhua-WANG-BUAA.github.io/images/Automatic-sample-injection-device.png" alt="Automatic-sample-injection-device.png" border="0" width="500" /></a>
collection: Projects
date: 2019-05-23
tags:
  - projects
---

Duration: Nov. 2018 - Mai. 2019

Company:  [Suzhou Weimu Intelligent System Co., Ltd.](http://www.weimutech.com/) <img src="https://jianhua-WANG-BUAA.github.io/images/logo-SuzhouWeimu.png" alt="logo-SuzhouWeimu.png" border="0" width="300" />

Advisor: Liang HAN

## Background

<!-- 苏州微木是一家研制爆炸物痕迹检测设备的公司。面对逐步增加的爆炸物检测的需要，传统的人工逐个检测已经无法满足客户的需求。同时，传统的人工检测存在容易引入污染、存在人工误差等缺点。因此，公司希望我们能够设计一套实现采样、检测和结果识别的自动化系统。 -->

<p style="text-align:justify; text-justify:inter-ideograph;">
Suzhou Weimu is a company that develops explosive trace detection equipment. Faced with the increasing demand for explosives detection, traditional manual detection one by one can no longer meet the needs of customers. At the same time, traditional manual detection has the disadvantages of easily introducing pollution and artificial errors. Therefore, the company hopes that we can design an automated system for sampling, testing and result identification.
</p>

<p style="text-align:center">
<img src="https://jianhua-WANG-BUAA.github.io/images/pic-SuzhouWeimu-manuel.png" alt="pic-SuzhouWeimu-manuel.png" border="0" width="500" />
</p>

## Technical schema

<!-- 1.	通信方面，该项目使用ROS搭建通信网络。导航定位系统通过ROS节点将导航信息发送至地面站，地面站将控制指令通过ROS节点发送到处于同一局域网的无人车，实现对无人车编队的反馈控制。
2.	导航方面，该项目采用UWB定位系统来获取无人车编队的实时位置信息，采用外置的惯性测量单元获取无人车的偏航信息。并将这些信息通过ROS发送到地面站。
3.	无人车平台搭建方面，使用自组装的万向轮无人车，搭载机械手，通过树莓派实现和地面站的信息交换，并通过树莓派控制无人车的运动和机械手的动作。
4.	协同控制方面，我们通过ROS机器人系统收集并整合无人车的位置、偏航信息，并将信息传入地面站主控程序，通过协同控制算法计算导航数据和设定的表演轨迹得到控制指令。最后将控制指令发送给无人车，实现整个系统的闭环反馈控制。 -->

1. <p style="text-align:justify; text-justify:inter-ideograph;">Vacuum suction table is used to draw the test paper. The utilization of the vacuum suction table can effectively prevent the test paper from being contaminated by other liquids.</p>
2. <p style="text-align:justify; text-justify:inter-ideograph;">Raspberry Pi is the control center. The control program of servos and the subsequent program used to identify the detection results are all running on the Raspberry Pi. The control commands are issued through the GPIO pins of the Raspberry Pi.</p>
3. <p style="text-align:justify; text-justify:inter-ideograph;">The slide rail is employed to transport the test paper, and it is considered to replace it with a conveyor belt later. The other small connectors are designed by us with Catia V5 and manufactured by 3D printer.</p>


## Achievements

<p style="text-align:justify; text-justify:inter-ideograph;">
The video below shows the demo of the automatic sampling and sample injection and image recognition device that was finally delivered to the company. 😆
</p>

   <iframe width="560" height="315" src="https://www.youtube.com/embed/Ulxlb1NkKak" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Poster (in French)

  <img src="https://jianhua-WANG-BUAA.github.io/images/pic-poster.jpg" alt="pic-poster.jpg" border="0"/>

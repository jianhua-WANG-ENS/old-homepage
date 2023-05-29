---
layout: archive
title: "Competitions"
permalink: /Competitions/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->
<!-- My experiment reports and assignments can be found 📄 here (for reports and assignments that have electronic versions).

{% include base_path %}

{% for post in site.Competitions reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## 1. Youth Scientific Innovation Exchanges from China and France

Date: Nov. 2019

Advisor: Liang HAN

Award: **Best Innovation Award**


### 1.1 Background

<!-- 以麦克纳姆轮为代表的万向轮无人车具有运动灵活，控制简单等优点，能够适应复杂的地形。随着对机械臂模型研究的逐步深入，针对多自由度的复杂机械臂的控制技术日渐完善。由机械臂和万向轮小车组合而成的轮式机器人可以充分发挥二者的优势，能够很好地完成在复杂地形下的物体搬运等任务。 -->

<p style="text-align:justify; text-justify:inter-ideograph;">
The universal wheel unmanned ground vehicle (UGV) represented by the Mecanum wheel has the advantage of flexible movement, and can adapt to complex terrain. With the extensive research on the manipulator model, the control technology for the complex manipulator with multiple degrees of freedom is gradually improving. The wheeled robot, which is composed of a manipulator and a universal wheeled trolley, can give full play to the advantages of both, and can well complete tasks such as object handling under complex terrain.
</p>

### 1.2 Technical scheme

<!-- 1.	通信方面，该项目使用ROS搭建通信网络。导航定位系统通过ROS节点将导航信息发送至地面站，地面站将控制指令通过ROS节点发送到处于同一局域网的无人车，实现对无人车编队的反馈控制。
2.	导航方面，该项目采用UWB定位系统来获取无人车编队的实时位置信息，采用外置的惯性测量单元获取无人车的偏航信息。并将这些信息通过ROS发送到地面站。
3.	无人车平台搭建方面，使用自组装的万向轮无人车，搭载机械手，通过树莓派实现和地面站的信息交换，并通过树莓派控制无人车的运动和机械手的动作。
4.	协同控制方面，我们通过ROS机器人系统收集并整合无人车的位置、偏航信息，并将信息传入地面站主控程序，通过协同控制算法计算导航数据和设定的表演轨迹得到控制指令。最后将控制指令发送给无人车，实现整个系统的闭环反馈控制。 -->

1. <p style="text-align:justify; text-justify:inter-ideograph;">Communication: Robot Operating System (ROS) is utilized to build a communication network. The positioning system sends navigation information to the ground station through the ROS node, and the ground station sends the control command to the UGV in the same local network through the ROS node to realize feedback control of the multi-UGV formation.</p>
2. <p style="text-align:justify; text-justify:inter-ideograph;">Navigation: Ultra Wide Band (UWB) positioning system is used to obtain real-time position information of the multi-UGV. An external inertial measurement unit is employed to obtain the UGV's yaw angle, and the yaw angle is sended to the ground station through ROS.</p>
3. <p style="text-align:justify; text-justify:inter-ideograph;">UGV platform: the self-assembled universal wheel UGV is equipped with a manipulator. The Raspberry Pi is responsible for receiving the pose and attitude information of the UGV and generating the control command for the UGV and the manipulator.</p>

### 1.3 Achievements

The following video shows the scene of a coordinated formation of UAVs and UGVs equipped with manipulators. 😎

  <iframe width="560" height="315" src="https://www.youtube.com/embed/wzu0CHlsenE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


### 1.4 Team photo 

  <img src="https://jianhua-WANG-ENS.github.io/images/competition-china-french.jpg" alt="competition-china-french.jpg" border="0"/>

---------------------------

## 2. "Lijian Cup" Smart Aerospace Innovation Competition

Date: Sep. 2020

Advisor: Liang HAN

Award: Advance to the final

### 2.1 Overview 

<!-- 本项目结合沿海密集城市地区的环境特点，融入新的作战理念，从多域联合、智能决策、侦查威慑、战力组合等方面出发，提出构建拒止环境智能防御对抗体系的方案。 -->

<p style="text-align:justify; text-justify:inter-ideograph;">
This proposal combines the environmental characteristics of dense coastal urban areas and incorporates new operational concepts. Starting from the aspects of multi-domain cooperation, intelligent decision-making, reconnaissance deterrence, and combat power combination, we propose a plan to build an intelligent defense confrontation system against the denied environment.</p>


### 2.2 Overall plan

<!-- 系统架构方面，采用了马赛克开放系统架构，将总体的作战武力单元分为多个感知、决策和执行单元。通过引入对抗学习、强化学习、博弈论和分布式优化等方法，使得三种基本武力单元具备根据子战场战力需求和战争激烈程度进行动态分配重组的能力。因此整个系统可以实现对敌方战力的快速高效打击。下图展示了方案的总体架构。👇 -->

<p style="text-align:justify; text-justify:inter-ideograph;">
In terms of system architecture, a mosaic open system architecture is adopted to divide the overall combat force unit into multiple units of perception, decision-making, and execution. Through the introduction of adversarial learning, reinforcement learning, game theory, and distributed optimization methods, the three basic force units have the ability to dynamically allocate and reorganize according to the needs of sub-battlefield combat power and the intensity of the war. Thereby, it can achieve rapid and efficient strikes against enemy forces. 
</p>

The following figure shows the overall structure of the program. 👇


<img src="https://jianhua-WANG-ENS.github.io/images/competition-lijian-cup.png" alt="competition-lijian-cup.png" border="0"/>


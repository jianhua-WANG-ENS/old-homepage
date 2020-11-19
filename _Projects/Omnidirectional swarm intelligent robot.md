---
title: "Omnidirectional swarm intelligent robot"
permalink: /Projects/Omnidirectional-swarm-intelligent-robot/
excerpt: 👍 We won the **Best Innovation Award** in the "Youth Scientific Innovation Exchanges from China and France"! <br/> <a href="https://jianhua-WANG-BUAA.github.io/Projects/Omnidirectional-swarm-intelligent-robot/"><img src="https://jianhua-WANG-BUAA.github.io/images/Omnidirectional-swarm-intelligent-robot.png" alt="Omnidirectional-swarm-intelligent-robot.png" border="0" width="500" /></a>
collection: Projects
date: 2019-10-24
tags:
  - projects
---

Duration: Jul. 2019 - Nov. 2019

Advisor: Liang HAN

Award: **Best Innovation Award**

## Background

<!-- 以麦克纳姆轮为代表的万向轮无人车具有运动灵活，控制简单等优点，能够适应复杂的地形。随着对机械臂模型研究的逐步深入，针对多自由度的复杂机械臂的控制技术日渐完善。由机械臂和万向轮小车组合而成的轮式机器人可以充分发挥二者的优势，能够很好地完成在复杂地形下的物体搬运等任务。 -->

<p style="text-align:justify; text-justify:inter-ideograph;">
The universal wheel unmanned ground vehicle (UGV) represented by the Mecanum wheel has the advantage of flexible movement, and can be adapted to complex terrain. With the extensive research on the manipulator model, the control technology for the complex manipulator with multiple degrees of freedom is gradually improving. The wheeled robot, composed of a manipulator and a universal wheeled trolley, combines the advantages of both, and can well complete tasks such as object handling under complex terrain.
</p>

## Technical schema

<!-- 1.	通信方面，该项目使用ROS搭建通信网络。导航定位系统通过ROS节点将导航信息发送至地面站，地面站将控制指令通过ROS节点发送到处于同一局域网的无人车，实现对无人车编队的反馈控制。
2.	导航方面，该项目采用UWB定位系统来获取无人车编队的实时位置信息，采用外置的惯性测量单元获取无人车的偏航信息。并将这些信息通过ROS发送到地面站。
3.	无人车平台搭建方面，使用自组装的万向轮无人车，搭载机械手，通过树莓派实现和地面站的信息交换，并通过树莓派控制无人车的运动和机械手的动作。
4.	协同控制方面，我们通过ROS机器人系统收集并整合无人车的位置、偏航信息，并将信息传入地面站主控程序，通过协同控制算法计算导航数据和设定的表演轨迹得到控制指令。最后将控制指令发送给无人车，实现整个系统的闭环反馈控制。 -->

1. <p style="text-align:justify; text-justify:inter-ideograph;">Communication: Robot Operating System (ROS) is utilized to build a communication network. The positioning system sends navigation information to the ground station through the ROS node, and the ground station sends the control command to the UGV in the same local network through the ROS node to realize the feedback control of the multi-UGV formation.</p>
2. <p style="text-align:justify; text-justify:inter-ideograph;">Navigation: Ultra Wide Band (UWB) positioning system is used to obtain real-time position information of the multi-UGV systems. An external inertial measurement unit is employed to obtain the UGV's yaw angle that is sent to the ground station through ROS.</p>
3. <p style="text-align:justify; text-justify:inter-ideograph;">UGV platform: the self-assembled universal wheel UGV is equipped with a manipulator. The Raspberry Pi is responsible for receiving the pose and attitude information of the UGV and generating the control command for the UGV and the manipulator.</p>

## Achievements

The following video shows the scenario of a coordinated formation of UAVs and UGVs equipped with manipulators. 😎

  <iframe width="560" height="315" src="https://www.youtube.com/embed/wzu0CHlsenE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Team photo 

  <img src="https://jianhua-WANG-BUAA.github.io/images/competition-china-french.jpg" alt="competition-china-french.jpg" border="0"/>

# Course program

The course is organized in **two consecutive days**.

- During the **first day**, we will provide you with some basic elements in three different fields that are prominent in robotics:
  1. the use of a **middleware** that allows for an easy plumbing of the information on a distributed system;
  1. a very basic overview of the **PID control** that will enable the robot to move its head in a meaningful way;
  1. a quick introductory course on **Computer Vision** to give you the tools for processing images acquired from the cameras to let the robot respond to external stimuli.
- In the **second day**, instead, we will challenge you to realize in practice the lessons learned in the frame of a **team contest**.

## Day 1

### Welcome

| |
| :---: |
| 10:00 — 10:15 | 

### Basics on YARP middleware
[YARP](http://www.yarp.it/index.html) is an **operating system for robotics** that has been designed to facilitate a number of activities we have to deal with while developing the software that controls our robots. In particular, YARP is very good at mastering **data transmission** in a distributed system, abstracting the **software API** from the hardware details, and building **complex architectures** that regulate the high-level robot behaviors as a collection of simpler blocks.

Through hands-on sessions, you will learn how to make code snippets run as threads that exchange pieces of information with another program or even the robot. Then, you will also see how to command a motor of the robot head in a very simple manner.

| | |
| :---: | :---: | 
| 10:15 — 11:30 | [`slides`](https://github.com/easy-peasy-robotics/easy-peasy-robotics.github.io/blob/master/material/slides/yarp.pptx) |
| | [`tutorial_yarp-basics`](https://github.com/vvv-school/tutorial_yarp-basics) |
| 11:30 — 13:00 | [`assignment_yarp-find-rgb`](https://github.com/vvv-school/assignment_yarp-find-rgb) |

### Basic PID Control
**Controlling the motors** in different modalities is a necessary part to let our robot undertake the correct **action** in response to the cues received from the world. Among all the huge number of control tools engineers have, the **PID controller** is undoubtedly one of the **simplest** and at the same time **most effective** solution. Further, the PID is so **ubiquitous** in our life — it can control nearly everything, up to a given extent 😏 — that knowing how it works will certainly turn out to be a **resource** you will be happy to own.   

In this lesson plus hands-on, you will learn how to control the robotic head with velocity commands to make the iCub gaze at different points in the space moving its articulated neck and eyes systems. 

| | |
| :---: | :---: | 
| 14:00 — 15:30 | [`slides`](https://github.com/easy-peasy-robotics/easy-peasy-robotics.github.io/blob/master/material/slides/control.pptx) |
| 15:30 — 17:00 | [`assignment_control-pid`](https://github.com/vvv-school/assignment_control-pid) |

### Basic Computer Vision
Given you now know how to cope with the **action**, **perception** kicks in as the other side of the story. Therefore, to close the loop with the action, robots need to sense the world and gauge a large amount of information acquired from the surrounding.

In our settings, this means that you will learn how to analyze the content of the images the robot receives from the two cameras mounted in its eye bulbs. You will do so in terms of different **cues** (e.g. colors, shape, disparity...) and to perform some relevant **processing** (e.g. segmentation).

Additionally, we will briefly explain **image recognition** using traditional computer vision techniques. Although they have been quickly superseded by Deep-Learning based methods, traditional approaches still power many applications. Many of these algorithms are also available in computer vision libraries like **OpenCV** and work very well out of the box.

| | |
| :---: | :---: | 
| 17:00 — 18:30 | [`slides`](https://github.com/easy-peasy-robotics/easy-peasy-robotics.github.io/blob/master/material/slides/vision.pdf) |
| | [`tutorial_yarp-opencv`](https://github.com/vvv-school/tutorial_yarp-opencv) |
| | [`tutorial_find-wally`](https://github.com/vvv-school/tutorial_find-wally) |
| 18:30 — 20:00 | [`assignment_closest-blob`](https://github.com/vvv-school/assignment_closest-blob) |

## Day 2

:busts_in_silhouette: [Team contest](https://github.com/easy-peasy-robotics/easy-peasy-robotics.github.io/wiki/Team-contest) as final assignment on the 🤖

| | |
| :---: | :---: | 
| 09:00 — 19:00 | Non stop 😉 |

---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an MSCS student from [Thomas Lord Department of Computer Science](https://www.cs.usc.edu/), [University of Southern California](https://www.usc.edu/). I'm intereseted in computer vision, robot visual navigation and robot manipulation with multi-modal prompts. My current research is about empowering intelligent robots with pre-trained foundational models. 

I am very fortunate to be advised by [Prof. Laurent Itti](http://ilab.usc.edu/itti/) of iLab at USC.
You can find my CV here: [Chen's Curriculum Vitae](../assets/Chen_Liu_Resume.pdf).

Preprints
========
<img align="left" src="../images/profile.png" alt="clean-usnob" width="160" height="160"/> 
![World model-based Sim2Real Transfer for Robot Visual Navigatio](https://sites.google.com/usc.edu/world-model-sim2real)
Chen Liu*, Kiran Lekkala*, Laurent Itti

*Preprint. Under Review.*

We propose a robust system that integrates a control policy, trained within a simulator, with an internal LSTM-based world model and an external visual perception model, facilitating seamless application of the policy in real-world scenarios.

Real-world Robot Visual Navigation in a Simulator: A New Benchmark
---------
HengHui Bao*, Kiran Lekkala*, Chen Liu, Laurent Itti

*Preprint. Under Review.*

We collect a large augmented dataset comprising panoramic RGB images annotated with pose stamps and developed a simulator that allows for seamless evaluation of reinforcement learning methods on robot visual navigation tasks. 

Ongoing Research
========

Facilitating Diverse Manipulation with Vision-Language Model
-------
Chen Liu, Sumedh Sontakke, Daniel Seita, Laurent Itti

We introduce a multi-task robotic system that empowers robots to perform long-horizon manipulation tasks by mimicking a human demonstration video.

Language to Plans for Hierarchical Multi-Agent Path Finding
-------
Chen Liu, Satish Kumar Thittamaranahalli

We use a Large Language Model (LLM) to convert natural language instructions into high-level constraints for HMAPF problems.

Projects
========

[Schoomatic  - A Differential-Drive Robot Simulator](https://github.com/crellian/carla-scoomatic) 
-------
We develop a robot simulator built on CARLA and Unreal Engine 4, embracing all intrinsic CARLA features such as NPC traffic, variable weather conditions and global waypoint planning. Additionally, our codebase provides integration with RLLib and ROS environments.

[Navigation for Schoomatic](https://github.com/crellian/BeoPlan)
-------
We implement a ROS-based end-to-end robot navigation system including A* global path planning, Gmapping SLAM, LiDAR-based occupancy grid mapping, Timed-Elastic-Band obstacle avoidance, and PD motion control.

[Deep Learning-based Image Bad Weather Removal](../assets/weather.pdf)
-------
We improve the state-of-the-art transformer-based model, TransWeather, to restore images degraded by different bad weathers.

[CVLab](https://github.com/crellian/CVLab)
-------
We build a computer vision library including features such as: a template Matrix class with reference counting, matrix operations, image filters (linear, nonlinear, morphological, and Gabor), image pyramids, etc.


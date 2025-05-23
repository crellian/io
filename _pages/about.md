---
permalink: /
title: "Chen's Place"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an MSCS student from <a href="https://www.cs.usc.edu/" style="text-decoration:none">Thomas Lord Department of Computer Science</a>, <a href="https://www.usc.edu/" style="text-decoration:none">University of Southern California</a>. I am interested in improving generalization and sample-efficiency of reinforcement learning algorithms by pre-trained models and guiding agents with external knowledge (e.g., large language model or vision-language model). My current research is about visual navigation and manipulation problems.

I am very fortunate to be advised by <a href="http://ilab.usc.edu/itti/" style="text-decoration:none">Prof. Laurent Itti</a> of iLab at USC.
You can find my CV here: <a href="../assets/Chen_Liu_Resume.pdf" style="text-decoration:none">Chen's Curriculum Vitae</a>.

Preprints
========
<img  style="margin-top:4em;" align="left" src="../images/carlagstview.png" width="160" height="160"/> 
<td>
    <p style="margin-left:10em;">
    <a href="https://sites.google.com/usc.edu/world-model-sim2real" style="text-decoration:none">
        World model-based Sim2Real Transfer for Robot Visual Navigation  <br>
    </a>
    <strong>Chen Liu*</strong>, Kiran Lekkala*, Laurent Itti <br>
    <a href="https://arxiv.org/abs/2310.18847"> [ARXIV] </a> <em>6th Robot Learning Workshop at Neural Information Processing Systems (NeurIPS) 2023, NeurIPs Registration Award; Under Review for ICRA. </em> <br>
    We propose a robust system that integrates the control policy with pretrained visual perception model and LSTM-based robustness-enhanced world model, facilitating seamless application of the policy in real-world scenarios.</p>
</td>
<img  style="margin-top:4em;" align="left" src="" width="160" height="160"/> 
<td>
    <p style="font-size:200%" style="margin-left:10em;">Real-world Visual Navigation in a Simulator using Scene Generation: A new Benchmark<br>
    Kiran Lekkala, HengHui Bao, <strong>Chen Liu</strong>, Laurent Itti <br>
    <em>Under preparation. Presented at the 2023 Annenberg Research Symposium. Awarded cash prize. </em> <br>
    Dataset consisting of accurate posestamped RGB Panaromic images and Velodyne pointcloud scans, and collected using the stereo-velodyne rig on top of <a href="https://klekkala.github.io/hardware/"> Beobotv3 </a> within the USC campus. This dataset has wide range utilities including benchmarking NeRFs, 3D Reconstruction, Visual SLAM and also serves as an offline dataset for evaluating pretrained models for Visual Navigation. We also use this dataset for the GenNavGym; A simulator uses Generative Rendering models to evaluate Visual Navigation.</p>
</td>

Ongoing Research
========
<img  style="margin-top:1em;" align="left" src="../images/chrome-capture-2023-9-20.gif" width="160" height="160"/> 
<td>
    <p style="font-size:150px" style="margin-left:10em;">Facilitating Diverse Manipulation with Vision-Language Model<br>
    <strong>Chen Liu</strong>, Sumedh Sontakke, Laurent Itti <br>
    We introduce a multi-task robotic system that empowers robots to perform long-horizon manipulation tasks by mimicking a human demonstration video.</p>
</td>

Selected Projects
========
<img  style="margin-top:1em;" align="left" src="../images/scoomatic.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic" style="text-decoration:none">
        Schoomatic - A Differential-Drive Robot Simulator<br>
    </a>
    I develop a robot simulator built on CARLA and Unreal Engine 4, embracing features such as NPC traffic, variable weather conditions and global waypoint planning. Additionally, our codebase provides integration with <a href="https://github.com/crellian/schoomatic_visnav" style="text-decoration:none">RLLib</a> reinforcement learning framework and <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none"> ROS </a> environments.</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/autopilot.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none">
        Schoomatic Autopilot<br>
    </a>
    I implement a ROS-based end-to-end robot navigation system including A* global path planning, Gmapping SLAM, LiDAR-based occupancy grid mapping, Timed-Elastic-Band obstacle avoidance, and PD motion control.</p>
</td>
<img  style="margin-top:2em;" align="left" src="../images/multi-tasks.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="../assets/weather.pdf" style="text-decoration:none">
        Deep Learning-based Image Bad Weather Removal<br>
    </a>
    We improve the state-of-the-art transformer-based model, TransWeather, to restore images degraded by different bad weathers. We Implement and compare CBMA, LeFF, Coordinate Attention and Global-Enhanced Transformer to
adapt the model to heavy rain scenarios. We also design a cascaded model to improve the restoration performance</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/Lenna.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/CVLab" style="text-decoration:none">
        CVLab<br>
    </a>
    I build a computer vision library including features such as: a template Matrix class with reference counting, matrix operations, image filters (linear, nonlinear, morphological, and Gabor), image pyramids, etc.</p>
</td>


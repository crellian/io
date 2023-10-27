---
permalink: /
title: "Chen's Place"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an MSCS student from <a href="https://www.cs.usc.edu/" style="text-decoration:none">Thomas Lord Department of Computer Science</a>, <a href="https://www.usc.edu/" style="text-decoration:none">University of Southern California</a>. I'm intereseted in robot visual navigation and robot manipulation. My current research is about empowering intelligent robots with pre-trained foundational models. 

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
    <a href="../assets/Sim2Real_ICRA__Copy_.pdf"> [PDF] </a> <em>Submitted to International Conference on Robotics and Automation (ICRA) 2024. Under Review. </em> <br>
    We propose a robust system that integrates a control policy, trained within a simulator, with an internal LSTM-based robustness-enhanced world model and an external visual perception model, facilitating seamless application of the policy in real-world scenarios.</p>
</td>
<img  style="margin-top:2em;" align="left" src="" width="160" height="160"/> 
<td>
    <p style="font-size:200%" style="margin-left:10em;">Real-world Robot Visual Navigation in a Simulator: A New Benchmark <br>
    Kiran Lekkala, HengHui Bao, <strong>Chen Liu</strong>, Laurent Itti <br>
    <em>Submitted to Winter Conference on Applications of Computer Vision (WACV) 2024 Workshop. Preprint. </em> <br>
    We collect a large augmented dataset comprising panoramic RGB images annotated with pose stamps and developed a simulator that allows for seamless evaluation of reinforcement learning methods on robot visual navigation tasks.</p>
</td>

Ongoing Research
========
<img  style="margin-top:1em;" align="left" src="../images/chrome-capture-2023-9-20.gif" width="160" height="160"/> 
<td>
    <p style="font-size:150px" style="margin-left:10em;">Facilitating Diverse Manipulation with Vision-Language Model<br>
    <strong>Chen Liu</strong>, Sumedh Sontakke, Laurent Itti <br>
    We introduce a multi-task robotic system that empowers robots to perform long-horizon manipulation tasks by mimicking a human demonstration video.</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/mapf.png" width="160" height="160"/> 
<td>
    <p style="font-size:200%" style="margin-left:10em;">Language to Plans for Hierarchical Multi-Agent Path Finding<br>
    <strong>Chen Liu</strong>, Satish Kumar Thittamaranahalli <br>
    We use a Large Language Model (LLM) to convert natural language instructions into high-level constraints for HMAPF problems. (<a href="http://idm-lab.org/bib/abstracts/papers/hplan21.pdf" style="text-decoration:none">Image Source</a>)</p>
</td>

Selected Projects
========
<img  style="margin-top:3em;" align="left" src="../images/scoomatic.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic" style="text-decoration:none">
        Schoomatic - A Differential-Drive Robot Simulator<br>
    </a>
    We develop a robot simulator built on CARLA and Unreal Engine 4, embracing all intrinsic CARLA features such as NPC traffic, variable weather conditions and global waypoint planning. This involved developing dynamics, collisions and C++ plugins in Unreal
Engine 4, enabling client-server communication via remote procedure call (RPC), and packaging/releasing the
simulator as a Docker image. Additionally, our codebase provides integration with <a href="https://github.com/crellian/schoomatic_visnav" style="text-decoration:none">RLLib</a> and <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none"> ROS </a> environments.</p>
</td>
<img  style="margin-top:1em;" align="left" src="../images/autopilot.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none">
        Schoomatic Autopilot<br>
    </a>
    We implement a ROS-based end-to-end robot navigation system including A* global path planning, Gmapping SLAM, LiDAR-based occupancy grid mapping, Timed-Elastic-Band obstacle avoidance, and PD motion control.</p>
</td>
<img  style="margin-top:2em;" align="left" src="../images/multi-tasks.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="../assets/weather.pdf" style="text-decoration:none">
        Deep Learning-based Image Bad Weather Removal<br>
    </a>
    We improve the state-of-the-art transformer-based model, TransWeather, to restore images degraded by different bad weathers. We Implement and compare CBMA, LeFF, Coordinate Attention and Global-Enhanced Transformer to
adapt the model to heavy rain scenarios. Designed cascaded model to improve the restoration performance</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/Lenna.png" width="160" height="160"/> 
<td>
  <p style="font-size:200%" style="margin-left:10em;">
    <a href="https://github.com/crellian/CVLab" style="text-decoration:none">
        CVLab<br>
    </a>
    We build a computer vision library including features such as: a template Matrix class with reference counting, matrix operations, image filters (linear, nonlinear, morphological, and Gabor), image pyramids, etc.</p>
</td>


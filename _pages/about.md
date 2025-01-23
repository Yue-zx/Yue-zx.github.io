---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨‍💻 About me
- Research interests focus on embodied intelligence, reinforcement learning, and artificial intelligence, with a commitment to pursuing related projects and aiming to publish articles.
- Feel free to connect if interested in my work.
- Here is my [**Resume**](file/Resume_Zhixu%20Yue.pdf).

# 📖 Educations
- *2023.09 - now*  
  **Southwest University, Chongqing**  
  School of Computer and Information Science School of Software, Department of Automation
  - GPA: 87.04/100 or 4.0/5.0
  - Ranking: 1/99

# 💻 Experience
<div>
- *2024.06 - 2024.09*  
  **Research on Chongqing Zhongke Automotive Software Innovation Center, Chongqing**
  *Project leader*  
  **Project name:** Indoor Localization of Quadrotor UAV Based on Visual SLAM
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">UAV</div><img src='images/experience1-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  - Assembled the drone by soldering and integrating hardware components such as Pixhawk 4 flight controller and Jetson Orin NX onboard computer; flashed PX4 firmware onto the flight controller, tuned PID parameters, and conducted takeoff testing.
  - Deployed the ORB-SLAM algorithm on the onboard computer and performed debugging and adaptation using the official dataset.
  - Remotely controlled the drone's flight and used the ROS2 system to interface with the depth camera. Applied the ORB_SLAM algorithm to perform sparse 3D reconstruction of the surrounding environment, and used Octomap tools and PCL algorithms to convert the point cloud into a 3D map.
</div>
</div>
</div>
  
# 🎖 Honors and Awards
- *2024.10*, **National Scholarship** (¥10000, Top1%) 
- *2024.09*, **First Prize** in Chongqing of China Undergraduate Mathematical Contest in Modeling
- *2024.05*, **Meritorious Winner** of American Mathematical Contest in Modeling (MCM)
- *2024.08*, **Second Prize** of TI Cup Chongqing College Student Electronic Design Competition
- *2024.08*, **First Prize** of Digital and Physical Integration Intelligent Algorithm Challenge

<br>
*This website is adapted from the open-source template by [RayeRen](https://github.com/RayeRen/acad-homepage.github.io).*

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

# 📖 About me
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

# 📖 Educations
- *2023.09 - now*  
  **Southwest University, Chongqing**  
  School of Computer and Information Science School of Software, Department of Automation
  - GPA: 87.04/100 or 4.0/5.0
  - Academic Ranking: 4/99  
    Overall Evaluation: 1/99
  - Core Courses:  
    Linear Algebra (97); Fundamentals of Circuits (96); Analog Circuits (94); Complex Functions and Integral Transforms (93); Data Structures and Algorithms (83)

# 💻 Experience
- *2024.06 - 2024.09*  
  **Research on Chongqing Zhongke Automotive Software Innovation Center, Chongqing**  
  *Project leader*  
  **Project name:** Indoor Localization of Quadrotor UAV Based on Visual SLAM
  - Assembled the drone by soldering and integrating hardware components such as Pixhawk 4 flight controller and Jetson Orin NX onboard computer; flashed PX4 firmware onto the flight controller, tuned PID parameters, and conducted takeoff testing.
  - Deployed the ORB-SLAM algorithm on the onboard computer and performed debugging and adaptation using the official dataset.
  - Remotely controlled the drone's flight and used the ROS2 system to interface with the depth camera. Applied the ORB_SLAM algorithm to perform sparse 3D reconstruction of the surrounding environment, and used Octomap tools and PCL algorithms to convert the point cloud into a 3D map.

# 🎖 Honors and Awards
- *2024.10*, **National Scholarship** (¥10000, Top1%) 
- *2024.09*, **First Prize** in Chongqing of China Undergraduate Mathematical Contest in Modeling
- *2024.05*, **Meritorious Winner** of American Mathematical Contest in Modeling (MCM)
- *2024.08*, **Second Prize** of TI Cup Chongqing College Student Electronic Design Competition
- *2024.08*, **First Prize** of Digital and Physical Integration Intelligent Algorithm Challenge

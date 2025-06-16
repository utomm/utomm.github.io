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

I am currently a research assistant at Visual Intelligence and System Group, Computer Vision Lab, ETH Zurich, working on visual-motor policy for manipulator and legged robots.

I graduated from ShenYuan Honors College, Beihang University (Beijing University of Aeronautics and Astronautics, BUAA) with a Bachelor's degree and from the Robotics Institute of Beihang University with a Master's degree, supervised by Prof. Wang Wei.

While my current research focuses on how (data-driven) **perceptions and control** can make robots more **autonomous and intelligent**, I also have a strong passion for hardware design and real world experiments, stemming from my background as an engineering student who embarked from the field of **Mechatronics**. 

For more details, please check my [published papers](https://scholar.google.com/citations?user=BlK2gEAAAAAJ) <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"> about **SLAM** and **Robot Learning**. You can also have a look at my previous tiny projects about robotics and automation.


# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><video muted autoplay loop alt="sym" width="100%" poster="images/MBTT.webp">
    <source src="images/MBTT.mp4" type="video/mp4">
</video></div></div>
<div class='paper-box-text' markdown="1">

[M3PC: Test-time Model Predictive Control for Pretrained Masked Trajectory Model](https://arxiv.org/abs/2412.05675v1)

Kehan Wen†, **Yutong Hu**†, Yao Mu*, Lei Ke* 

[**Project**](https://sites.google.com/view/m3pc) \| [**Code**](https://github.com/wkh923/m3pc)

<strong><span class='show_paper_citations' data=''></span></strong>
- Enhance Masked Transformer for Offline RL by employing versatile capabilities from the Model itself for runtime Predictive Control.
- Achieve better performance in offline RL and offline-to-online RL for both simulated and real-world robotic tasks, with additional goal-reaching capabilities.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><video muted autoplay loop alt="sym" width="100%" poster="images/ball.webp">
    <source src="images/ball.mp4" type="video/mp4">
</video></div></div>
<div class='paper-box-text' markdown="1">

[DexDribbler: Learning Dexterous Soccer Manipulation via Dynamic Supervision](https://arxiv.org/abs/2403.14300)

**Yutong Hu***, Kehan Wen, Fisher Yu<span style="color:white">, Yifan Liu</span>

[**Project**](https://sites.google.com/view/dex-soccer-dribbler/home) \| [**Code**](https://github.com/SysCV/soccer-player) 
<strong><span class='show_paper_citations' data=''></span></strong>
- Make quadrupedal robot able to dribble and kick soccer ball using only ego-vision camera and onboard sensors.
- Transfer the skill from Sim to Real by using a virtual Feedback Controller to guide the Deep Reinforcement Learning process of a implicit Policy Network from Massively Parallel Simulation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L & IROS 2022</div><video muted autoplay loop alt="sym" width="100%" poster="images/SPD.webp">
    <source src="images/SPD-SLAM.mp4" type="video/mp4">
</video></div></div>
<div class='paper-box-text' markdown="1">

[Making Parameterization and Constrains of Object Landmark Globally Consistent via SPD (3) Manifold](https://arxiv.org/abs/2204.10552)

**Yutong Hu**, Wei Wang*

<strong><span class='show_paper_citations' data='BlK2gEAAAAAJ:u-x6o8ySG0sC'></span></strong>
- Propose A Mono-camera SLAM system that can provide map with sematic-meaningful Ellipsoid landmarks to represent object in the indoor scenes.
- Further improvements on the representation of the 9-DOF object landmarks (Rotation, Translation, Scale), resulting in an improved Object SLAM system with faster and more accurate back-end mapping manifold optimization process.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L & ICRA 2022</div><img src='images/sym.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SO-SLAM: Semantic object slam with scale proportional and symmetrical texture constraints](https://arxiv.org/abs/2109.04884)

Ziwei Liao, **Yutong Hu**, Jiadong Zhang, Xianyu Qi, Xiaoyu Zhang, Wei Wang*

<strong><span class='show_paper_citations' data='BlK2gEAAAAAJ:d1gkVwhDpl0C'></span></strong>
- Enhance monocular object SLAM algorithm by fully coupling three spatial structure (Symmetrical, Plane-Tangent, Scale) constraints for indoor environments.
- Propose a sampling-based method to detect the texture symmetry for objects in monocular images.
</div>
</div>

<!-- <br/>

<span class="highlight-blue">RA-L & ICRA 2022</span>&nbsp;[SO-SLAM: Semantic object slam with scale proportional and symmetrical texture constraints](https://arxiv.org/abs/2109.04884), Ziwei Liao, **Yutong Hu**, et al. -->


<span class='anchor' id='tiny-projects'></span>
# ⚙️ Tiny Projects


<html>
<head>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* Creates as many columns of min 250px as can fit */
            gap: 10px; /* Spacing between grid items */
            padding: 10px;
        }
        .grid-item {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .grid-item img {
            max-height: 180px;
            width: auto;
            margin-bottom: 10px; /* Space between the image and the text */
        }
        .caption {
            height: 30px;
            width: 90%;
            text-align: center;
            text-align: center;
            background-color: #f0f0f0; /* Gray background */
            padding: 5px 10px; /* Slightly larger than the text */
            border-radius: 5px; /* Rounded corners */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);  
        }
                    
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">
            <img src="images/dragon.webp" alt="Image 1">
            <div class="caption"><p>Dragon-like Worm</p> </div>
        </div>
        <div class="grid-item">
            <img src="images/walker.webp" alt="Image 2">
            <div class="caption">8-bar Linkage Walker</div>
        </div>
        <div class="grid-item">
            <img src="images/paper.webp" alt="Image 3">
            <div class="caption">Smartphone-controlled Paper Plane</div>
        </div>
        <div class="grid-item">
            <img src="images/maglev.webp" alt="Image 4">
            <div class="caption">Maglev Prototype</div>
        </div>
        <div class="grid-item">
            <img src="images/maze.webp" alt="Image 5">
            <div class="caption">2-joint Maze Solver</div>
        </div>
        <div class="grid-item">
            <img src="images/grasp.webp" alt="Image 6">
            <div class="caption">Sim2Real Grasping</div>
        </div>
    </div>
</body>
</html>




# 📖 Educations
- *2020.09 - 2023.03：* M.Phil., the Robotics Institute, School of Mechanical Engineering and Automation, Beihang University
- *2016.09 - 2020.06：* B.Eng., ShenYuan Honors College, Beihang University


# 💻 Internships
- *2023.07 - 2024 (Now)：* Research Assistant @ Visual Intelligence and System Group, Computer Vision Lab, ETH Zurich.
- *2022.05 - 2022.11：* Research Intern @ [Samsung Research Center](https://research.samsung.com/robotics), Beijing.

# 🎖 Honors and Awards
- *2023.03：* Graduate Excellence in Beijing Province
- *2023.01：* Samsung 2022 Best Intern 
- *2023.01：* Outstanding Master Thesis Award in Beihang University
- *2022.12：* Robotics Institute Founder's Scholarship (1/year)
- *2016, 2018-2019, 2020, 2022：* Annual Full Scholarship

---

<html>
<body>
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=a5a5a5&w=300&t=tt&d=0IgJWoXAmV8VcT-Y8cwpwADxpkSlsG5eGUpxm_MiWvM&co=ffffff&ct=000000&cmo=4c846f&cmn=bc7575&w=400'></script>
</body>
</html>

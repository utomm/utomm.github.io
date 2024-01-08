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

I am currently a research assistant at Visual Intelligence and System Group, Computer Vision Lab, ETH Zurich, working on visual-locomotion control for manipulator and legged robots.

I graduated from ShenYuan Honors College, Beihang University (Beijing University of Aeronautics and Astronautics, BUAA) with a Bachelor's degree and from the Robotics Institute of Beihang University with a Master's degree, supervised by Prof. Wang Wei.

While my current research focuses on how (data-driven) **perceptions** can make robots more **autonomous and intelligent**, I still have a strong passion for hardware design and real world experiments, stemming from my background as an engineering student who embarked from the field of **Mechatronics**. 

For more details, please check my [published papers](https://scholar.google.com/citations?user=BlK2gEAAAAAJ) <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> about **SLAM** and **Robot Learning**. You can also have a look at my previous tiny projects about robotics and automation.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/dribble-web.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DexDribbler: Learning Dexterous Soccer Control via Adaptable Feedback Supervision]()

**Yutong Hu**, et.al.

<strong><span class='show_paper_citations' data=''></span></strong>
- Make quadrupedal robot able to dribble and kick soccer ball using only ego-vision camera and onboard sensors.
- Transfer the skill from Sim to Real by distilling a Feedback based Motion Prior into an implicit Policy Network learned from Massively Parallel Deep Reinforcement Learning process.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L & IROS 2022</div><img src='images/spd-web.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Making Parameterization and Constrains of Object Landmark Globally Consistent via SPD (3) Manifold](https://arxiv.org/abs/2204.10552)

**Yutong Hu**, Wang Wei

<strong><span class='show_paper_citations' data='BlK2gEAAAAAJ:u-x6o8ySG0sC'></span></strong>
- Propose A Mono-camera SLAM system that can provide map with sematic-meaningful Ellipsoid landmarks to represent object in the indoor scenes.
- Further improvements on the representation of the 9-DOF object landmarks (Rotation, Translation, Scale), resulting in an improved Object SLAM system with faster and 22% more accurate back-end mapping manifold optimization process.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L & ICRA 2022</div><img src='images/sym-web.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[So-slam: Semantic object slam with scale proportional and symmetrical texture constraints](https://arxiv.org/abs/2109.04884)

Ziwei Liao, **Yutong Hu**, Jiadong Zhang, Xianyu Qi, Xiaoyu Zhang, Wei Wang

<strong><span class='show_paper_citations' data='BlK2gEAAAAAJ:d1gkVwhDpl0C'></span></strong>
- Enhance monocular object SLAM algorithm by fully coupling three spatial structure (symmetrical, plane-Tangent, scale) constraints for indoor environments.
- Propose a sampling-based method to detect the texture symmetry for objects in monocular images.
</div>
</div>

# ⚙️ Tiny Projects

<html>
    <table style="border-collapse: collapse; width: 100%; text-align: center;">
        <tr>
            <td>
                <img src="images/dragon-web.gif" alt="Image 1" style="height: 180px;">
                <br>
                <br>
                Dragon-like Worm
            </td>
            <td>
                <img src="images/walker-web.gif" alt="Image 2" style="height: 180px;">
                <br>
                <br>
                8-bar Linkage Walker
            </td>
            <td>
                <img src="images/paper-web.gif" alt="Image 3" style="height: 180px;">
                <br>
                <br>
                Smartphone-controlled Paper Plane
            </td>
        </tr>
        <tr>
            <td>
                <img src="images/maglev-web.gif" alt="Image 4" style="height: 180px;">
                <br>
                <br>
                Maglev Prototype
            </td>
            <td>
                <img src="images/maze-web.gif" alt="Image 5" style="height: 180px;">
                <br>
                <br>
                2-joint Maze Solver
            </td>
            <td>
                <img src="images/grasp-web.gif" alt="Image 6" style="height: 180px;">
                <br>
                <br>
                Sim2Real Grasping
            </td>
        </tr>
    </table>
</html>



# 📖 Educations
- *2020.09 - 2023.03：* M.Phil., the Robotics Institute, School of Mechanical Engineering and Automation, Beihang University
- *2016.09 - 2020.06：* B.Eng., ShenYuan Honors College, Beihang University


# 💻 Internships
- *2023.07 - 2024 (Now)：* Research Assistant @ Visual Intelligence and System Group, Computer Vision Lab, ETH Zurich.
- *2022.05 - 2022.10：* Research Intern @ [Samsung Research Center](https://research.samsung.com/robotics), Beijing.

# 🎖 Honors and Awards
- *2024.01：* Samsung 2023 Best Intern
- *2024.01：* Outstanding Master Thesis Award in Beihang University
- *2024.01：* Outstanding Graduates Award in Beijing province
- *2023.11：* Robotics Institute Founder's Scholarship (1/year)
- *2016,2018-2019,2020, 2022：* Annual Full Scholarship
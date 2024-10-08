---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Work Experience
* **Research Scientist, Aalto University, Espoo, Finland**  
  *Nov 2021 - Present*
  - Research in safe and robust reinforcement learning algorithms for robotics.
  - **Keywords:** Safe Reinforcement Learning, Safe Exploration, Robust Reinforcement Learning.
  - **Key Technologies:** Python, PyTorch, ROS2, Docker, LaTeX
  - **Key Achievements:** 
    - Developed uncertainty-aware safe exploration for reinforcement learning using text-based constraints using a Bayesian cost model, making the agent safely operate in complex, unknown environments (under review); 
    - Developed robust reinforcement learning algorithm for fast adaptation to unseen dynamical changes using adaptive control (under review).

* **Machine Learning Engineer, Huawei Research Center, Moscow, Russia**  
  *September 2019 - October 2021*  
  - Conducted research and development in deep learning algorithms for image enhancement and super-resolution.
  - **Key Technologies:** Python, TensorFlow, PyTorch, OpenCV, Git. 
  - **Keywords:** Super-resolution, Deblurring, Normalizing Flows, Image Segmentation.
  - **Key Achievements:** 
    - Developed a deep learning solution for demosaicing of underscreen camera photos, improving image quality by 15%. 
    - Designed a super-resolution algorithm based on Normalizing Flows that enhanced image resolution.

* **Intern Software Engineer, Samsung Research Russia, Moscow, Russia**  
  *June 2018 - August 2019*  
  - Developed AI-based Mobile Testing Automation for Android.
  - **Key Technologies:** Python, PyTorch, Bash, Git, OpenStack.
  - **Key Achievements:** 
    - Created a benchmark of environments for mobile testing automation, leading to faster feature deployment and testing.
    - Received award an outstanding work certificate for significant contributions to the OVS-OpenStack system, which streamlined deployment processes.

# Education
* **Ph.D. Candidate in Electrical Engineering, Aalto University**  
  *January 2022 - Present*  
  - **Professional Interests:** Enthusiastic about applying advanced machine learning techniques in real-world industry settings.
  - **Research Focus:** Safe Reinforcement Learning, Safe Exploration, Robust Reinforcement Learning.
  - **GPA:** 4.52 / 5
  - **Courses:** Reinforcement Learning, Deep Learning, Bayesian Machine Learning.

* **M.Sc. in Applied Mathematics, Lomonosov Moscow State University**  
  *September 2018 - May 2020*  
  - **GPA:** 4.05 / 5
  - **Courses:** Control Engineering, Optimal Control, Programming (Python, C++).

* **B.Sc. in Physics, Lomonosov Moscow State University**  
  *September 2014 - May 2018*  
  - **GPA:** 4.51 / 5
  - **Courses:** Advanced Calculus, Linear Algebra, Group Theory, Advanced Physics, Quantum Mechanics.

# Skills
* **Programming Languages:**
  - Python, C++, MATLAB
* **Machine Learning Frameworks:**
  - PyTorch, TensorFlow, Pandas, NumPy, SciPy
* **Software Tools:**
  - Linux, Git, Docker, Robot Operating System (ROS)
* **Languages:**
  - English (C1), Swedish (B1), German (A2), Finnish (A1), Russian (native)

# Certifications
* **Generative AI with Large Language Models, Coursera**  
  *July 2024*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<embed src="{{ site.baseurl }}/files/nikita_kostin_cv.pdf" width="600" height="700" type='application/pdf'> 

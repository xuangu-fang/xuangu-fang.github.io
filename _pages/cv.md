---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV here](/files/resume_Fang%20Shikai%20v1.7.pdf)

Education
======
* Ph.D. in Computer Science, University of Utah, 2024
* M.S. in Computer Science, Temple University, 2019
* B.S. in Statistics and Computer Science (double degree), University of Science and Technology of China (USTC), 2018

Work experience
======
* Summer 2024 - Present: Senior Researcher
  * Microsoft Research Asia
  * Research focus: Bayesian machine learning, tensor learning, physics-informed machine learning

* 2019 - 2024: Ph.D. Student
  * University of Utah, School of Computing
  * Scientific Computing and Imaging Institute
  * Advisors: Prof. Shandian Zhe and Prof. Mike Kirby
  * Research focus: Bayesian machine learning, tensor decomposition, streaming inference

* 2018 - 2019: M.S. Student
  * Temple University
  * Research focus: Machine learning and data mining

* 2014 - 2018: B.S. Student
  * University of Science and Technology of China (USTC)
  * School of the Gifted Young (少年班学院)
  * Double degree in Statistics and Computer Science

Skills
======
* **Machine Learning**: Bayesian methods, deep learning, tensor decomposition, sparse learning
* **Programming**: Python, C++, MATLAB, R
* **Frameworks**: PyTorch, TensorFlow, JAX, NumPy, SciPy
* **Applications**: Time series analysis, computer vision, natural language processing
* **Domains**: Physics-informed ML, medical AI, quantitative finance

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
  
Service and leadership
======
* **Reviewer**: ICML, NeurIPS, ICLR, UAI, AAAI, IJCAI, KDD, ICDM
* **Teaching Assistant**: Multiple courses in machine learning and data mining at University of Utah
* **Mentor**: Undergraduate and graduate students in research projects
* **Community**: Active contributor to open-source machine learning projects

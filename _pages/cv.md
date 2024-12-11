---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
description: "Curriculum Vitae of Zih-Ching (Virginia) Chen, detailing education, work experience, skills, publications, talks, teaching, and service."
---

{% include base_path %}

# Education
=====
* **Master of Communication Engineering**, National Taiwan University, Taipei, Taiwan, 2021 - 2023
* **Bachelor of Economics**, National Taiwan University, Taipei, Taiwan, 2017 - 2021

# Work Experience
=====
* **Spring 2024: Academic Pages Collaborator**
  * **GitHub University**
  * Duties include: Updates and improvements to template
  * Supervisor: The Users

* **Fall 2015: Research Assistant**
  * **GitHub University**
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* **Summer 2015: Research Assistant**
  * **GitHub University**
  * Duties included: Tagging issues
  * Supervisor: Professor Git

# Skills
=====
* **Programming Languages**
  * Python, C/C++, JavaScript, R, Stata
* **Machine Learning Libraries**
  * PyTorch, TensorFlow, CUDA, Scikit-learn
* **Tools and Platforms**
  * Git, Linux, LaTeX, React.js, Node.js
* **Languages**
  * Mandarin (Native), English (Fluent)

# Publications
=====
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

# Teaching
=====
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

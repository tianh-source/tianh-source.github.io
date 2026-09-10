---
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

# Hou Tian
**Date of Birth:** 1995‑01‑23 | **Hometown:** Weifang, Shandong Province
**Address:** School of Mathematics and Statistics, Nanjing University of Science and Technology, Xuanwu District, Nanjing, Jiangsu Province
**Email:** tianh@njust.edu.cn | **Phone:** 15556988958

## Education
- **Government‑sponsored Joint‑Training Program**, 2021.11‑2023.11
  Department of Mathematics and Statistics, Memorial University of Newfoundland
  *Supervisor: Xiao‑Qiang Zhao*

- **Combined Master‑Doctor Program**, 2017.09‑2024.06
  School of Mathematical Sciences, University of Science and Technology of China
  Major: Pure Mathematics, **Doctor of Philosophy (Ph.D.)**
  *Supervisor: Professor Yi Wang*

- **Undergraduate Study**, 2013.09‑2017.06
  School of Mathematics and Statistics, Northeast Normal University
  Major: Statistics, **Bachelor of Science (B.Sc.)**

## Work Experience
- **Postdoctoral Research Fellow**, 2024.07 – Present
  Department of Mathematics, School of Mathematics and Statistics, Nanjing University of Science and Technology
  Research Area: Applied Dynamical Systems
  *Co‑supervisor: Professor Zhipeng Qiu*

## Research Interests
- Reaction‑diffusion systems
- Monotone dynamical systems
- Mathematical biology

## Publications
{% include base_path %}
### Journal Articles
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

### Preprints
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

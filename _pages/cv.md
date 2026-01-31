---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<!-- {% include base_path %} -->

教育经历/Education
======
* 高中 石家庄市第二中学 省理科实验班 物化生 2020-2023
* 本科 南京航空航天大学长空学院 长空创新班（工科试验班） 2023-2027

项目经历/Project Experience
======
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}

技术栈/Skills
======
- C/C++ ROS2 开发
- 单片机及其PCB电路开发
- $\LaTeX$
- MATLAB/Python 仿真/绘图
- Web/Sever搭建和维护

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

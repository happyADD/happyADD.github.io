---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历/Education
======
* 高中 石家庄市第二中学 省理科实验班 物化生 2020-2023
* 本科 南京航空航天大学长空学院 长空创新班（工科试验班） 2023-2027

项目经历/Project Experience
======
- [三自由度稳定云台](https://happyadd.github.io/projects/云台) #嵌入式 #运动控制  
	- MPU6050读取数据并解算姿态，实时控制保持末端稳定。
- 投篮机器人
- 智能投递机器人
- 机械臂物料搬运小车
- 机械臂三子棋游戏装置
- RoboMaster2025机甲大师赛 工程机器人
- 卫惯组合导航在单片机上的部署
- 多约束的机械臂控制规划

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

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
  
Talks
======

  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

___

Education
===
* **Ph.D** in Algorithmic Monitoring of the World Wide Web, Tilburg University, 2028 (expected)
* **Master** in Cognitive Science and Artificial Intelligence, Tilburg University, 2024
* **Bachelor** in Cognitive Science and Artificial Intelligence, Tilburg University, 2019

Work experience
===
* **Independent Research Advisor**
  * European Commission, DG CNECT, 07/2023 – 01/2024
  * Providing research and advisory services regarding technical aspects of Artificial Intelligence systems, and how this may interact with the European Artificial Intelligence Act.

* **Blue Book Trainee in AI Policy**
  * European Commission, DG CNECT, 10/2022 – 02/2023
  * Responsible for various research tasks concerning the standardization of AI regulatory requirements, emerging technologies such as Brain Computer Interfaces, and sustainability of AI.

* **Junior AI Specialist**
  * Arcadis NL, 2019 - 2020
  * Duties included: Development of Computer Vision models for infrastructure tasks, such as road detection from satellite imagery, detection of animals for ecological purposes and technical solutions for municipalities.
  
Skills
===
* Python, R, SQL, C++
* Machine Learning
  * Pytorch & TensorFlow
  * LLMs, Computer Vision
* Data Science and Analysis
  * Web Scraping, Visualization, Image Processing

Publications
===
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
===
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
===
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


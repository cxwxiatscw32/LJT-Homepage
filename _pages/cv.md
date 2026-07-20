---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science** (2024 - Present)  
  Hong Kong University of Science and Technology (HKUST)

* **B.Eng.** (2020 - 2024)  
  Shanghai Jiao Tong University (SJTU)  
  Zhiyuan Honor Scholarship

Work Experience
======
* **Research Intern**, MINIMAX (February 2025 - Present)

* **Research Intern**, Tencent WXG (June 2024 - September 2024)  
  Advisor: Zifei Shan

* **Research Intern**, Shanghai AI Lab (June 2023 - December 2023)  
  Advisor: Prof. Yu Cheng

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
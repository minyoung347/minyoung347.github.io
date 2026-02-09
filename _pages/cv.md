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
* **Ph.D. in Physics**, POSTECH (Pohang University of Science and Technology), Korea, 2020
  * Advisor: Prof. Woo-Sung Jung
* **B.S. in Physics**, Kyung Hee University, Korea, 2014

Work Experience
======
* **2026.02 - Present: Associate Research Fellow**
  * Bank of Korea, Economic Research Institute
  * Micro Institution Research Team

* **2022.10 - 2026.01: Manager**
  * Bank of Korea, Digital Innovation Office
  * Digital New Technology Team

* **2020.08 - 2022.09: Associate Research Fellow**
  * Korea Exchange, Securities and Derivatives Research Center

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

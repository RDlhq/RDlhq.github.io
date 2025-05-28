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
* Ph.D in Physics, Brown University, 2029 (expected)
* B.S. in Honors Mathematics, New York University, 2023

Work experience
======
* Fall 2024: Research Assistant
  * Brown University
  * Fractional Quantum Hall Effect
  * Supervisor: Prof. Dima Feldman

* Spring 2023: Research Assistant
  * Brown University
  * Axion Cosmology
  * Supervisor: Prof. JiJi Fan

* Spring 2020: Research Assistant
  * New York University
  * Unconventional Superconductivity and Topological Insulator
  * Supervisor: Prof. Hanghui Chen

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% unless post.type == "patent" %}
      {% include archive-single-cv.html %}
    {% endunless %}
  {% endfor %}</ul>

Patents
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == "patent" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

Honors and Awards
======
  * ΦΒΚ, 2023
  * 美的冰箱校企联合创意大赛---一等奖(30,000 RMB)，最佳人气奖, 2021
  * Best Research Project, Undergraduate Research Symposium, NYU Shanghai, 2020
  * SRPP Funding (9,000 RMB $$\times 3$$), 2021,2022,2023

  



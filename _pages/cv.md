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
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == "patent" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>
  



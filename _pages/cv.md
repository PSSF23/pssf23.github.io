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
* B.S. in Bioengineering: Bioinformatics, University of California - San Diego, 2020
* M.S.E. in Biomedical Engineering, Johns Hopkins University, 2021

Work experience
======
* 01/2021 - present: Research Assistant
  * Johns Hopkins University - NeuroData Lab
  * Supervisor: Dr. Joshua Vogelstein

<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->

Projects
======
  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

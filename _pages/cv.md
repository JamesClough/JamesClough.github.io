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
* Ph.D in Physics, Imperial College London, 2017
* MSci in Theoretical Physics, Imperial College London, 2013

Work experience
======
* June 2017 - Present: Research Associate (Machine Learning)
  * King's College London
  * Motion Modelling and Analysis Group, School of Biomedical Engineering & Imaging Sciences

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

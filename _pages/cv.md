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
* Ph.D in Statistics, Seoul National University, 2012
* B.S. in Business Administration, Seoul National University, 2005

Work experience
======
* (2014-Present): Professor
  * University of Seoul

* (2023): Director
  * Urban Bidata & AI Institute, University of Seoul

* (2021-22): Vice Director
  * Office of research affairs, Univsersity of Seoul

* (2022): General Director
  * Convergence and Open Sharing System (Bigdata), Univsersity of Seoul

* (2021): General Director for Statistics and Data
  * Seoul Metropolitan Government
  

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
  
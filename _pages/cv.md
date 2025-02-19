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
* Ph.D student in Cognitive Psychology, Department of Psychology and Neuroscience, UNC Chapel Hill, 2028 (expected)
* M.S. in Cognitive Neuroscience, State Key Laboratory of Cognitive Neuroscience and Learning & IDG/McGovern Institute for Brain Research, Beijing Normal University, 2023
* B.S. in Psychology, Faculty of Psychology, Beijing Normal University, 2020
  
Skills
======
* Programming
  * Imaging analysis tools: MATLAB (including SPM, CONN, GRETNA, PTB, etc.), AFNI (linux).
  * Statistical tools: R, SPSS, Python, Mplus.
  * Experiment tools: E-Prime, Qualtrics.
  * Graphing tools: BrainNet Viewer, MRIcro, Surfice, etc.
* Imaging methods
  * MRI
  * wake/sleep EEG

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
======
  <ul>{% for post in site.conferences reversed %}
    {% include archive-single-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


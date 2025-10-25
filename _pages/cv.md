---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Please contact me for a detailed CV.

Education
======
* Ph.D in Reinforcement Learning for Flight Control, Delft University of Technology, 2026 (expected)


Work experience
======
  * Winter 2020: Phd researcher
  * Delft University of Technology
  * Duties includes: RL research and Supervision on Masters' Thesis
  * Supervisor: Dr. Erik-Jan van Kampen
  
Skills
======
* Simulation
  * PyTorch
  * TensorFlow
  * Simulink
* Algorithm
  * Deep Deterministic Policy Gradient (DDPG)
  * Incremental Heuristic Dynamic Programming (IHDP)
  * Recursive Least Square (RLS) Identification
  * Soft Actor Critic (SAC)

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
  
Service
======
* Reviewers for Journal of Aerospace Engineering, Aerospace Science and Technology, Transactions of Measurement and Control, European Control Conference (ECC)

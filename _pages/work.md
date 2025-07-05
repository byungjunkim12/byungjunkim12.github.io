---
layout: archive
title: "Work experience"
permalink: /work/
author_profile: true
# redirect_from:
#   - /resume
---

{% include base_path %}


<!-- Work experience
====== -->
* **Intern** at Samsung Semiconductor RF system team, June 2024 - Sept. 2024
  * Developed a human gesture recognition system using **mmWave FMCW SISO radar**. To overcome SISO limitations, proposed to use a range-Doppler map as input to an LSTM-based classifier, demonstrating accurate detection of **microgestures including finger tap**.
  * Supervisor: Dr. John Kim and Dr. Dongwoo Kim

* **Research Intern** at Intel Labs Wireless AI team, June 2022 - Sept. 2022
  * Applied adaptive learning algorithms for **user selection in massive MU-MIMO systems** to enhance adaptability to environmental variations. Developed **transfer learning and meta-learning algorithms** to minimize the data required for model adaptation in new environments.
  * Supervisor: Dr. Hosein Nikopour and Dr. Oner Orhan

  
Skills
======
* Python
  * Pytorch, Tensorflow
* C++
  * GNURadio

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams

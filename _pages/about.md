---
permalink: /
title: "About"
author_profile: true
---

<div id="about"></div>

I am a Ph.D. student at Columbia University, where I am advised by <a href="https://zzzzzbbzzzzz.github.io/zhengbozou.github.io/" target="_blank">Prof. Zhengbo Zou</a> in the <a href="https://intelconstructlab.github.io/" target="_blank">ICON Lab</a>. I am also affiliated with the <a href="https://cail.columbia.edu/" target="_blank">Columbia Core AI Lab (CAIL)</a>. My research lies in construction automation, human–robot interaction, and human-centered AI.

Before starting my Ph.D., I received my M.A.Sc. in Civil Engineering from the University of British Columbia, where my research focused on egocentric vision for intelligent construction. I earned my B.Sc. in Geomatics from The Hong Kong Polytechnic University, where I worked on remote sensing.

<!-- <div id="news"></div>

## News

- **July 2026** — Paper accepted at CVPR Workshop on Computer Vision for the Built World.
- **March 2026** — Presented poster at IEEE HRI 2026, Edinburgh. -->

<div id="publications"></div>

## Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



<div id="teaching"></div>

## Teaching

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

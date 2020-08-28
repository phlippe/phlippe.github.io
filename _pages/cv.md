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
* B.Eng. in Computer Science (Specialization: IT-Automotive), Cooperative State University Baden-Wuerttemberg, 2015-2018
  * Bachelor thesis (Daimler AG): Hierarchical Multi-Label Object Detection of Rare Classes for Autonomous Driving ([thesis-pdf](https://drive.google.com/open?id=1kQyc8DL1UFyp1yzreZVM3Np0L2scO5Tp))
* M.Sc. in Artificial Intelligence (GPA: 9.5), University of Amsterdam, 2018-2020
  * Master thesis ([ISIS lab](https://ivi.fnwi.uva.nl/isis/index.html)): Categorical Normalizing Flows via Continuous Transformations ([thesis-pdf](https://github.com/phlippe/master_thesis/blob/master/thesis_latex/Master_Thesis_AI_Phillip_Lippe_final.pdf), [publication](https://arxiv.org/abs/2006.09790))
* Currently persuing a Ph.D in Computer Science/Artificial Intelligence (Topic: Temporal Causality), University of Amsterdam ([QUVA lab](https://ivi.fnwi.uva.nl/quva/)), 2020-today
  * Supervisor: [Efstratios Gavves](www.egavves.com), Co-supervisor: [Taco Cohen](https://tacocohen.wordpress.com)

Work experience
======
* May 2017 - Aug 2017: Student Research Intern
  * At: Mercedes Benz Research and Development North-America (Sunnyvale, California - US)
  * Research and development of deep generative video models for predicting agent behavior in complex traffic environments

* Dec 2016 - Mar 2017, Apr 2018 - Sep 2018: Student Research Intern
  * At: Daimler AG, Image Understanding department (Stuttgart, Germany)
  * Research and development of real-time hierarchical, multi-class object detector for autonomous driving
  * Focus on handling rare classes and events

* Nov 2018 - Jun 2018: Student Research Assistant
  * At: Vrije University of Amsterdam (Amsterdam, Netherlands)
  * Research in theorem proving for high-order logic, development of a hammer for Lean to first-order logic ([project website](https://lean-forward.github.io))

* Jul 2019 - Dec 2019: Student Research Assistant
  * At: University of Amsterdam, [ILPS](https://ilps.science.uva.nl) and AIRLab (Amsterdam, Netherlands)
  * Research in task-oriented dialogue system in cooperation with Ahold Delhaize
  * Publication: Diversifying Dialogue Response Generation with Prototype Guided Paraphrasing ([arXiv](https://arxiv.org/abs/2008.03391))

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

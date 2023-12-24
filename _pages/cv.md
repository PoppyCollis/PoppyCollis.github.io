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
* PhD in Informatics, University of Sussex (ongoing)
* Gatsby Bridging Programme, Mathematics for Computational Neuroscience and Machine Learning, UCL (Summer 2023)
* MSc in Artificial Intelligence and Adaptive Systems, University of Sussex, 2021-2022
* BSc in Neuroscience with Cognitive Science, University of Sussex, 2018-2021


Experience
======

* **AI Ethics Representative** for [MetaTool](https://www.metatool-project.eu/) (Autumn 2023 - Ongoing)
  * Participated in Working Group discussions for a Portfolio of projects  ('Awareness Inside') funded by the EU EIC Pathfinder Challenge
  * Engaged with panels discussing the ethical implications of AI
  * Helped draft roadmap for Working Group activities

* **Gatsby Bridging Programme, UCL** (Summer, 2023)
  * 7 week postgraduate course in Mathematics for Computational Neuroscience and Machine Learning run by the Gatsby Computational Neuroscience Unit
  * Linear algebra, Calculus, Probability theory, ODEs, Fourier Transforms

* **Research Assistant**, Neuromorphic Computing Group, University of Sussex (Summer, 2021)
  * Helped develop benchmark dataset of dynamic vision sensor data ([Turner et al., 2022](https://dl.acm.org/doi/abs/10.1145/3517343.3517378))
  * Conducted research project to improve 'sim-to-real' generalisation during training by synthesising and injecting noise into dataset (a novel application of 'domain randomisation', see [James et al., 2017](https://proceedings.mlr.press/v78/james17a/james17a.pdf) ).
  * OpenCV, Docker, Linux command line
  * Supervisor: Professor Thomas Nowotny


* **Web developer** (December 2017 - February 2021)
  * NCompass: Web design and digital services agency
  * HTML, CSS, Google Analytics, Wordpress, Magento, Google Adwords, Git
  * Wesbite design and development, database management, marketing  

Skills
======
* Python
* Git
* Web development

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
  
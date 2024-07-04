---
layout: archive
title: "CV/Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can view my full academic CV [here (PDF)](/files/Academic_CV.pdf) and my one-page resume [here (PDF)](/files/Resume.pdf).

Education
======
* Ph.D. in Physics, Harvard University, *November 2023*
* M.A. in Physics, Harvard University, *November 2020*
* B.S. in Physics, National University of Engineering, *January 2016*

Work experience
======
* 2018 - 2023: Doctoral Researcher
  * Harvard University (Cambridge, MA) and CERN (Geneva, Switzerland)
  * Duties included: Leading Python-based data analysis, optimizing event classification in large datasets, and commissioning a muon spectrometer
  * Supervisor: Professor Melissa Franklin

* 2016: Research Assistant
  * Yale University (New Haven, CT)
  * Duties included: Analyzing data for the PROSPECT reactor antineutrino experiment
  * Supervisor: Professor Karsten Heeger

* 2015: Research Assistant
  * Peruvian Institute of Nuclear Energy (Lima, Peru)
  * Duties included: Performance of neutron activation analysis in nuclear reactor core
  * Supervisor: Professor Rubén Bruna
  
Skills
======
* Machine Learning
  * TensorFlow
  * Keras
  * XGBoost
* Data Analysis
  * Pandas
  * NumPy
  * SciPy
* Development Tools
  * Git
  * Bash
  * Regex
  * IDEs (VSCode, Emacs, Sublime Text)
* Programming Languages
  * Python
  * C/C++
  * Julia
  * HTML, CSS
* Language Proficiency
  * Spanish (Native)
  * English (Fluent)
  * French (Advanced)
  * Akkadian (Advanced)
  * Sumerian (Advanced)
  * Quechua (Basic)
  * Mandarin (Basic)
  * German (Basic)

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
* Teaching experience at Harvard University and National University of Engineering
* Contributor to open-source projects related to physics 
* Volunteer for science outreach programs and community education initiatives
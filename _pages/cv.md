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
* BEng in Computer Science and Technology, Big Data and Intelligence Track, Xidian University, 2022-2026 (Expected)
  * GPA: 4.0/4.0
  * Rank: 2/1500+ (first year), 1/476 (second year), 1/105 (third year)

Academic Research
======
* LES-Talker: Fine-Grained Emotion Editing in Linear Emotion Space (First Author, Under Review at ICCV 2025)
  * Led the full research pipeline, from problem formulation to model design, experimentation, and paper writing
  * Proposed the Linear Emotion Space (LES), a novel interpretable framework enabling fine-grained emotion editing
  * Designed LES-Talker with a universal Cross-Dimension Attention Network to align 3D model deformation with emotional control signals

* KAN-Face: Efficient Resource Usage and Precision Lip-Sync (Co-author, Accepted at ICASSP 2025)
  * Contributed to the design and refinement of a lightweight framework utilizing KANs
  * Participated in the development and review of the Lip-Sync Enhancement Module
  * Actively involved in technical discussions and rebuttal preparation

* EmoSpeaker: Emotion-Controlled Talking Face Generation (Co-author, Under Review at IEEE TMM)
  * Assisted in a one-shot framework capable of fine-grained emotional control and precise lip synchronization
  * Contributed to the design of an audio decoupling mechanism guided by facial attributes
  * Actively involved in paper revision and rebuttal writing

Projects Experience
======
* Public Transportation Management System - Android App Development (Team Leader)
  * Led a team in developing a full-stack Android application
  * Designed a low-redundancy relational database tailored to project needs
  * Proposed a technical framework for lightweight management systems

Awards
======
* Champion — Task 3 in AAAI2024 Workshop on AI for Digital Human, BDIV Lab
  * Achieved top scores across four evaluation metrics in both video- and audio-based tracks
  * Modified SadTalker by removing PoseNet and redesigning ExpNet for direct 70D 3DMM prediction
  * Enhanced realism via innovative blinking and lip-sync strategies using OpenFace and Hubert

Skills
======
* Developer Tools: Python, Pytorch, C, Assembly Language, MySQL, C++, Java
* Languages: English (TOEFL), Chinese (native tongue)

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

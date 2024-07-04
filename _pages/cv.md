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
<ul>
    <li>
        <div style="display: flex; align-items: center;">
            <span>Ph.D in Computer Science, Technische Universität Berlin, 2025 (expected)</span>
            <img src="/images/tu_berlin.png" alt="TU Berlin" style="margin-left: auto; width: 250px; height: auto;"/>
        </div>
    </li>
    <li>
        <div style="display: flex; align-items: center;">
            <span>M.Sc. in Computer Science, Universität Bonn, 2022</span>
            <img src="/images/uni_bonn.png" alt="University of Bonn" style="margin-left: auto; width: 250px; height: auto;"/>
        </div>
    </li>
    <li>
        <div style="display: flex; align-items: center;">
            <span>B.Sc. in Computer Science, German University in Cairo, 2020</span>
            <img src="/images/guc.png" alt="GUC" style="margin-left: auto; width: 250px; height: auto;"/>
        </div>
    </li>
</ul>


Work experience
======
* Sept 2022 - Present : Machine Learning Researcher
  * Continental AG
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Nov 2020 - July 2022: Research Assistant
  * Fraunhofer FKIE
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Professional Service
======
* Reviewer
  * Conferences:  [British Machine Vision Conference (BMVC) 2024](https://bmvc2024.org/), [IEEE Intelligent Vehicles Symposium (IV) 2024](https://ieee-iv.org/2024/aes-and-revewers/), [IEEE Intelligent Transportation Systems Conference (ITSC) 2024](https://ieee-itsc.org/2024/) 

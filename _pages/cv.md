---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
show_publications: false
show_talks: false
show_teaching: false
---

{% include base_path %}

### Full-Stack Web Applications Engineer, Project Manager, BS in Industrial Technology Management

Strategic thinker, creative problem solver and process streamliner, AI-, coding- and UX-obsessed technologist, with extensive experience in programming, design and operations, that enjoys forming and leading effective teams, and is passionate about staying current on the latest technologies and best-practices.

Interested in exciting challenges where the technologies of today and tomorrow can be harnessed to contribute to a better future for us all.

## Education

* B.S. – Industrial Technology Management, Arizona State University – 2000
  - Concentration in Web and Graphic Design, Information Technology and Applied Engineering, with an emphasis in Mechanical Engineering and IT Project Management

* Certifications – University of Arizona, Tucson, AZ – 2020-2023
  - Secure System Administration and Developer Certification (SADC)
  - Information Security Awareness Certifications

* Six Sigma Green Belt – Motorola University, Tempe, AZ – 2008
  * Green Belt Project: NPI Material Reservation Process

## Work Experience

<!-- {{ site.data.ui-text[site.locale].current | default: "Current" }} -->

<section class="experience">
{% for post in site.experience reversed %}
  {% include cv-experience.html type="experience" %}
{% endfor %}
</section>
  
## Skills
* Software Development
* Project Management
* Web Applications
* TypeScript
* Angular

**Languages & Technologies:**  
ES6+, TypeScript, Angular, Ionic, Vue, Git, GraphQL, C#.NET, HTML5, CSS3, Python, PHP, Swift, AWS Serverless Architectures

**Applications:**  
Visual Studio Code, X-Code, Adobe Photoshop, Illustrator, Acrobat, Blender

{% if show_publications %}
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}

{% if show_talks %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endif %}

  
{% if show_teaching %}
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}


## Service and leadership

* Currently signed in to 9 different slack teams

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

### Full-Stack Web &amp; AI Application Developer, Project Manager, BS in Industrial Technology Management

Accomplished and innovative technology leader with decades of experience in full-stack web development, project management, and team leadership. Expert in designing and implementing scalable, secure, and user-friendly applications using cutting-edge technologies such as TypeScript, Vue, Angular, AWS, AI and blockchain. Proven track record of streamlining processes, enhancing operational efficiency, and delivering high-quality solutions on time and within budget.

Skilled in leading cross-functional teams, fostering a collaborative and innovative environment, and mentoring junior developers. Passionate about leveraging the latest technologies and best practices to drive impactful projects that contribute to a better future. Seeking new challenges where I can apply my expertise to create meaningful and transformative technological solutions.

## Education

* B.S. – Industrial Technology Management, Arizona State University – 2000
  - Concentration in Web and Graphic Design, Information Technology and Applied Engineering, with an emphasis in Mechanical Engineering and IT Program Management

* Certifications – University of Arizona, Tucson, AZ – 2020-2024
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
* Full-Stack Software Development
* Project Management
* Web Applications
* TypeScript
* Angular

**Languages & Technologies:**  
ES6+, TypeScript, Angular, Ionic, Vue, React, Redux, GraphQL, C#.NET, Python, PHP, Swift, HTML5, CSS3, Git, AWS Serverless Architectures, Docker

**Applications:**  
Visual Studio Code, X-Code, Jupyter, Anaconda, Adobe Photoshop, Illustrator, Acrobat, Blender

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

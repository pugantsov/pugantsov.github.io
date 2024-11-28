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
**Doctor of Philosophy (PhD), Computing Science**, University of Glasgow<br>
<small>Dec 2019 - Jun 2024</small>

**Master in Science (MSci), Software Engineering**, University of Glasgow<br>
<small>Sep 2014 - Jun 2019</small>

Work experience
======
**Postdoctoral Researcher**, University of Padua<br>
<small>Oct 2024 - present</small>

**Teaching Assistant**, University of Glasgow<br>
<small>Oct 2017 - May 2024</small>

**Automation Engineer**, Barclays<br>
<small>Aug 2019 - Dec 2019</small>

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

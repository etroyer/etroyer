---
layout: page
title: About
permalink: /resume
---

<h2>Experience</h2>
{% for experience in site.data.experiences %}
  <p class="title"><strong>{{ experience.role }}</strong> {{ experience.acquired }}</p>
  <p>{{ experience.date }}</p>
  <p>{{ experience.highlights }}</p>
{% endfor %}

<h2>Education</h2>
<p class="title"><strong>Purdue University</strong></p>
<p>BS in Computer Graphics Technology, AA in Art & Design</p>

<h2>Skills</h2>
<p>Sketch, Principle, Invision Studio, HTML/CSS, React, Adobe.</p>

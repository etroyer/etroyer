---
layout: page
title: About
permalink: /resume
---

<h2>Experience</h2>
{% for experience in site.data.experiences %}
  <h3>{{ experience.role }}</h3>
  <h4>{{ experience.date }}</h4>
  <p>{{ experience.highlights }}</p>
{% endfor %}

<h2>Education</h2>
<h2>Skills</h2>

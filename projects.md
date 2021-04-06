---
layout: page
permalink: /projects
permalink_name: /projects
title: Projects
---

{% for item in site.projects %}
<h2><a href = "{{ item.url }}" >{{ item.title }}</a></h2>
<p>{{ item.description }}</p>

{% endfor %}
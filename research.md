---
layout: page
permalink: /reserach
permalink_name: /research
title: Research
---

{% for item in site.research %}
<h2><a href = "{{ item.url }}" >{{ item.title }}</a></h2>
<p>{{ item.description }}</p>

{% endfor %}
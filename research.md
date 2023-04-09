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

## My research is supported by the following:

{:style="text-align:center;"}
![](../assets/aro-seal-300x300-1.png) ![](../assets/512px-DARPA-logo-300x165-1.png)

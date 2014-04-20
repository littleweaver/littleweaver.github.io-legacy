---
layout: default
title: Little Weaver Open Source
---

<strong class="co-name">Little Weaver Web Collective</strong> is a cooperative web development group. Our work is built on the work of others; we give back by providing high-quality, reusable, open-source code as a resource for the development of a better internet.

{% for project in site.data.projects %}
###[{{ project.name }}](http://github.com/littleweaver/{{ project.github }})
{{ project.description }}

{% endfor %}

---
layout: page
title: About
permalink: /about/
---

Previously founded Elto.com which was acquired by GoDaddy.com in 2015.

Passionate about: remote teams, software excellenge, lean startup, agile development

Technologies I've worked with:
{% for tech in site.technologies %}
  * {{ tech }}
{% endfor %}

Get in [contact with me][email]

I am currently in: **{{site.current_location}}**

[email]: mailto:{{site.email}}
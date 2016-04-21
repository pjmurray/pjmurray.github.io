---
layout: page
title: About
permalink: /about/
order: 1
---

I'm customer centric full-stack software engineer. Most notably, I founded Elto.com which was acquired by GoDaddy.com in 2015.

I'm most passionate about: remote teams, software excellence, lean startups, agile development.


# Employment

* 2012-2015: Elto.com
* 2012: Inspire 9
* 2011-2012: ThoughtWorks
* 2010 - 2011: NRW
* 2005 - 2009: University of Cantebury


# Technologies

{% for tech in site.technologies %}
  * {{ tech }}{% endfor %}

# Personal

I was born in South Africa,
grew up and studied in New Zealand, worked in various parts on Australia,
spent 2 years in San Francisco, and am now in London.

# Hobbies + Interests

{{ site.interests | join: ', ' }}
---
layout: default
title: Writing
permalink: /blog/
order: 2
---

This is a summary of my writing:

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <h1>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h1>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
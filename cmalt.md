---
layout: page
title: "CMALT Portfolio"
permalink: /cmalt/
---

Welcome to my CMALT portfolio.

## CMALT Criteria and Evidence

Below are the entries I've written for each of the core CMALT areas:

<ul>
  {% assign sorted_cmalt = site.cmalt | sort: 'title' %}
  {% for entry in sorted_cmalt %}
    <li><a href="{{ entry.url }}">{{ entry.title }}</a></li>
  {% endfor %}
</ul>
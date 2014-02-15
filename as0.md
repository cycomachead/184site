---
layout: default
title: Assignment 0
permalink: as0/index.html
---

# Assignment 0

Here's a bunch of screenshots. Some of these were bugs that turned out to look interesting.

{% assign arr = "1|2|3|4|5|6" | split: "|" %}
{% for item in arr %}
![{{ item }}.png]({{ item }}.png)
{% endfor %}
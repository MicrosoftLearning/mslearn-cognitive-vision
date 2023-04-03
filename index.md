---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Cognitive Vision Exercises


{% assign labs = site.pages | where_exp:"page", "page.url contains '/instructions'" %}
{% for activity in labs  %}
- [{{ activity.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}


---
layout: default
title: Home
---

# Hi — I'm Anand

Welcome to my portfolio. I build products and developer tools. Below are recent projects and ways to get in touch.

## Recent projects

- [Sample Project — Portfolio Starter](/projects/)
---
layout: home
title: Home
---


Welcome — I'm Anand. I build products and developer-facing tools.

<!-- The Minimal Mistakes `home` layout will render configured front matter and collections. -->

## Recent projects

{% for project in site.projects limit:3 %}
- [{{ project.title }}]({{ project.url }}) — {{ project.excerpt }}
{% endfor %}


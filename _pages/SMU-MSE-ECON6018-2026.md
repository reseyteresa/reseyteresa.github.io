---
title: "SMU MSE ECON6018 Tutorials 2026"
permalink: /tutorials/smu-mse-econ6018-tutorials-2026/
layout: single
---

## Tutorials

{% assign tutorials = site.teaching | where: "course", "SMU MSE ECON6018 Tutorials 2026" | sort: "date" %}

<ul>
{% for t in tutorials %}
  <li>
    <a href="{{ t.url }}">{{ t.title }}</a> ({{ t.date | date: "%d %b %Y" }})
  </li>
{% endfor %}
</ul>
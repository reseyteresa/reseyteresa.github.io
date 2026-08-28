---
title: "SIM MICROECONOMICS FOUNDATION FALL 2027"
permalink: /tutorials/sim-econ181-foundation-macroeconomics-2027/
layout: single
---

## Tutorials

{% assign tutorials = site.teaching | where: "course", "SSIM MICROECONOMICS FOUNDATION FALL 2027" | sort: "date" %}

<ul>
{% for t in tutorials %}
  <li>
    <a href="{{ t.url }}">{{ t.title }}</a> ({{ t.date | date: "%d %b %Y" }})
  </li>
{% endfor %}
</ul>
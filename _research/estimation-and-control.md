---
title: "State estimation and control"
collection: research
permalink: /research/estimation-and-control
---

## Relevant publications

<ul>
{% for post in site.publications reversed %}
  {% for tag in post.tags %}
    {% if tag == 'state-estimation' or tag == 'real-time-control' %}
      <li class="publication__li"><a href="{{post.permalink}}">{{post.citation}}</a></li>
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
</ul>

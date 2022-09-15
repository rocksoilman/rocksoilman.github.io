---
title: "Coupled Infrastructure System Modeling"
collection: research
permalink: /research/coupled-infrastructure-modeling
---

## Relevant publications

<ul>
{% for post in site.publications reversed %}
  {% for tag in post.tags %}
    {% if tag == 'coupled-infrastructure-modeling' %}
      <li class="publication__li"><a href="{{post.permalink}}">{{post.citation}}</a></li>
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
</ul>

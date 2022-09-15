---
title: "Wireless sensor networks for water infrastructure"
collection: research
permalink: /research/wireless-sensor-networks
---

## Relevant publications

<ul>
{% for post in site.publications reversed %}
  {% for tag in post.tags %}
    {% if tag == 'wsns' %}
      <li class="publication__li"><a href="{{post.permalink}}">{{post.citation}}</a></li>
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
</ul>

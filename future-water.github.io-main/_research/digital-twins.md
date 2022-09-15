---
title: "Digital twin models of water infrastructure"
collection: research
permalink: /research/digital-twins
---

## Relevant publications

<ul>
{% for post in site.publications reversed %}
  {% for tag in post.tags %}
    {% if tag == 'digital-twins'%}
      <li class="publication__li"><a href="{{post.permalink}}">{{post.citation}}</a></li>
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
</ul>

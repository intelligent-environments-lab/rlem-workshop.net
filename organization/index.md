---
layout: default
title: Organization
---

<h1 class="display-5 mb-4">
    {{ page.title }}
</h1>

{% for org in site.data.organization %}
<h2 class="organization">
  {{ org.role }}
  {% if org.chair%}
    {% if org.member.size > 1 %}
      Co-Chairs
    {% else %}
      Chair
    {% endif %}
  {% endif %}
</h2>
<ul class="organization">
  {% for mbr in org.member %}
  <li>
    <a href="{{ mbr.url }}">
      {{ mbr.name }}
    </a>
    ({{ mbr.affiliation }})
  </li>
  {% endfor %}
</ul>
{% endfor %}
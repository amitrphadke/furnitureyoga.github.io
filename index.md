---
layout: home
# articles:
#   excerpt_type: html
aside:
  toc: true
---
{% for asana in site.asanas %}
  <h2>
    <a href="{{ asana.url }}">
      {{ asana.name }} - {{ asana.category }}
    </a>
  </h2>
  <!-- <p>{{ asana.content | markdownify }}</p> -->
{% endfor %}


## Publications

{% for link in site.data.publications.main %}

- **{{ link.title }}**  
  {{ link.authors }}  
  *{{ link.conference }}*  
  {% if link.notes %}{{ link.notes }}{% endif %}
  {% if link.pdf %} [PDF]({{ link.pdf }}){% endif %}
  {% if link.code %} [Code]({{ link.code }}){% endif %}
  {% if link.page %} [Project Page]({{ link.page }}){% endif %}

{% endfor %}

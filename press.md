<ul>
{% for page in site.pages %}
  {% if page.categories contains 'press' %}
    <li>
      <a href="#"><p>Page</p></a>
    </li>
  {% endif %}
{% endfor %}
</ul>

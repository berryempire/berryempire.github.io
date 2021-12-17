<ul>
{% for page in site.pages %}
  {% if page.categories contains 'press' %}
    <li>
      <a href="{{page.url}}"><p>Page</p></a>
    </li>
  {% endif %}
{% endfor %}
</ul>

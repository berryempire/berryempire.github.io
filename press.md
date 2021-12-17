<ul>
{% for page in site.pages %}
  {% if page.categories contains 'press' %}
    <li>
      <a href="{{page.url}}"><p>{{page.title}}</p></a>
    </li>
  {% endif %}
{% endfor %}
</ul>

<ul>
{% for page in site.pages %}
  <li>
      <a href="{{page.url}}"><p>{{page.title}}</p></a>
  </li>
{% endfor %}
</ul>

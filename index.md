This is Lumostor's first HTML page on github.io.<BR>
Mainly this is a test.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


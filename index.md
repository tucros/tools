## Chan's Tools

Hello World 

[elo_sim.html](elo_sim.html)

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

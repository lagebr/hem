<!--- deklarera att teckenkodning är utf-8 -->
<meta http-equiv='Content-Type' content='text/html; charset=utf-8'/>

# Index
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

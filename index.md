# Welcome to my blog

I'm glad you are here. I plan to talk about ... nothing by now actually, this is lorem ipsum qwerty uiop
<ul>
  {% for post in site.posts %}
    <li>
      <a href="/RANDOMTITLE{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

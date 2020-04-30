# contributor

{% for post in site.post %}

  <h2>{{ post.user }}</h2>
  <h2>{{ post.name }}</h2>
  <p>{{ post.content | markdownify }}</p>
{% endfor %}


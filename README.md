# contributor

{% for post in site.posts %}

  <h2>{{ post.user }}</h2>
  <h2>{{ post.name }}</h2>
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}


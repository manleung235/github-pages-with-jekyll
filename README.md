# contributor

{% for post1 in site.posts %}
  <h2>{{ post.user }}</h2>
  
  <p>{{ post.name }}</p>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}



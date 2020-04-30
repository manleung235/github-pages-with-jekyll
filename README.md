# contributor

{% for post in site.collections.posts %}
  <h2>{{ post.user }}</h2>
  
  <p>{{ post.name }}</p>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}



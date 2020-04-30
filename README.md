# contributor

{% for post in collection.posts %}
  <p>{{ post.user }}</p>
  
  <p>{{ post.name }}</p>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}


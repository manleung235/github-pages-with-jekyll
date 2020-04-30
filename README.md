# contributor

{% for post in collections.posts %}
  <p>{{ post.user }}</p>
  
  <p>{{ post.name }}</p>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}



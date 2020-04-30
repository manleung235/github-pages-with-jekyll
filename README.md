# contributor

{% for post in collections.posts %}
  <li>{{ post.data.user }}</li>
  
  <li>{{ post.name }}</li>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}



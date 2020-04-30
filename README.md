# contributor

{% for post in collections.post %}
  <li>{{ post.data.user }}</li>
  
  <li>{{ post.name }}</li>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}



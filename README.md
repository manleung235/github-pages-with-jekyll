# contributor

{% for post in site.posts %}
  <p>{{ post.user }}</p>
  
  <p>{{ post.name }}</p>
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}


# contributor

{% for post in site.posts %}

  {{ post.user }}
  
  {{ post.name }}
  
  <p>{{ post.content | markdownify }}</p>
  
{% endfor %}


# contributor
{% for stu in site.stu %}
  <h2>{{ stu.user }}-{{ stu.name }}</h2>
 - <p>{{ stu.content | markdownify }}</p>
{% endfor %}



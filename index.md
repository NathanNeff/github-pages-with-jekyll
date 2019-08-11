# Welcome to my blog

I'm glad you are here. I plan to talk about ...

Blogging and Wikis usin GitHub

{% for post in site.posts %}
{{ post.title }}
{{ post.date | date_to_long_string }}

{{ post.excerpt }}

Read Post
{% endfor %} 

---

layout: page
permalink: "/heart"
---

## Heart

{% for post in site.categories.heart %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
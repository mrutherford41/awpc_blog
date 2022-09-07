---

layout: page
permalink: "/heart"
---

## Heart

a place for expressing matters of the heart

{% for post in site.categories.heart %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
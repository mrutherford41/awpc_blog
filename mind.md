---

layout: page
permalink: "/mind"
---

## Mind

a place for sharing knowledge including programming works in progress, random tidbits of knowledge, etc.

{% for post in site.categories.mind %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
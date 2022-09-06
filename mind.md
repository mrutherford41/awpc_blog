---

layout: page
permalink: "/mind"
---

## Mind

{% for post in site.categories.mind %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
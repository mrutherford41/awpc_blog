---

layout: page
permalink: "/moodring"
---

## Moodring

a place for anything that fits my current mood (music, movies, books, etc.)

{% for post in site.categories.moodring %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
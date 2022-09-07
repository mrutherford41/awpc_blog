---

layout: page
permalink: "/moodring"
---

## Moodring

a place for anything that fits my current mood (music, movies, books, etc.)

<br>
#### On Repeat:
<iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/48pL4zB6KXWPvd7Ln33ENy?utm_source=generator" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>


{% for post in site.categories.moodring %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
---
permalink: /news/
title: "News"
author_profile: true
---

{% for post in site.posts %}

## {{ post.title }}

**{{ post.date | date: "%B %-d, %Y" }}**  
*{{ post.author }}*

{% if post.image %}
<img src="{{ post.image }}" alt="{{ post.title }}" style="max-width: 500px; margin: 10px 0 15px 0;">
{% endif %}

{{ post.excerpt }}

[Read more]({{ post.url }})

---

{% endfor %}

---
layout: default
title: "Welcome to My Data Visualization Blog"
---

# {{ site.title }}

Hi! I’m Anveksha, and this site showcases my visualization work from **IS445 (Data Visualization)**.  
Below you’ll find all my projects and assignments:

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
*Published on {{ post.date | date: "%B %d, %Y" }}*
<br>
{{ post.excerpt }}
---
{% endfor %}


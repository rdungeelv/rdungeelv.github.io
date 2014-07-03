---
layout: page
title: Archive
--- 

<p class="message">
This will one day be an archive of posts. For now, it's this.
</p>

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

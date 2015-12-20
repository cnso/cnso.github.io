---
layout: default
---

#Posts
{% for post in site.posts %}
####{{ post.date | date_to_string }}
[{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}
subscribe [via RSS]({{ "/feed.xml" | prepend: site.baseurl }})

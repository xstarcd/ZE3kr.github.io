---
layout: page
title: Archive
notpost: yes
permalink: /archive.html
redirect_from:
  - /archive/
---

<ul>
{% for post in site.posts %}
<li>
<a class="post-date" href="{{ post.url | prepend: site.github.url }}" title=""><b class="gray">{{ post.date | date: "%b %d %Y" }}</b>
<span>{{ post.title }}</span></a>
</li>
{% endfor %}
</ul>

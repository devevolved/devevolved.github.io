---
layout: page
title: Archives
banner: true
---

<div class="archives" itemscope itemtype="http://schema.org/Blog">
{% for post in site.posts reverse %}
{% if post.layout == 'post' %}
	{% include archive_post.html %}
{% endif %}
{% endfor %}
  </ul>
</div>


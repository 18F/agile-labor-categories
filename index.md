---
title: Types of People You Need for the BPA
layout: template/page
---

<ul>
{% for position in site.positions %}
	<li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

---
title: Labor Category Descriptions for Agile Procurements
layout: template/page
---

<ul>
{% for position in site.positions %}
	<li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

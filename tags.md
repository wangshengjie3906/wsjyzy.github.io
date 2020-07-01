---
layout: page
title: 标签列表 
---

<div class="page-content wc-container">
	<div class="post">
		<h1>标签列表</h1>  
		<ul>
			{% for tag in site.tags %}
			<li><a href="{{ '/tag/' | append:tag[0] | relative_url }}">{{ tag[0] }}</a></li>
			{% endfor %}
		</ul>
	</div>
</div>
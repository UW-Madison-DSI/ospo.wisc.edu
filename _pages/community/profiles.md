---
title: Faces of Open Source | Open Source Program Office
layout: default
permalink: /community/profiles
---

<h1 class="page-title uw-mini-bar">Faces of Open Source</h1>
<p class="page-description">Below are some faces of open source at the Universty of Wisconsin-Madison. </p>

<div class="profiles row m-md-auto">
	{% for page in site.pages %}
	{% if page.layout == 'profile' %}
	<div class="icon col-xs-12 col-sm-6 col-md-4">
		<a href="{{ page.permalink }}">
			<div class="headshot" style="background-image:url(../../images/profiles/{{ page.headshot }})"></div>
		</a>
		<h3>{{ page.fullname }} </h3>
	</div>
	{% endif %}
	{% endfor %}
</div>
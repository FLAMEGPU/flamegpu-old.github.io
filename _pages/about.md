---
permalink: /about/
---
<div class="about-page">
	<div class="about">
		<p>FLAME GPU is a high performance Graphics Processing Unit (GPU) extension to the FLAME framework. It provides a mapping between a formal agent specifications with C based scripting and optimised CUDA code. This includes a number of key ABM building blocks such as multiple agent types, agent communication and birth and death allocation. The advantages of our contribution are three fold. Firstly Agent Based (AB) modellers are able to focus on specifying agent behaviour and run simulations without explicit understanding of CUDA programming or GPU optimisation strategies. Secondly simulation performance is significantly increased in comparison with desktop CPU alternatives. This allows simulation of far larger model sizes with high performance at a fraction of the cost of grid based alternatives. Finally massive agent populations can be visualised in real time as agent data is already located on the GPU hardware.</p>

		<div class="video">
			<h4>FLAME GPU Agent Based Simulation Demos</h4>
			{% include video id="u1LBLSlMUFo" provider="youtube" %}
		</div>

		<div class="video">
			<h4>FLAME GPU Pedestrian Crowd Simulation Demo</h4>
			{% include video id="LSoDfG-p6Ik" provider="youtube" %}
		</div>
	</div>
<!--<div class="news">
	<h4>News and Announcements</h4>
{% assign cposts = 0 %}
{% assign mposts = 0 %}
{% for post in site.posts %}
	{% if post.categories contains 'news' %}
		{% if cposts<5 %}
			<a class="newslink" href="{{ post.url }}">{{ post.title }}</a>
			<div class="link_content">{{post.content}}</div>
			<p>Posted {{post.date}} by {{post.author}}</p>
			{% assign cposts = cposts | plus:1 %}
			{% assign mposts = mposts | plus:1 %}
		{%else%}
			{% assign mposts = mposts | plus:1 %}
		{% endif %}		
	{%endif%}
{% endfor %}
<p>{%if cposts>0 %}Showing posts: <b>1 - {{cposts}}</b> of <b>{{mposts}}</b>. <a href="/newsfeed">View more >></a>{% else %}Error: No posts found{%endif%}</p>
</div>-->
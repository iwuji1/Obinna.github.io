---
layout: default
title: Data Stories
permalink: /data_stories
---
Data Stories
{: .page-header-2}

<p>For most of my professional life(Which is not very long at this point), I have been a data analyst. I like how data and visuals can help better understandings of complex issues whether that relates to revenue or migration patterns. I want to create more data stories to illuminate things I find interesting so here is a catalogue of my work thus far!</p>
{% for post in site.posts%}
{% if post.categories contains "Data" %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<p>{{ post.excerpt }}</p>
{% endif %}
{% endfor %}

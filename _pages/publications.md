---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} 

# Publications In Preparation

Click the links below for current drafts of publications that are in preparation.  

{% include base_path %}

{% for post in site.inprep_publications reversed %}
  {% include archive-single.html %}
{% endfor %}  


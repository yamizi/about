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

#https://api.semanticscholar.org/graph/v1/author/2399971?fields=papers.authors,papers.title,papers.abstract,papers.venue,papers.year
#https://api.semanticscholar.org/graph/v1/author/2399971/papers?fields=url,title,year,venue,abstract,authors


---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

I currently have no officially published papers, but I hope that I will soon!

{% for post in site.papers reversed %}
  {% include archive-single.html %}
{% endfor %}

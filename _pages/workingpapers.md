---
layout: archive
title: "Working papers and reports"
permalink: /workingpaper/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.workingpaper reversed %}
  {% include archive-single.html %}
{% endfor %}

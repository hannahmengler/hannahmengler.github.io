---
layout: archive
title: "Special Projects"
permalink: /projects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Online Sales Optimization Task Force

More details to come.

## Knopf Doubleday Publishing Group Internship Program

More details to come.

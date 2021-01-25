---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## _Friends on the Internet_

My pandemic project! I’m working on a series of essays, delivered weekly via Substack, recapping each episode of the first season of Catfish: The TV Show. In this newsletter, I explore themes of loneliness, conflict, and connection in the digital age - themes that, after the events of 2020, interest me all the more. Digressions include Barbra Streisand movies, pop punk music, true crime, and more. Subscribe [here](https://friendsontheinternet.substack.com/). 
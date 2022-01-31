---
layout: archive
permalink: nlp
title: "NLP"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.nlp %}
{% for post in posts %}
  {% include custom-archive-single.html type=entries_layout %}
{% endfor %}
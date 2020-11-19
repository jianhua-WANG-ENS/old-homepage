---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

{% include base_path %}

{% for post in site.Research reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

<!-- 加reversed进行反序 -->
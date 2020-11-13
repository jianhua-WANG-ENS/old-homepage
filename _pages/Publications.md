---
layout: archive
title: "Publications"
permalink: /Publications/
author_profile: true
---

{% include base_path %}

{% for post in site.Publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- 加reversed进行反序 -->
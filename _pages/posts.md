---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: false
---

{% include base_path %}

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}

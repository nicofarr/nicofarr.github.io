---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  A automatically update version can be found on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

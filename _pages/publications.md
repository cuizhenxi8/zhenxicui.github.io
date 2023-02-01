---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.orcid %}
<!--   You can also find my articles on <u><a href="{{author.orcid}}">my orcid profile</a>.</u> -->
You can also find my articles on [my orcid profile](https://orcid.org/0000-0003-3508-0939).

{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

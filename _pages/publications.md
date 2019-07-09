---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### <u>Item-specific delay activity demonstrates concurrent storage of multiple active neural representations</u>

Sutterer DW, Foster JJ, Adam KCS, Vogel EK, Awh E (2019). *PLOS Biology*, 17: e3000239. 

PDF | Code and Data









{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

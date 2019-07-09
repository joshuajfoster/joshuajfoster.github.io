---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



## Alpha-band oscillations track the retrieval of precise spatial representations from long-term memory

Sutterer DW, Foster JJ, Serences JT, Vogel EK, Awh E (in press). *Journal of Neurophysiology*.

PDF \| Data and Code

## Item-specific delay activity demonstrates concurrent storage of multiple active neural representations

Sutterer DW\*, Foster JJ*, Adam KCS, Vogel EK, Awh E (2019). *PLOS Biology*, 17: e3000239. 

PDF \| [Data and Code](https://osf.io/47cmn/)

## The role of alpha oscillations in spatial attention: Limited evidence for a suppression account

Foster JJ and Awh E (2019) *Current Opinion in Psychology*, 29, 34-40.

PDF







{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

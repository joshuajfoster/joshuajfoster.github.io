---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



## Alpha-band oscillations track the retrieval of precise spatial representations from long-term memory

Sutterer DW, Foster JJ, Serences JT, Vogel EK, Awh E (in press). *Journal of Neurophysiology*. PDF

## Item-specific delay activity demonstrates concurrent storage of multiple active neural representations

Sutterer DW\*, Foster JJ\*, Adam KCS, Vogel EK, Awh E (2019). *PLOS Biology*, 17: e3000239. PDF \| [Data and Code](https://osf.io/47cmn/)

## The role of alpha oscillations in spatial attention: Limited evidence for a suppression account

Foster JJ and Awh E (2019) *Current Opinion in Psychology*, 29, 34-40. PDF

## Inverted encoding models assay population-level stimulus representations, not single-unit neural tuning

Sprague TC, Adam KCS, Foster JJ, Rahmati M, Sutterer DW, Vo VA (2018). *eNeuro*, 5(3). PDF

## Spatially selective alpha oscillations reveal moment-by-moment trade-offs between working memory and attention

D van Moorselaar, Foster JJ, Sutterer DW, Theeuwes J, Olivers CNL, Awh E (2018). *Journal of Cognitive Neuroscience*, 30(2), 256-266. PDF



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

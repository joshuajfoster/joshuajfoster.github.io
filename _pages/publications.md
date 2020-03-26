---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\* authors made equal contributions

[**Covert spatial attention speeds target individuation**](https://www.jneurosci.org/content/40/13/2717)<br/>Foster JJ, Bsales EM, Awh E (2020). *Journal of Neuroscience*, 40(13), 2717-2726.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster et al_2020_JNeurosci.pdf) \| [data and code](https://osf.io/a9mvb/)

## Alpha-band oscillations track the retrieval of precision spatial representations from long-term memory

Sutterer DW, Foster JJ, Serences JT, Vogel EK, Awh E (2019). *Journal of Neurophysiology*, 122(2), 539-551.<br/> [PDF](https://www.biorxiv.org/content/biorxiv/early/2018/02/18/207860.full.pdf)

## Item-specific delay activity demonstrates concurrent storage of multiple active neural representations

Sutterer DW\*, Foster JJ\*, Adam KCS, Vogel EK, Awh E (2019). *PLOS Biology*, 17(4): e3000239.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Sutterer Foster et al_2019_PLOS Biology.pdf) \| [Data and Code](https://osf.io/47cmn/)

## The role of alpha oscillations in spatial attention: Limited evidence for a suppression account

Foster JJ and Awh E (2019) *Current Opinion in Psychology*, 29, 34-40.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Foster & Awh_2019_CurrOpinionPsych.pdf)

## Inverted encoding models assay population-level stimulus representations, not single-unit neural tuning

Sprague TC, Adam KCS, Foster JJ, Rahmati M, Sutterer DW, Vo VA (2018). *eNeuro*, 5(3).<br/>[PDF](http://joshuajfoster.github.io/files/papers/Sprague et al_2018_eNeuro.pdf)

## Spatially selective alpha oscillations reveal moment-by-moment trade-offs between working memory and attention

D van Moorselaar, Foster JJ, Sutterer DW, Theeuwes J, Olivers CNL, Awh E (2018). *Journal of Cognitive Neuroscience*, 30(2), 256-266.<br/>[PDF](http://joshuajfoster.github.io/files/papers/van Moorselaar et al_2018_JoCN.pdf) \| [Data and Code](https://osf.io/56rzh/)

## Alpha-band activity reveals spontaneous representations of spatial position in visual working memory

Foster JJ, Bsales EM, Jaffe RJ, Awh E (2017). *Current Biology*, 27(20), 3216-3223.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Foster et al_2017_CurrBio.pdf) \| [Data and Code](https://osf.io/vw4uc/) \| [Research Highlight in Nature Neuroscience](https://www.nature.com/articles/nrn.2017.143?WT.ec_id=NRN-201712&spMailingID=55372847&spUserID=NzM5Njg0NjU0NzUS1&spJobID=1282840712&spReportId=MTI4Mjg0MDcxMgS2)

## Alpha-band oscillations enable spatially and temporally resolved tracking of covert spatial attention

Foster JJ, Sutterer DW, Serences, JT, Vogel EK, Awh E (2017). *Psychological Science*, 28(7), 929-941.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Foster et al_2017_PsychScience.pdf) \| [Data and Code](https://osf.io/29nxv/)

## The topography of alpha-band activity tracks the content of spatial working memory

Foster JJ, Sutterer, DW, Serences JT, Vogel EK, Awh E (2016). *Journal of Neurophysiology*, 115(1), 168-177<br/>[PDF](http://joshuajfoster.github.io/files/papers/Foster et al_2016_JNeurophysiol.pdf) \| [Data and Code](https://osf.io/bwzfj/)

## Frontal and parietal EEG asymmetries interact to predict attentional bias to threat

Grimshaw GM, Foster JJ, Corballis PM (2014). *Brain and Cognition*, 90, 76-86.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Grimshaw et al_2014_Brain&Cognition.pdf)

## Is feature-based attention always spatially global during visual search?

Foster JJ\* and Adam KCS\* (2014). *Journal of Neuroscience*, 34 (26), 8662-8664.<br/>[PDF](http://joshuajfoster.github.io/files/papers/Foster & Adam_2014_JNeurosci.pdf)





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

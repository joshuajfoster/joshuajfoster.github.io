---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\* indicates that authors made equal contributions

## Articles

**Covert attention increases the gain of stimulus-evoked population codes**<br/>Foster JJ, Thyer W, Wennberg JW, Awh E (in press). *Journal of Neuroscience*.<br/>[preprint](https://www.biorxiv.org/content/10.1101/2020.07.30.228981v2)

**Working memory as persistent neural activity**<br/>Foster JJ, Vogel EK, Awh E (in press). *Oxford Handbook of Human Memory* (Eds: MJ Kahana & AD Wagner)<br/>[preprint](https://psyarxiv.com/jh6e3/)

**Covert spatial attention speeds target individuation**<br/>Foster JJ, Bsales EM, Awh E (2020). *Journal of Neuroscience*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster et al_2020_JNeurosci.pdf) \| [data and code](https://osf.io/a9mvb/)

**Alpha-band oscillations track the retrieval of precise spatial representations from long-term memory**<br/>Sutterer DW, Foster JJ, Serences JT, Vogel EK, Awh E (2019). *Journal of Neurophysiology*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Sutterer et al_2019_JNeurophysiol.pdf) \| [data and code](https://osf.io/bh4dq/)

**Item-specific delay activity demonstrates concurrent storage of multiple active neural representations**<br/>Sutterer DW\*, Foster JJ\*, Adam KCS, Vogel EK, Awh E (2019). *PLOS Biology*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Sutterer Foster et al_2019_PLOS Biology.pdf) \| [data and code](https://osf.io/47cmn/)

**The role of alpha oscillations in spatial attention: Limited evidence for a suppression account**<br/>Foster JJ and Awh E (2019) *Current Opinion in Psychology*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster & Awh_2019_CurrOpinionPsych.pdf)

**Inverted encoding models assay population-level stimulus representations, not single-unit neural tuning**<br/>Sprague TC, Adam KCS, Foster JJ, Rahmati M, Sutterer DW, Vo VA (2018). *eNeuro*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Sprague et al_2018_eNeuro.pdf)

**Spatially selective alpha oscillations reveal moment-by-moment trade-offs between working memory and attention**<br/>van Moorselaar, Foster JJ, Sutterer DW, Theeuwes J, Olivers CNL, Awh E (2018). *Journal of Cognitive Neuroscience*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/van Moorselaar et al_2018_JoCN.pdf) \| [data and code](https://osf.io/56rzh/)

**Alpha-band activity reveals spontaneous representations of spatial position in visual working memory**<br/>Foster JJ, Bsales EM, Jaffe RJ, Awh E (2017). *Current Biology*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster et al_2017_CurrBio.pdf) \| [data and code](https://osf.io/vw4uc/) \| [research highlight in Nature Reviews Neuroscience](https://www.nature.com/articles/nrn.2017.143?WT.ec_id=NRN-201712&spMailingID=55372847&spUserID=NzM5Njg0NjU0NzUS1&spJobID=1282840712&spReportId=MTI4Mjg0MDcxMgS2)

**Alpha-band oscillations enable spatially and temporally resolved tracking of covert spatial attention**<br/>Foster JJ, Sutterer DW, Serences, JT, Vogel EK, Awh E (2017). *Psychological Science*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster et al_2017_PsychScience.pdf) \| [data and code](https://osf.io/29nxv/)

**The topography of alpha-band activity tracks the content of spatial working memory**<br/>Foster JJ, Sutterer, DW, Serences JT, Vogel EK, Awh E (2016). *Journal of Neurophysiology*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster et al_2016_JNeurophysiol.pdf) \| [data and code](https://osf.io/bwzfj/)

**Frontal and parietal EEG asymmetries interact to predict attentional bias to threat**<br/>Grimshaw GM, Foster JJ, Corballis PM (2014). *Brain and Cognition*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Grimshaw et al_2014_Brain&Cognition.pdf)

**Is feature-based attention always spatially global during visual search?**<br/>Foster JJ\* and Adam KCS\* (2014). *Journal of Neuroscience*.<br/>[pdf](http://joshuajfoster.github.io/files/papers/Foster & Adam_2014_JNeurosci.pdf)





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

class: middle, center, title-slide
count: false

# Software Citation Tools, Technologies,<br> and Best Practices

.huge.blue[Matthew Feickert]<br>
.large[(University of Wisconsin-Madison)]
<br>
[matthew.feickert@cern.ch](mailto:matthew.feickert@cern.ch)

[Software Citation and Recognition in HEP Workshop 2022](https://indico.cern.ch/event/1211229/contributions/5120858/)
<br>
November 23rd, 2022

.middle-logo[]

---
# Talk information
<br><br>

- .bold[talk time]: .bold[20 minute] presentation
   - .bold[10 minutes] talk
   - .bold[10 minutes] questions
- .bold[talk notes]: Follow up on Dan Katz's talk to keep a consistent thread

---
# Introduction and Overview

.kol-1-2.large[
- In Tuesday's session, Daniel Katz already gave very nice high level overview of software citation .bold[principles] and .bold[tools]
- This is an .red[opinionated] summary of the tooling landscape and examples of workflows
   - Full disclosure: Opinions formed from pyhf development.
- Meant to be recommendations to software developers on making your work as .bold[easy to cite as possible]
   - These recommendations can transfer to experiment software as well
]
.kol-1-2[
<br><br>
.center.width-100[[![dan-katz-intro](figures/dan-katz-intro.png)](https://indico.cern.ch/event/1211229/contributions/5120849/)]
.center[[Daniel Katz's talk](https://indico.cern.ch/event/1211229/contributions/5120849/)]
]

---
# Making clear statements in documentation

.kol-1-2.large[
- Zenodo
]
.kol-1-2[
<br><br>
.center.width-100[[![zenodo-landing-page](figures/zenodo-landing-page.png)](https://zenodo.org/)]
]

---
# CITATION.cff

.kol-1-2.large[
- Zenodo
]
.kol-1-2[
<br><br>
.center.width-100[[![zenodo-landing-page](figures/zenodo-landing-page.png)](https://zenodo.org/)]
]

---
# Zenodo

.kol-1-2.large[
- Zenodo
]
.kol-1-2[
<br><br>
.center.width-100[[![zenodo-landing-page](figures/zenodo-landing-page.png)](https://zenodo.org/)]
]

---
# DOI minting made easy

- Everything on Zenodo has a DOI
- You can upload directly to Zenodo or can enable it to [automatically preserve work from GitHub](https://guides.github.com/activities/citable-code/)
- We're going to do so now

.center[
.width-80[[![Zenodo_DOI_guide](figures/Zenodo_DOI_guide.png)](https://zenodo.org/account/settings/github/)]
]

---
# Proving a citation information from CLI

.kol-1-2.large[
- Zenodo
]
.kol-1-2[
<br><br>
.center.width-100[[![zenodo-landing-page](figures/zenodo-landing-page.png)](https://zenodo.org/)]
]

<!-- ---
# Goals of physics analysis at the LHC

.kol-1-1[
.kol-1-3.center[
.width-100[[![ATLAS_Higgs_discovery](figures/ATLAS_Higgs_discovery.png)](https://atlas.web.cern.ch/Atlas/GROUPS/PHYSICS/PAPERS/HIGG-2012-27/)]
Search for new physics
]
.kol-1-3.center[
<br>
.width-100[[![CMS-PAS-HIG-19-004](figures/CMS-PAS-HIG-19-004.png)](http://cms-results.web.cern.ch/cms-results/public-results/superseded/HIG-19-004/index.html)]

<br>
Make precision measurements
]
.kol-1-3.center[
.width-110[[![SUSY-2018-31_limit](figures/SUSY-2018-31_limit.png)](https://atlas.web.cern.ch/Atlas/GROUPS/PHYSICS/PAPERS/SUSY-2018-31/)]

Provide constraints on models through setting best limits
]
]

- All require .bold[building statistical models] and .bold[fitting models] to data to perform statistical inference
- Model complexity can be huge for complicated searches (hundreds of parameters + systematics)
- **Problem:** Time to fit can be .bold[very long] (for MLE fits, worse if pseudoexperiments required)
- .blue[Goal:] Empower analysts with fast fits and expressive models -->

---
# Summary
.kol-2-3[
- .huge.bold[Build community practices on top of established standards]
- Y
]
.kol-1-3[
- X
- Y
]

---
class: end-slide, center

Backup

---
# Does any of this actually work?

As mentioned, these opinions have been formed from developing pyhf, and the citation count for the [JOSS paper](https://doi.org/10.21105/joss.02823) has increased each year.

.center.width-100[[![pyhf-inspire-citations-count](figures/pyhf-inspire-citations-count.png)](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=refersto%3Arecid%3A1845084&ui-citation-summary=true)]


---
# References

1. F. James, Y. Perrin, L. Lyons, .italic[[Workshop on confidence limits: Proceedings](http://inspirehep.net/record/534129)], 2000.

---

class: end-slide, center
count: false

The end.

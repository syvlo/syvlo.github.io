---
layout: page
title: PhD thesis
permalink: /phd/
nav: false
---

<p style="text-align: center; font-weight: bold">Markovian models for SAR images:<br>Application to water detection in SWOT satellite images and multi-temporal analysis of urban areas</p>


Defended on November 16th, 2017 at Télécom Paris in front of the jury:
- Mr. [Eric Pottier](https://sites.google.com/site/ericpottier/) (President)
- Mr. [Ronan Fablet](https://perso.telecom-bretagne.eu/ronanfablet/) (Reviewer)
- Mr. [Jean-François Giovannelli](http://giovannelli.free.fr/) (Reviewer)
- Mme [Marie Chabert](http://chabert.perso.enseeiht.fr/) (Examinator)
- Mme [Gilda Schirinzi](https://en.uniparthenope.it/ugov/person/2984) (Examinator)
- Mr. [Loïc Denis](https://perso.univ-st-etienne.fr/deniloic/) (Examinator)
- Mr. Brent Williams (Invited member)
- Mme [Florence Tupin](https://perso.telecom-paristech.fr/tupin/) (Supervisor)
- Mr. Roger Fjørtoft (Supervisor)

## Downloads
- [Manuscript](/assets/pdf/Manuscrit_These.pdf) (55 MB)
- [Slides](/assets/pdf/Soutenance_These.pdf) (99 MB)

## Abstract
To obtain a better coverage both spatially and temporally, hydrologists use spaceborne data in addition to data acquired in situ. Resulting from a collaboration between NASA’s Jet Propulsion Laboratory (JPL) and the French Space Agency (CNES), the upcoming SWOT mission will provide global continental water elevation measures using Synthetic Aperture Radar (SAR) interferometry. In this dissertation, we address the problem of water detection in SWOT amplitude images, which is to be performed before the interferometric processing.
To this end, we propose to use a method dedicated to the detection of large water bodies and a specific algorithm for the detection of narrow rivers. The first method is based on Markov Random Fields (MRF). The classification is regularized and the class parameters, which cannot be assumed constant in the case of SWOT, are jointly estimated. The second method is based on segment detection at the pixel level, completed by a connection step.
In order to study the extension to multi-temporal data, we propose methods adapted to the processing of series of SAR images of urban areas. These areas feature strong scatterers, having a radiometry orders of magnitude higher than the other points in the image. The proposed models explicitly account for the presence of these strong scatterers by considering the images as a sum of two components (the background and the strong scatterers). Different regularization terms can then be applied to each of these components. Modeled as MRF, they can then be optimized exactly using graph cuts. We present applications for strong scatterers detection, regularization and change detection.


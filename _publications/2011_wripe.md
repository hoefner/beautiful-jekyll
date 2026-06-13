---
layout: publication
id: "2011_wripe"
title: "Modelling and Analysis of AODV in UPPAAL"
venue_type: conference
year: 2011
authors:
  - "Ansgar Fehnker"
  - "Rob van Glabbeek"
  - "Peter Höfner"
  - "Annabelle McIver"
  - "Marius Portmann"
  - "Wee Lum Tan"
booktitle: "Rigorous Protocol Engineering (WRiPE'11)"
publisher: "IEEE"
pdf: "2011_hoefner_wripe.pdf"
arxiv: "1512.07312"
bibtex: |
  @inproceedings{hoefner2011-7,
  author = {Fehnker, Ansgar and van Glabbeek, Rob and H{\"o}fner, Peter and McIver, Annabelle and Portmann, Marius and Tan, Wee Lum},
  title     = {{Modelling and Analysis of {AODV} in {UPPAAL}}},
  booktitle = {Rigorous Protocol Engineering (WRiPE'11) (WRiPE 2011)},
  year = {2011},
  publisher = {IEEE}
  }
---

This paper describes work in progress towards an automated formal and rigorous analysis of the Ad hoc On-Demand Distance Vector (AODV) routing protocol, a popular protocol used in ad hoc wireless networks. We give a brief overview of a model of AODV implemented in the UPPAAL model checker, and describe experiments carried out to explore AODV's behaviour in two network topologies. We were able to locate automatically and confirm some known problematic and undesirable behaviours. We believe this use of model checking as a diagnostic tool complements other formal methods based protocol modelling and verification techniques, such as process algebras. Model checking is in particular useful for the discovery of protocol limitations and in the development of improved variations.

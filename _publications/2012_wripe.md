---
layout: publication
id: "2012_wripe"
title: "Towards a Rigorous Analysis of AODVv2 (DYMO)"
venue_type: conference
year: 2012
authors:
  - "Sarah Edenhofer"
  - "Peter Höfner"
booktitle: "Rigorous Protocol Engineering (WRiPE 2012)"
publisher: "IEEE"
doi: "10.1109/ICNP.2012.6459942"
url: "https://doi.org/10.1109/ICNP.2012.6459942"
pdf: "2012_hoefner_wripe.pdf"
bibtex: |
  @inproceedings{hoefner2012_wripe,
    author    = {Edenhofer, Sarah and
                 H{\"o}fner, Peter},
    title     = {{Towards a Rigorous Analysis of {AODVv2} ({DYMO})}},
    booktitle = {Rigorous Protocol Engineering (WRiPE 2012)},
    editor    = {Foster, Nate and Gurney, Alexander},
    year      = {2012},
    publisher = {IEEE},
    doi       = {10.1109/ICNP.2012.6459942},
  }
---

Dynamic MANET On-demand (AODVv2) routing, formerly known as DYMO, is a routing protocol especially designed for wireless, multi hop networks. AODVv2 determines routes in a network in an on-demand fashion. In this paper we present a formal model of AODVv2, using the process algebra AWN. The benefit of this is two-fold: (a) the given specification is definitely free of ambiguities; (b) a formal and rigorous analysis of the routing protocol is now feasible. To underpin the latter point we also present a first analysis of the AODVv2 routing protocol. On the one hand we show that some of the problems discovered in the AODV routing protocol, the predecessor of AODVv2, have been addressed and solved. On the other hand we show that other limitations still exist; an example is the establishment of non-optimal routes. Even worse, we locate shortcomings in the AODVv2 routing protocol that do not occur in AODV. This yields the conclusion that AODVv2 is not necessarily better than AODV.

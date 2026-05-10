---
layout: publication
id: "2012_tacas"
title: "Automated Analysis of AODV using UPPAAL"
venue_type: conference
year: 2012
authors:
  - "Ansgar Fehnker"
  - "Rob van Glabbeek"
  - "Peter Höfner"
  - "Annabelle McIver"
  - "Marius Portmann"
  - "Wee Lum Tan"
booktitle: "Tools and Algorithms for the Construction and Analysis of Systems (TACAS 2012)"
series: "Lecture Notes in Computer Science"
volume: "7214"
pages: "173-187"
publisher: "Springer"
doi: "10.1007/978-3-642-28756-5_13"
url: "https://doi.org/10.1007/978-3-642-28756-5_13"
arxiv: "1512.07352"
pdf: "2012_hoefner_tacas.pdf"
bibtex: |
  @InProceedings{Hoefner2012-1,
    Author = {Fehnker, Ansgar and van Glabbeek, Rob and H{\"o}fner, Peter and McIver, Annabelle and Portmann, Marius and Tan, Wee Lum},
    Title = {Automated Analysis of AODV using UPPAAL},
    BookTitle = {Tools and Algorithms for the Construction and Analysis of Systems (TACAS 2012)},
    Editor = {Flanagan, Cormac and K{\"o}nig, Barbara},
    Series = {Lecture Notes in Computer Science},
    Volume = {7214},
    Pages = {173-187},
    Year = {2012},
    Publisher = {Springer},
    Doi = {10.1007/978-3-642-28756-5_13}
  }
---

This paper describes an automated, formal and rigorous analysis of the Ad hoc On-Demand Distance Vector (AODV) routing protocol, a popular protocol used in wireless mesh networks. We give a brief overview of a model of AODV implemented in the UPPAAL model checker. It is derived from a process-algebraic model which reflects precisely the intention of AODV and accurately captures the protocol specification. Furthermore, we describe experiments carried out to explore AODV's behaviour in all network topologies up to 5 nodes. We were able to automatically locate problematic and undesirable behaviours. This is in particular useful to discover protocol limitations and to develop improved variants. This use of model checking as a diagnostic tool complements other formal-methods-based protocol modelling and verification techniques, such as process algebra.

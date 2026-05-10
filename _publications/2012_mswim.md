---
layout: publication
id: "2012_mswim"
title: "A Rigorous Analysis of AODV and its Variants"
venue_type: conference
year: 2012
acronym: "MSWiM 2012"
authors:
  - "Peter Höfner"
  - "Rob van Glabbeek"
  - "Wee Lum Tan"
  - "Marius Portmann"
  - "Annabelle McIver"
  - "Ansgar Fehnker"
booktitle: "Modeling, Analysis and Simulation of Wireless and Mobile Systems (MSWiM 2012)"
publisher: "ACM"
pages: "203-212"
doi: "10.1145/2387238.2387274"
url: "https://doi.org/10.1145/2387238.2387274"
arxiv: "1512.08873"
pdf: "2012_hoefner_mswim.pdf"
note: "Nominated for best paper award"
bibtex: |
  @InProceedings{Hoefner2012-7,
    Author    = {H{\"o}fner, Peter and van Glabbeek, Rob and Tan, Wee Lum and Portmann, Marius and McIver, Annabelle and Fehnker, Ansgar},
    Title     = {A Rigorous Analysis of {AODV} and its Variants},
    BookTitle = {Modeling, Analysis and Simulation of Wireless and Mobile Systems (MSWiM 2012)},
    Pages     = {203-212},
    Year      = {2012},
    Publisher = {ACM},
    Doi       = {10.1145/2387238.2387274}
  }
---

In this paper we present a rigorous analysis of the Ad hoc On-Demand Distance Vector (AODV) routing protocol using a formal specification in AWN (Algebra for Wireless Networks), a process algebra specifically tailored for the modelling of Mobile Ad Hoc Networks and Wireless Mesh Network protocols. Our formalisation models the exact details of the core functionality of AODV, such as route discovery, route maintenance and error handling. We demonstrate how AWN can be used to reason about critical protocol correctness properties by providing a detailed proof of loop freedom. In contrast to evaluations using simulation or model checking, our proof is generic and holds for any possible network scenario in terms of network topology, node mobility and traffic patterns. A key contribution of this paper is the demonstration of how the reasoning and proofs can relatively easily be adapted to protocol variants.
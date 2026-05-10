---
layout: publication
id: "2013_formats"
title: "Quantitative Analysis of AODV and its Variants on Dynamic Topologies using Statistical Model Checking"
venue_type: conference
year: 2013
acronym: "FORMATS 2013"
authors:
  - "Peter Höfner"
  - "Maryam Kamali"
booktitle: "Formal Modelling and Analysis of Timed Systems (FORMATS 2013)"
editors:
  - "V. Braberman"
  - "L. Fribourg"
series: "Lecture Notes in Computer Science"
volume: "8053"
pages: "121-136"
publisher: "Springer"
doi: "10.1007/978-3-642-40229-6_9"
url: "https://doi.org/10.1007/978-3-642-40229-6_9"
pdf: "2013_hoefner_formats.pdf"
bibtex: |
  @InProceedings{Hoefner2013_formats,
    Author = {H{\"o}fner, Peter and Kamali, Maryam},
    Title = {Quantitative Analysis of {AODV} and its Variants on Dynamic Topologies using Statistical Model Checking},
    BookTitle = {Formal Modelling and Analysis of Timed Systems (FORMATS 2013)},
    Editor = {Braberman, V{\'i}tor and Fribourg, Laurent},
    Series = {Lecture Notes in Computer Science},
    Volume = {8053},
    Pages = {121-136},
    Year = {2013},
    Publisher = {Springer},
    Doi = {10.1007/978-3-642-40229-6_9}
  }
---

Wireless Mesh Networks (WMNs) are self-organising ad-hoc networks that support broadband communication. Due to changes in topology, route discovery and maintenance play a crucial role in the reliability and performance of such networks. Formal analysis of WMNs using exhaustive model checking techniques is often infeasible because large network sizes and topology changes yield state-space explosion. Statistical model checking can overcome this limitation and enables quantitative analysis.

In this paper we illustrate this through a detailed analysis of the Ad hoc On-demand Distance Vector (AODV) routing protocol. We show that some optional features of AODV are not useful and that AODV exhibits unexpected behaviour, yielding a high probability of route discovery failure.
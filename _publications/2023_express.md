---
layout: publication
id: "2023_express"
title: "A Lean-Congruence Format for EP-Bisimilarity"
venue_type: conference
year: 2023
acronym: "EXPRESS/SOS 2023"
authors:
  - "Rob van Glabbeek"
  - "Peter Höfner"
  - "Weiyou Wang"
booktitle: "Expressiveness in Concurrency and Structural Operational Semantics"
publisher: "Open Publishing Association"
series: "Electronic Proceedings in Theoretical Computer Science"
volume: "387"
pages: "59-75"
doi: "10.4204/EPTCS.387.6"
url: "https://doi.org/10.4204/EPTCS.387.6"
arxiv: "2308.16350"
pdf: "2023_hoefner_express.pdf"
bibtex: |
  @inproceedings{hoefner2023_express,
    author    = {van Glabbeek,Rob  and
                 H{\"o}fner, Peter and
                 Wang, Weiyou},
    title     = {A Lean-Congruence Format for EP-Bisimilarity},
    editor ={Mezzina, Claudio Antares and
                  Caltais, Georgiana},
    year      = {2023},
    booktitle = {Expressiveness in Concurrency and Structural Operational Semantics (EXPRESS/SOS 2023)},
    series    = {Electronic Proceedings in Theoretical Computer Science},
    volume    = {387},
    publisher = {Open Publishing Association},
    pages     = {59--75},
    doi       = {10.4204/EPTCS.387.6}
  }
---

Enabling preserving bisimilarity is a refinement of strong bisimilarity that preserves safety as well as liveness properties. To define it properly, labelled transition systems needed to be upgraded with a successor relation, capturing concurrency between transitions enabled in the same state. We enrich the well-known De Simone format to handle inductive definitions of this successor relation. We then establish that ep-bisimilarity is a congruence for the operators, as well as lean congruence for recursion, for all (enriched) De Simone languages.

---
layout: publication
id: "2017_express"
title: "Analysing Mutual Exclusion using Process Algebra with Signals"
venue_type: conference
year: 2017
acronym: "EXPRESS/SOS 2017"
authors:
  - "Victor Dyseryn"
  - "Rob van Glabbeek"
  - "Peter Höfner"
booktitle: "Expressiveness in Concurrency and Structural Operational Semantics"
publisher: "Open Publishing Association"
series: "Electronic Proceedings in Theoretical Computer Science"
volume: "255"
pages: "18-34"
doi: "10.4204/EPTCS.255.2"
url: "https://doi.org/10.4204/EPTCS.255.2"
pdf: "2017_hoefner_express.pdf"
bibtex: |
  @inproceedings{hoefner2017_express,
    author    = {Dyseryn, Victor and
                 van Glabbeek, Rob and
                 H{\"o}fner, Peter},
    title     = {{Analysing Mutual Exclusion using Process Algebra with Signals}},
    year      = {2017},
    booktitle = {Expressiveness in Concurrency and Structural Operational Semantics},
    series    = {Electronic Proceedings in Theoretical Computer Science},
    volume    = {255},
    publisher = {Open Publishing Association},
    pages     = {18--34},
    doi       = {10.4204/EPTCS.255.2},
  }
---

In contrast to common belief, the Calculus of Communicating Systems (CCS) and similar process algebras lack the expressive power to accurately capture mutual exclusion protocols without enriching the language with fairness assumptions. Adding a fairness assumption to implement a mutual exclusion protocol seems counter-intuitive. We employ a signalling operator, which can be combined with CCS, or other process calculi, and show that this minimal extension is expressive enough to model mutual exclusion: we confirm the correctness of Peterson's mutual exclusion algorithm for two processes, as well as Lamport's bakery algorithm, under reasonable assumptions on the underlying memory model. The correctness of Peterson's algorithm for more than two processes requires stronger, less realistic assumptions on the underlying memory model.

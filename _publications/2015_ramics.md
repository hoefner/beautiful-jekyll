---
layout: publication
id: "2015_ramics"
title: "Tool-Based Verification of a Relational Vertex Coloring Program"
venue_type: conference
year: 2015
acronym: "RAMiCS 2015"
authors:
  - "Rudolf Berghammer"
  - "Peter Höfner"
  - "Insa Stucke"
booktitle: "Relational and Algebraic Methods in Computer Science"
publisher: "Springer"
series: "Lecture Notes in Computer Science"
volume: "9348"
pages: "275-292"
doi: "10.1007/978-3-319-24704-5_17"
url: "https://doi.org/10.1007/978-3-319-24704-5_17"
pdf: "2015_hoefner_ramics.pdf"
bibtex: |
  @InProceedings{Hoefner2015_ramics,
    Author = {Berghammer, Rudolf and H{\"o}fner, Peter and Stucke, Insa},
    Title = {Tool-Based Verification of a Relational Vertex Coloring Program},
    BookTitle = {Relational and Algebraic Methods in Computer Science (RAMiCS 2015)},
    Editor = {Kahl, Wolfram and Oliveira, Jos{\'e} N. and Winter, Michael},
    Series = {Lecture Notes in Computer Science},
    Volume = {9348},
    Pages = {275-292},
    Year = {2015},
    Publisher = {Springer},
    Doi = {10.1007/978-3-319-24704-5_17}
  }
---

We present different approaches of using a special purpose computer algebra system and theorem provers in software verification. To this end, we first develop a purely algebraic while-program for computing a vertex coloring of an undirected (loop-free) graph. For showing its correctness, we then combine the well-known assertion-based verification method with relation-algebraic calculations. Based on this, we show how automatically to test loop-invariants by means of the RelView tool and also compare the usage of three different theorem provers in respect to the verification of the proof obligations: the automated theorem prover Prover9 and the two proof assistants Coq and Isabelle/HOL. As a result, we illustrate that algebraic abstraction yields verification tasks that can easily be verified with off-the-shelf theorem provers, but also reveal some shortcomings and difficulties with theorem provers that are nowadays available.

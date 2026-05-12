---
layout: publication
id: "2020_jlamp"
title: "Relational Characterisations of Paths"
venue_type: journal
year: 2020
acronym: "JLAMP"
authors:
  - "Rudolf Berghammer"
  - "Furusawa Hitoshi"
  - "Walter Guttmann"
  - "Peter Höfner"
journal: "Journal of Logic and Algebraic Methods in Programming"
publisher: "Elsevier"
volume: "117"
doi: "10.1016/j.jlamp.2020.100590"
url: "https://doi.org/10.1016/j.jlamp.2020.100590"
arxiv: "1801.04026"
pdf: "2020_hoefner_jlamp.pdf"
bibtex: |
  @article{Hoefner2020-3,
    Author = {Berghammer, Rudolf and Furusawa, Hitoshi and Guttmann, Walter and H{\"o}fner, Peter},
    Title = {Relational Characterisations of Paths},
    Journal = {Journal of Logic and Algebraic Methods in Programming},
    Volume = {117},
    Year = {2020},
    Publisher = {Elsevier},
    Doi = {10.1016/j.jlamp.2020.100590}
  }
---

Binary relations are one of the standard ways to encode, characterise and reason about graphs. Relation algebras provide equational axioms for a large fragment of the calculus of binary relations. Although relations are standard tools in many areas of mathematics and computing, researchers usually fall back to point-wise reasoning when it comes to arguments about paths in a graph. We present a purely algebraic way to specify different kinds of paths in relation algebras. We study the relationship between paths with a designated root vertex and paths without such a vertex. Since we stay in first-order logic this development helps with mechanising proofs. To demonstrate the applicability of the algebraic framework we verify the correctness of three basic graph algorithms. All results of this paper are formally verified using Isabelle/HOL.

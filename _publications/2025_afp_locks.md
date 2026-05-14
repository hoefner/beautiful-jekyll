---
layout: publication
id: "2025_afp_locks"
title: "Rely-Guarantee Extensions and Locks"
venue_type: afp
subtype: "Archive of Formal Proofs"
year: 2025
authors:
  - "Robert J. Colvin"
  - "Scott Heiner"
  - "Peter Höfner"
  - "Roger C. Su"
journal: "Archive of Formal Proofs"
url: "https://www.isa-afp.org/entries/RG_Locks.html"
bibtex: |
  @article{hoefner2025_afp_locks,
  author  = {Colvin, Robert J. and Heiner, Scott and H{\"o}fner, Peter and Su, Roger C.},
  title   = {Rely-Guarantee Extensions and Locks},
  journal = {Archive of Formal Proofs},
  year    = {2025},
  note    = {\url{https://isa-afp.org/entries/RG_Locks.html},
             Formal proof development},
  ISSN    = {2150-914x},
  }
---

We enhance rely-guarantee verification in Isabelle/HOL by extending the 2003 built-in library with flexible syntax, data-invariant support, and new tactics. We demonstrate our enhanced library by applying it to the examples attached to the original library. We also apply our library to three queue locks: the Abstract Queue Lock, the Ticket Lock, and the Circular Buffer Lock.
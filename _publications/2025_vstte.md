---
layout: publication
id: "2025_vstte"
title: "Rely-Guarantee Verification of Queue Locks with Proof Support in Isabelle/HOL"
venue_type: conference
year: 2025
acronym: "VSTTE 2025"
authors:
  - "Robert J. Colvin"
  - "Scott Heiner"
  - "Peter Höfner"
  - "Roger C. Su"
publisher: "Springer"
series: "Lecture Notes in Computer Science"
volume: ""
pages: ""
doi: ""
url: ""
pdf: "2025_hoefner_vstte.pdf"
note: "in press"
bibtex: |
  @InProceedings{Hoefner2025_vstte,
    Author = {Colvin, Robert J. and Heiner, Scott and H{\"o}fner, Peter and  Su, Roger C.},
    Title = {Rely-Guarantee Verification of Queue Locks with Proof Support in Isabelle/HOL},
    BookTitle = {Verified Software: Theories, Tools, and Experiments (VSTTE 2025)},
    Editor = {Pit-Claudel, Cl{\'e}ment and Kosaian, Katherine},
    Series = {Lecture Notes in Computer Science},
    Volume = {},
    Pages = {},
    Year = {2025},
    Publisher = {Springer},
    Doi = {},
    Note = {(in press)}
  }
---

To support rely-guarantee reasoning, we present an extension to Isabelle/HOL's built-in library, which we use to verify a hierarchy of queue locks. The framework incorporates novel features of Isabelle, and enables flexible syntax, assertion-annotations, and tactics for both automated and structured proofs. Assertion-annotations enable elegant top-down specification from an abstract queue lock to a non-trivial, practical circular-buffer queue lock.
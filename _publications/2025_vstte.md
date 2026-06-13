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
pdf: "2025_hoefner_vstte.pdf"
note: "in press"
bibtex: |
  @inproceedings{hoefner2025_vstte,
  author = {Colvin, Robert J. and Heiner, Scott and H{\"o}fner, Peter and  Su, Roger C.},
  title     = {{Rely-Guarantee Verification of Queue Locks with Proof Support in Isabelle/HOL}},
  booktitle = {Verified Software: Theories, Tools, and Experiments (VSTTE 2025)},
  editor = {Pit-Claudel, Cl{\'e}ment and Kosaian, Katherine},
  series = {Lecture Notes in Computer Science},
  year = {2025},
  publisher = {Springer},
  note = {(in press)}
  }
---

To support rely-guarantee reasoning, we present an extension to Isabelle/HOL's built-in library, which we use to verify a hierarchy of queue locks. The framework incorporates novel features of Isabelle, and enables flexible syntax, assertion-annotations, and tactics for both automated and structured proofs. Assertion-annotations enable elegant top-down specification from an abstract queue lock to a non-trivial, practical circular-buffer queue lock.
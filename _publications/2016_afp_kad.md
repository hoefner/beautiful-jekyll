---
layout: publication
id: "2016_afp_kad"
title: "Kleene Algebras with Domain"
venue_type: afp
subtype: "Archive of Formal Proofs"
year: 2016
authors:
  - "Victor B. F. Gomes"
  - "Walter Guttmann"
  - "Peter Höfner"
  - "Georg Struth"
  - "Tjark Weber"
journal: "Archive of Formal Proofs"
bibtex: |
  @misc{Hoefner2016_afp_kad,
    author    = {Gomes, Victor B. F. and
                 Guttmann, Walter and
                 H{\"o}fner, Peter and
                 Struth, Georg and
                 Weber, Tjark},
    title     = {{Kleene Algebras with Domain}},
    Journal = {Archive of Formal Proofs},
    year      = {2016},
  note    = {\url{https://isa-afp.org/entries/KAD.html},
             Formal proof development}
  }
---

Kleene algebras with domain are Kleene algebras endowed with an operation that maps each element of the algebra to its domain of definition (or its complement) in abstract fashion. They form a simple algebraic basis for Hoare logics, dynamic logics or predicate transformer semantics. We formalise a modular hierarchy of algebras with domain and antidomain (domain complement) operations in Isabelle/HOL that ranges from domain and antidomain semigroups to modal Kleene algebras and divergence Kleene algebras. We link these algebras with models of binary relations and program traces. We include some examples from modal logics, termination and program analysis.

---
layout: publication
id: "2014_afp_aodv"
title: "Loop Freedom of the (Untimed) AODV Routing Protocol"
venue_type: formalisation
year: 2014
authors:
  - "Timothy Bourke"
  - "Peter Höfner"
journal: "Archive of Formal Proofs"
url: "https://www.isa-afp.org/entries/AODV.shtml"
bibtex: |
  @article{Hoefner2014_afp_atva,
    Author  = {Bourke, Timothy and H{\"o}fner, Peter},
    Title   = {Loop Freedom of the (Untimed) {AODV} Routing Protocol},
    Journal = {Archive of Formal Proofs},
    Year    = {2014}
  }
---

The Ad hoc On-demand Distance Vector (AODV) routing protocol allows nodes in a Mobile Ad hoc Network (MANET) or Wireless Mesh Network (WMN) to determine where to forward data packets. The protocol is considered loop free if it never leads to routing decisions that forward packets in circles.

This development mechanises an existing pen-and-paper proof of loop freedom of AODV. The protocol is modelled in the Algebra of Wireless Networks (AWN), following earlier work and AFP mechanisations. The proof relies on a novel compositional approach for lifting invariants to networks of nodes.

The mechanisation is further exploited to analyse several variants of AODV. Isabelle/HOL is able to automatically re-establish most proof obligations and precisely identify the proof steps that are no longer valid for modified protocol variants.
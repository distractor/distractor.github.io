---
title: "Fast variable density node generation on parametric surfaces with application to mesh-free methods"
authors: "Duh, U., Kosec, G., & Slak, J."
collection: publications
permalink: /publication/2021-03-15-surface-fill
excerpt: 'An algorithm to generate meshless node sets on surfaces is presented.'
date: 2021-02-17
journal: 'SIAM Journal on Scientific Computing'
localfile: 'papers/P_2021_DuhKosecSlak_SurfaceFill.pdf'
bibtex: 'papers/P_2021_DuhKosecSlak_SurfaceFill.bib'
officialurl: 'https://epubs.siam.org/doi/abs/10.1137/20M1325642'
doi: '10.1137/20M1325642'
citation: 'Duh, U., Kosec, G., & Slak, J. (2021). Fast variable density node generation on parametric surfaces with application to mesh-free methods. SIAM Journal on Scientific Computing, 43(2), A980-A1000.'
---

## Abstract

Domain discretization is considered a dominant part of solution procedures for solving partial differential equations. It is widely accepted that mesh generation is among the most cumbersome parts of the finite element method analysis and often requires human assistance, especially in complex three-dimensional geometries. When using alternative mesh-free approaches, the problem of mesh generation is simplified to the problem of positioning nodes, a much simpler task, though still not trivial. In this paper we present an algorithm for generation of nodes on arbitrary $d$-dimensional surfaces. This algorithm complements a recently published algorithm for generation of nodes in domain interiors and represents another step toward a fully automated dimension-independent solution procedure for solving partial differential equations. The proposed algorithm generates nodes with variable density on surfaces parameterized over arbitrary parametric domains in a dimension-independent way in $O(N\log N)$ time. It is also compared with existing algorithms for generation of surface nodes for mesh-free methods in terms of quality and execution time.

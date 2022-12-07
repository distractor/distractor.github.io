---
title: "Discretized Boundary Surface Reconstruction"
authors: 'Mitja Jančič, Viktor Cvrtila, Gregor Kosec'
collection: publications
permalink: /publication/2021-10-01-reconstruction
excerpt: 'Discretized Boundary Surface Reconstruction using parametric splines.'
date: 2021-10-01
journal: 'IEEE'
localfile: 'papers/2021-10-01-reconstruction.pdf'
bibtex: 'papers/2021-10-01-reconstruction.bib'
officialurl: 'https://ieeexplore.ieee.org/document/9596965'
doi: '10.23919/MIPRO52101.2021.9596965'
citation: 'Jančič, Mitja, Viktor Cvrtila, and Gregor Kosec. "Discretized boundary surface reconstruction." 2021 44th International Convention on Information, Communication and Electronic Technology (MIPRO). IEEE, 2021.'
---

## Abstract

Domain discretization is an essential part of the solution procedure in numerical simulations. Meshless methods simplify the domain discretization to positioning of nodes in the interior and on the boundary of the domain. However, generally speaking, the shape of the boundary is often undefined and thus needs to be constructed before it can be discretized with a desired internodal spacing. Domain shape construction is far from trivial and is the main challenge of this paper. We tackle the simulation of moving boundary problems where the lack of domain shape information can introduce difficulties. We present a solution for 2D surface reconstruction from discretization points using cubic splines and thus providing a surface description anywhere in the domain. We also demonstrate the presented algorithm in a simulation of phase-change-like problem.
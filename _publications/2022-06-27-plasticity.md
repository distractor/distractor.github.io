---
title: "A Meshless Solution of a Small-Strain Plasticity Problem"
authors: 'Filip Strniša, Mitja Jančič, Gregor Kosec'
collection: publications
permalink: /publication/2022-06-27-plasticity
excerpt: 'A Meshless Solution of a Small-Strain Plasticity Problem.'
date: 2022-06-27
journal: 'IEEE'
localfile: 'papers/2022-06-27-plasticity.pdf'
bibtex: 'papers/2022-06-27-plasticity.bib'
officialurl: 'https://ieeexplore.ieee.org/document/9803585'
doi: '10.23919/MIPRO55190.2022.9803585'
citation: 'F. Strniša, M. Jančič and G. Kosec, "A Meshless Solution of a Small-Strain Plasticity Problem," 2022 45th Jubilee International Convention on Information, Communication and Electronic Technology (MIPRO), 2022, pp. 257-262, doi: 10.23919/MIPRO55190.2022.9803585.'
---

## Abstract

When the deformations of a solid body are sufficiently large, parts of the body undergo a permanent deformation commonly refereed to as plastic deformation. Several plasticity models describing such phenomenon have been proposed, e.g. von Mises, Tresca, etc. Traditionally, the finite element method (FEM) is the numerical tool of choice for engineers who are solving such problems. In this work, however, we present the implementation of the von Mises plasticity model with non-linear isotropic hardening in our in-house developed MEDUSA library, utilizing a variant of meshless methods – namely the radial basis function-generated finite differences (RBF-FD). We define a simple plane stress case, where a 2D block is fixed at one edge, and a tensile force, which causes the block to deform, is applied to it at the opposite edge. We show that results are in good agreement with the numerical solution obtained by Abaqus FEA, a commercial FEM solver.
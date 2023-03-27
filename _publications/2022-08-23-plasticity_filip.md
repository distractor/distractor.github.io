---
title: "Meshless simulation of infinitesimal elastoplastic deformation of a 3D body"
authors: 'Filip Strniša, Mitja Jančič, Gregor Kosec'
collection: publications
permalink: /publication/2022-08-23-plasticity_filip
excerpt: 'Meshless simulation of infinitesimal elastoplastic deformation of a 3D body.'
date: 2022-08-23
journal: 'IEEE'
localfile: 'papers/2022-08-23-plasticity_filip.pdf'
bibtex: 'papers/2022-08-23-plasticity_filip.bib'
officialurl: 'https://www.ctresources.info/ccc/paper.html?id=9396'
citation: 'F. Strnisa, M. Jancic, G. Kosec, "Meshless simulation of infinitesimal elastoplastic deformation of a 3D body", in B.H.V. Topping, J. Kruis, (Editors), "Proceedings of the Fourteenth International Conference on Computational Structures Technology", Civil-Comp Press, Edinburgh, UK, Online volume: CCC 3, Paper 3.4, 2022'
---

## Abstract

Modelling elastoplasticity is a non-linear problem which requires multi-step iterative solving. Traditionally such problems are solved with the finite elements method (FEM), which is also often featured in commercially available software for modelling solid mechanics. The accuracy of FEM solutions depends on the quality of the mesh, which can become computationally expensive when discretizing complex domains. Meshless methods do not require meshing, and can alternatively be used to solve diverse solid-mechanics problems. In this work we present our implementation of elastoplasticity into our C++ library for solving partial differential equations, which is based on the use of meshless methods – Medusa. The implementation is tested on a simple 3D von Mises elastoplasticity case, and results are compared against the solution of the same case in Abaqus. Results of both approaches are in good agreement with each other. 
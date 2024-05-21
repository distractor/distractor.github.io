---
title: "Spatially dependent node regularity in meshless approximation of partial differential equations"
authors: 'Miha Rot, Mitja Jančič, Gregor Kosec'
collection: publications
permalink: /publication/2024-04-27-node_regularity
excerpt: 'Spatially dependent node regularity in meshless approximation of partial differential equations'
date: 2024-04-27
journal: 'Journal of Computational Science'
localfile: 'papers/2024-04-27-node_regularity.pdf'
bibtex: 'papers/2024-04-27-node_regularity.bib'
officialurl: 'https://www.sciencedirect.com/science/article/pii/S1877750324000991?via%3Dihub'
citation: 'Rot, Miha, Mitja Jančič, and Gregor Kosec. "Spatially dependent node regularity in meshless approximation of partial differential equations." Journal of Computational Science (2024): 102306.'
---

## Abstract

In this paper, we address a way to reduce the total computational cost of meshless approximation by reducing the required stencil size through spatially varying computational node regularity. Rather than covering the entire domain with scattered nodes, only regions with geometric details are covered with scattered nodes, while the rest of the domain is discretized with regular nodes. A simpler approximation can be used in regions covered by regular nodes, effectively reducing the required stencil size and computational cost compared to the approximation on scattered nodes where a set of polyharmonic splines is added to ensure convergent behaviour.

This paper is an extended version of conference paper entitled “Spatially-varying meshless approximation method for enhanced computational efficiency” (Jančič et al., 2023) presented at “International Conference on Computational Science (ICCS) 2023”. The paper is extended with discussion on development and implementation of a hybrid regular-scattered node positioning algorithm (HyNP). The performance of the proposed HyNP algorithm is analysed in terms of separation distance and maximal empty sphere radius. Furthermore, it is demonstrated that HyNP nodes can be used for solving problems from fluid flow and linear elasticity, both in 2D and 3D, using meshless methods.

The extension also provides additional analyses of computational efficiency and accuracy of the numerical solution obtained on the spatially-variable regularity of discretization nodes. In particular, different levels of refinement aggressiveness and scattered layer widths are considered to exploit the computational efficiency gains offered by such solution procedure.
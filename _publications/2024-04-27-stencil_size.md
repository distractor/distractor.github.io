---
title: "Some observations regarding the RBF-FD approximation accuracy dependence on stencil size"
authors: 'Andrej Kolar-Požun, Mitja Jančič, Miha Rot, Gregor Kosec'
collection: publications
permalink: /publication/2024-04-27-stencil_size
excerpt: 'Some observations regarding the RBF-FD approximation accuracy dependence on stencil size'
date: 2024-04-27
journal: 'Journal of Computational Science'
localfile: 'papers/2024-04-27-stencil_size.pdf'
bibtex: 'papers/2024-04-27-stencil_size.bib'
officialurl: 'https://www.sciencedirect.com/science/article/pii/S1877750324000772?via%3Dihub'
citation: 'Kolar-Požun, Andrej, Mitja Jančič, Miha Rot, and Gregor Kosec. "Some observations regarding the RBF-FD approximation accuracy dependence on stencil size." Journal of Computational Science (2024): 102284.'
---

## Abstract

When solving partial differential equations on scattered nodes using the Radial Basis Function-generated Finite Difference (RBF-FD) method, one of the parameters that must be chosen is the stencil size. Focusing on Polyharmonic Spline RBFs with monomial augmentation, we observe that it affects the approximation accuracy in a particularly interesting way — the solution error oscillates under increasing stencil size. We find that we can connect this behaviour with the spatial dependence of the signed approximation error. Based on this observation we are able to introduce a numerical quantity that could indicate whether a given stencil size is locally optimal. This work is an extension of our ICCS 2023 conference paper (Kolar-Požun et al., 2023).
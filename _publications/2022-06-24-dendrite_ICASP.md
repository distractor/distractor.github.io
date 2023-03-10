---
title: "A sharp-interface mesoscopic model for dendritic growth"
authors: 'Mitja Jančič, Miha Založnik, Gregor Kosec'
collection: publications
permalink: /publication/2022-06-24-dendrite-ICASP
excerpt: 'A sharp-interface mesoscopic model for dendritic growth.'
date: 2022-24-06
journal: 'IOP Conference Series: Materials Science and Engineering'
localfile: 'papers/2022-06-24-dendrite-ICASP.pdf'
bibtex: 'papers/2022-06-24-dendrite-ICASP.bib'
officialurl: 'https://iopscience.iop.org/article/10.1088/1757-899X/1274/1/012046'
doi: '10.1088/1757-899X/1274/1/012046'
citation: 'Jančič, Mitja, Miha Založnik, and Gregor Kosec. "A sharp-interface mesoscopic model for dendritic growth." IOP Conference Series: Materials Science and Engineering. Vol. 1274. No. 1. IOP Publishing, 2023.'
---

## Abstract

The grain envelope model (GEM) describes the growth of envelopes of dendritic crystal grains during solidification. Numerically the growing envelopes are usually tracked using an interface capturing method employing a phase field equation on a fixed grid. Such an approach describes the envelope as a diffuse interface, which can lead to numerical artefacts that are possibly detrimental. In this work, we present a sharp-interface formulation of the GEM that eliminates such artefacts and can thus track the envelope with high accuracy. The new formulation uses an adaptive meshless discretization method to solve the diffusion in the liquid around the grains. We use the ability of the meshless method to operate on scattered nodes to accurately describe the interface, i.e., the envelope. The proposed algorithm combines parametric surface reconstruction, meshless discretization of parametric surfaces, global solution construction procedure and partial differential operator approximation using monomials as basis functions. The approach is demonstrated on a two-dimensional h-adaptive solution of diffusive growth of dendrites and assessed by comparison to a conventional diffuse-interface fixed-grid GEM. 
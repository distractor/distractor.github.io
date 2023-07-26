---
title: "Spatially-Varying Meshless Approximation Method for Enhanced Computational Efficiency"
authors: 'Mitja Jančič, Miha Rot, Gregor Kosec'
collection: publications
permalink: /publication/2023-06-26-spatially_varying
excerpt: 'Spatially-varying meshless approximation method for enhanced computational efficiency.'
date: 2023-06-26
journal: 'International Conference on Computational Science'
bibtex: 'papers/2023-06-26-spatially_varying.bib'
officialurl: 'https://link.springer.com/chapter/10.1007/978-3-031-36027-5_39'
citation: 'Jančič, M., Rot, M., Kosec, G. (2023). Spatially-Varying Meshless Approximation Method for Enhanced Computational Efficiency. In: Mikyška, J., de Mulatier, C., Paszynski, M., Krzhizhanovskaya, V.V., Dongarra, J.J., Sloot, P.M. (eds) Computational Science – ICCS 2023. ICCS 2023. Lecture Notes in Computer Science, vol 10476. Springer, Cham. https://doi.org/10.1007/978-3-031-36027-5_39'
---

## Abstract

In this paper, we address a way to reduce the total computational cost of meshless approximation by reducing the required stencil size through spatially varying computational node regularity. Rather than covering the entire domain with scattered nodes, only regions with geometric details are covered with scattered nodes, while the rest of the domain is discretized with regular nodes. A simpler approximation using solely monomial basis can be used in regions covered by regular nodes, effectively reducing the required stencil size and computational cost compared to the approximation on scattered nodes where a set of polyharmonic splines is added to ensure convergent behaviour.

The performance of the proposed hybrid scattered-regular approximation approach, in terms of computational efficiency and accuracy of the numerical solution, is studied on natural convection driven fluid flow problems. We start with the solution of the de Vahl Davis benchmark case, defined on a square domain, and continue with two- and three-dimensional irregularly shaped domains. We show that the spatial variation of the two approximation methods can significantly reduce the computational demands, with only a minor impact on the accuracy.
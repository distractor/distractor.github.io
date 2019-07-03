---
title: "Parallel Coordinate Free Implementation of Local Meshless Method"
authors: "J. Slak, G. Kosec"
collection: publications
permalink: /publication/2018-05-24-parallel-mipro
talk: 2018-05-24-parallel-mipro
excerpt: 'This paper presents an implementation of a Meshless Local Strong Form Method that allows users to write elegant code expressed in terms of abstract mathematical objects.'
date: 2018-05-24
journal: 'MIPRO 2018: 41st International Convention on Information and Communication Technology, Electronics and Microelectronics, May 21–25, 2018, Opatija, Croatia'
localfile: 'papers/CP_2018_SlakKosec_Mipro.pdf'
bibtex: 'papers/CP_2018_SlakKosec_Mipro.bib'
doi: '10.23919/MIPRO.2018.8400034'
officialurl: 'https://ieeexplore.ieee.org/document/8400034'
citation: ' J. Slak and G. Kosec, Parallel coordinate free implementation of local meshless method, in: MIPRO 2018: 41st International Convention on Information and Communication Technology, Electronics and Microelectronics, May 21–25, 2018, Opatija, Croatia (ed. K. Skala), MIPRO proceedings, IEEE, Croatian Society for Information and Communication Technology, Electronics and Microelectronics, 2018 pp. 194–200, doi:10.23919/mipro.2018.8400034.'
---

## Abstract

This paper presents an implementation of a Meshless Local Strong Form Method that allows
users to write elegant code expressed in terms of abstract mathematical objects, such as
operators and fields, consequently avoiding working directly with matrix and array indices,
which is tedious and error prone. This is achieved by using object oriented programming
techniques for definition of abstract concepts and leveraging C++'s powerful templating
mechanism. It is demonstrated that code written this way has little-to-no performance
overhead compared to classical numerical code while being more expressive and readable,
which gravely shortens model development and testing phases. The overall functionality of
presented implementation is illustrated on numerical examples from classical
thermodynamics, linear elasticity and fluid dynamics in one, two and three dimensions.

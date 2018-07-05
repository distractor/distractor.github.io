---
title: "Parallel Coordinate Free Implementation of Local Meshless Method"
collection: publications
permalink: /publication/2018-05-24-parallel-mipro
excerpt: 'This paper presents an implementation of a Meshless Local Strong Form Method that allows users to write elegant code expressed in terms of abstract mathematical objects.'
date: 2018-05-24
venue: 'DS-DC Mipro proceedings'
paperurl: 'papers/CP_2018_SlakKosec_Mipro.pdf'
doi: 'http://docs.mipro-proceedings.com/dsdc/dsdc_05_4889.pdf'
citation: 'Slak, J., and Kosec, G. Parallel Coordinate Free Implementation of Local Meshless Method, DS-DC Mipro proceedings, Croatia, Opatija, 24. May 2018.'
share: false
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

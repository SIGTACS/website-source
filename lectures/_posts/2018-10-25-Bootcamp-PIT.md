---
layout: post
categories:
  - lecture
title:  "A Bootcamp on polynomial identity testing"
author: "SIGTACS"
coordinates: KD103, 3 PM 25th Oct 2018
tags: 
---
### Abstract

Polynomial Identity Testing (PIT) is a fundamental problem in theoretical computer science . The problem is about finding an efficient algorithm to test if a given algebraic expression (for example, x^2-y^2=(x+y)(x-y) ) is an identity (LHS=RHS). Equivalently, the problem is to test whether a given algebraic formula computing a multivariate polynomial is identically zero or not. It may seem to be a trivial problem, as we can expand the polynomial, compute all its coefficients and check if they are zero. This is a correct algorithm, but the running time is exponential as there are exponentially many monomials in a generic n-variate degree d polynomial. A simple idea (check if the polynomial is zero at a random point) gives a more efficient (randomized polynomial time) algorithm, but the algorithm may mistakenly output zero for a non zero polynomial. Luckily the probability of error is really small, so this algorithm works in practice.

Can we give a deterministic polynomial time algorithm? There is strong evidence that there exists such an algorithm. Finding a solution would be a major breakthrough as it would solve several problems in computer science.

Last decade has seen continuous progress in this area, several special cases are now solved and strong reduction results are known. In this workshop we will start from the basics and go on till we see a few state of the art results. The prerequisite for understanding the talks is minimal, basic understanding of linear algebra and algorithms should be sufficient.

[Program](/assets/resource/bootcamp-PIT.pdf)

References:
* [Progress on Polynomial Identity Testing - Nitin Saxena](https://www.cse.iitk.ac.in/users/nitin/papers/pit-survey09.pdf)
* [Classifying polynomials and identity testing - Manindra Agarwal and Ramprasad Saptharishi](https://www.ias.ac.in/public/Resources/Other_Publications/Overview/Current_Trends/149-162.pdf)

---
layout: post
categories:
  - talk
title:  " Computing Igusa's local zeta function of univariates in deterministic polynomial-time "
author: " Ashish Dwivedi"
coordinates: 
slides: "2020-07-14-Ashish-Dwivedi.pdf"
link: "https://youtu.be/3OQt2TgOkxw"
tags: 
---
## Abstract

The famous millennium prize problem “The Riemann Hypothesis” is about the zeros of a zeta function known as “Riemann Zeta Function”. In this talk we will talk about another interesting zeta function which counts the number of roots of a polynomial, $f(x_1,\dots,x_n)$ with integer coefficients, reduced mod a prime-power $p^k$, for all k; known as— Igusa’s Local Zeta Function $Z_{f,p}(s)$.

It is a famous result, in analytic number theory, that $Z_{f,p}(s)$ converges to a rational function. We give an elementary proof of this fact for a 1-variable polynomial $f(x)$. Our proof is constructive as it gives an explicit formula for the number of roots of $f(x) \mod{p^k}$. Our proof, when combined with the recent root-counting algorithm of (Dwivedi, Mittal, Saxena, CCC, 2019), yields the first deterministic poly-time algorithm to compute the rational form of $Z_{f,p}(s)$.

This is based on joint work [ANTS 2020](https://www.math.auckland.ac.nz/~sgal018/ANTS/papers/Dwivedi-Saxena.pdf) with Professor Nitin Saxena.
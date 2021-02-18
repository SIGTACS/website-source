---
layout: post
categories:
  - talk
title:  " Optimal Streaming Approximations for all Boolean Max-2CSPs "
author: " Chi-Ning Chou"
fixture: "14-05-2020"
coordinates: 
slides: "2020-05-14-Chi-Ning-Chou.pdf"
link: "https://youtu.be/en_E2J1YDnI"
tags: 
---
## Abstract

Constraint Satisfaction Problem (CSP)is one of the central computational problems studied in complexity theory. In this work, we focus on the streaming model where the input is a sequence of constraints and the goal is to approximate the maximum number of satisfied constraints using space as small as possible.

Unlike the traditional setting, there have been very few results in the streaming model. A recent line of works culminating in [Kapralov-Krachun, STOC 2019]shows that $(1/2+\varepsilon)$-approximation for Max-CUT requires $\Omega(n)$ space while there is a trivial $1/2$-approximation using $O(\log n)$ space. However, the knowledge of the right approximation ratio for other boolean 2CSP in the streaming model remains elusive. Specifically, prior to this work, there is a $2/5$-approximation for Max-DICUT while the hardness side only refutes $1/2$-approximation [Guruswami-Velingker-Velusamy, APPROX-RANDOM 2017].

In this work, we show that, surprisingly, the right approximation ratio for Max-DICUT in the streaming model is $4/9$. Furthermore, we settle down the right approximation ratios for all the boolean 2CSP in the streaming model. The techniques we are using are random samplings and reductions from the distributional boolean hidden matching problem (DBHP).

This is joint work with Santhoshini Velusamy and Sasha Golonev.
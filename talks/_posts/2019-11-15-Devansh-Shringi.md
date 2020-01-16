---
layout: post
categories:
  - talk
title:  "PIT of Depth-4 Constant Top and Bottom Fan-in Circuits"
author: "Devansh Shringi"
coordinates: KD103, 3 PM 16th Nov 2019
tags: 
---
## Abstract

In this talk, we will explore the problem of Polynomial Identity Testing (PIT) which is of finding an algorithm that checks if a given polynomial is zero or not in polynomial time. The problem is central to the field of Algebraic complexity and has known connections to lower bounds, as well as other problems in complexity theory. It has a simple randomized black-box solution but a deterministic algorithm is not known.

We will take a look at the restricted class of circuits of depth-4 constant Top and Bottom Fan-in. Solving the problem for the depth-4 case will imply a solution for the general PIT using depth reduction in [AV08]. The case of constant top Fan in depth-3 has been solved for both white-box [KS07] and black-box [SS13] cases. Thus, this remains the next unsolved case in the field, for which even the white-box solution is not known. We will look at the conjectures in [Gup14] of Sylvester-Gallai type theorems for non-linear polynomials proposed to solve the case, and prove one of the easier conjectures for quadratic polynomials from [Shp18].
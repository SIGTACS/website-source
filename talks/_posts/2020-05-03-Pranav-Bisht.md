---
layout: post
categories:
  - talk
title:  " Poly-time blackbox identity testing for sum of log-variate, constant-width ROABPs "
author: " Pranav Bisht"
fixture: "03-05-2020"
coordinates: 
slides: "2020-05-03-Pranav-Bisht.pdf"
link: "https://youtu.be/2zzfCgi2NkA"
tags: 
---
## Abstract

The talk is based on joint work with Prof. Nitin Saxena. We explore blackbox PIT (Polynomial Identity Testing) problem for the model of "Sum of ROABPs (Read-once oblivious Algebraic Branching Programs)". Recent bootstrapping results motivate us to study log-variate ROABPs. We also restrict the width of ROABP to a constant but study the more general sum-of-ROABPs model. We give the first poly($s$)-time blackbox PIT for sum of constant-many, size-$s$, $O(\log s)$-variate constant-width ROABPs. The
previous best for this model was a quasi-polynomial time which is comparable to brute-force in the log-variate setting. Also, we handle unbounded-many such ROABPs if each ROABP computes a homogeneous polynomial.

Our new techniques comprise-- (1) a ROABP computing a homogeneous polynomial can be made syntactically homogeneous in the same width; and (2) overcome the hurdle of unknown variable order in sum-of-ROABPs in the log-variate setting (over any field).

In the talk, we will begin from scratch with definitions of PIT and various models including ROABPs. Then, we shall discuss the motivations behind this model and its non-triviality. Finally, we will give a brief overview of the PIT algorithms and why they work.

See the paper for more detials: [TR20-042](https://eccc.weizmann.ac.il/report/2020/042/)
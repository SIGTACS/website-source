---
layout: post
categories:
  - talk
title:  "Fault-Tolerant Reachability and Strong-connectivity Structures"
author: "Keerti Choudhary"
coordinates: KD103, 4 PM 7th Oct 2019
slides: "2019-10-7-Keerti-Choudhary.pdf"
tags: 
---
## Abstract

Reachability and strong-connectivity are some of the fundamental graph problems. In the static setting, both problems can be solved in O(m+n) time for any directed graph G with n vertices and m edges. However, most real-world networks are prone to failures. The failures are transient and occur for a small duration of time. Under such a setting, we would like to preprocess the graph to compute data-structures that can achieve robustness by being functional even after the occurrence of failures. In recent years, researchers have studied various questions pertaining to connectivity, distances, routing, min-cuts, etc. in the domain of fault tolerance networks.

In this talk, the speaker will discuss the following questions:
1. Can we compute a reachability tree in just linear time, after the occurrence of a small number of failures?
2. How fast can we compute the strongly connected components, again on the occurrence of failures?
3. Does there exist a sparse certificate for these structures that remains valid even after a bounded number of failures?

The solutions to these problems employ extremely basic tools like max-flows, min-cuts, and heavy-path-decomposition. 

[Slides](/assets/resource/talk_iitk_keerti_7oct.pdf)

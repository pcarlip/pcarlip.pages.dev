---
title: "Oceanography"
menu: main
weight: 20
layout: "simple"
---

### Turbulence and Structure Functions

In general, I'm interested in the connections between our analytical and numerical 
understanding of the ocean, focusing on ocean mixing and turbulence. 
My goal is to improve our 
understanding of how energy and other flow properties move between scales. This is 
important for ensuring the accuracy of large-scale ocean models, as they can't directly
simulate turbulence at smaller scales. Many of my current research questions are 
related to structure functions, which 
connect energy dissipation and related variables to the differences between flow 
variables (such as velocity and advection) at pairs of grid points at a 
constant distance. These methods have
a long history in isotropic flows, but there is substantial work remaining to develop 
and improve them for flow fields with directional dependence.

I am currently working on taking transformation methods developed for 2-dimensional flows
(as vertical motion is typically very small at large scales in the ocean) and extending 
them to three dimensions. I am also developing more efficient methods of calculating 
structure functions, including through the use of vectorized operations on CUDA GPUs.
In addition, I have begun working on the scaling properties of 
[Oceananigans](https://github.com/CliMA/Oceananigans.jl) across multiple GPUs, which 
can allow for larger, faster ocean simulations than a single GPU can provide, while
using less resources than a comparable simulation on a large CPU cluster.
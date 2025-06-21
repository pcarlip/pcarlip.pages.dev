---
title: "Cell Signaling"
menu: main
weight: 30
layout: "simple"
---

### Differential Equation Models of Signaling Networks

{{<figure
    src="images/raf-diagram.png"
    alt="A chemical diagram, representing different states of Raf and 14-3-3 through the positions of colored blobs. Arrows labeled with reaction constant names connect different states."
    class="center"
    caption="A cartoon of some of the protein-protein interactions involved in activating Raf.">}}


Immediately before joining OSU, I worked as a postgraduate associate in the
[Stites lab](https://www.stiteslab.org/) at the Yale School of
Medicine. I focused on modeling cell signaling networks,
particularly aspects of the Ras-MAPK pathway. I use ODE and equilibrium
models, primarily written in Python and Matlab, as well as rule-based models
with tools such as pysb and BioNetGen.

I focused on the activation mechanism of the Raf protein.
Like many of the proteins in the MAPK pathway, Raf is involved in promoting
cell proliferation and is frequently mutated in cancer. For instance, around 50% of
melanomas have mutations in BRaf, one of three Raf proteins. 
Raf activation has a large number of known steps, but the order and importance of many of 
the steps is unclear. In my preprint 
[Analysis of the Modulation of RAF Signaling by 14-3-3 Proteins](https://www.biorxiv.org/content/10.1101/2024.07.16.603736v1) (currently under review), 
I argue that the binding between Raf and 14-3-3 (a protein which can keep Raf either active
or inactive depending on its binding configuration) can be approximated as a single binding
event rather than modeling two distinct steps of binding. This can be shown by comparing 
the results of a prior transfection experiment (what actually happens when 14-3-3 is added)
to the derivatives of the solution to an equilibrium model (what happens when the 14-3-3
parameter is increased.)

I also worked on several Ras-related projects. Ras, the protein immediately prior to Raf
in the MAPK pathway, is typically cited as mutated in 30% of cancers, including 90% of 
pancreatic cancer and around half of colorectal cancer 
(with [caveats](https://aacrjournals.org/cancerres/article/72/10/2457/575860/A-Comprehensive-Survey-of-Ras-Mutations-in) 
about [normalization](https://doi.org/10.1038/s41467-021-26213-y)).
I modeled three proposed synthetic modifications to Ras and proteins which interact with 
it, to determine the necessary characteristics of the modified proteins to e.g., 
selectively degrade mutant Ras or to supress prolonged activation without affecting 
shorter bursts of activity.
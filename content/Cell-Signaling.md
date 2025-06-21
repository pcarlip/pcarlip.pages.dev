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


My work immediately before joining OSU was as a postgraduate associate in the
[Stites lab](https://www.stiteslab.org/) at the Yale School of
Medicine. My work there has focused on modeling cell signaling networks,
particularly aspects of the Ras-MAPK pathway. I use ODE and equilibrium
models, primarily written in Python and Matlab, as well as rule-based models
with tools such as pysb and BioNetGen.

I focused on the activation mechanism of the Raf protein.
Like many of the proteins in the MAPK pathway, Raf is involved in promoting
cell proliferation and is frequently mutated in cancer. Around 50% of
melanomas have BRaf mutations, for instance. Raf activation has a large number
of known steps, but the order and importance of many of the steps is unclear.
In my preprint 
[Analysis of the Modulation of RAF Signaling by 14-3-3 Proteins](https://www.biorxiv.org/content/10.1101/2024.07.16.603736v1), 
I show that approximating the interactions of Raf and 14-3-3 as a single binding event 
is likely valid, based on an equilibrium model and the results of prior transfection 
experiments.
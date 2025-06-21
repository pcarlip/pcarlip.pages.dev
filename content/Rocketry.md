---
title: "Rocketry"
menu: main
weight: 50
layout: "simple"
---

{{<figure
    src="images/fin mesh.png"
    alt="A grid of colorful triangles, which become much smaller in an area shaped like rocket fins."
    class="right"
    caption="CFD mesh around rocket fins, used for aerodynamics simulations.">}}

## UCSD Rocket Propulsion Lab
I was a member of
[UCSD Rocket Propulsion Lab](https://www.rocketproplab.org/)
for all 4 of my years at UCSD. During my first year, I took part in the New
Member Project, learning the basic principles of rocketry by designing a
small, solid-propellant model rocket. After that, I joined the Analysis team,
and after about a year became the Lead Analysis Engineer.

My work on the analysis team focused on computational fluid dynamics
simulations, generally using ANSYS Fluent. For some specific projects, we used
other software such as OpenRocket (for center of pressure analysis and flight
simulations) and GT Suite (for pipe flow approximations in cases where
standard CFD was too computationally expensive). 

One major project I worked on
was simulating heat transfer from the combustion chamber to the walls and into
the regenerative cooling channels, working with the Propulsion team to iterate
through cooling channel designs. We didn't have the computational resources to simulate 
both the combustion and cooling channels at once, so I found the hat gas properties inside
the engine and used empirical heat transfer results to find the appropriate heat flux
through the engine walls.
I also worked to ensure that the fin geometry
provided enough drag at the right location to keep the center of pressure
behind the center of mass, ensuring the rocket's stability, while still
maximizing the apogee.

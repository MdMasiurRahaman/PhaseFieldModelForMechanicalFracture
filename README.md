# Phase-field model for mechanical fracture

An open-source implementation of a phase-field model for brittle fracture using a recently developed finite-element toolbox, Gridap in Julia, is provided. This work 
exploits the advantages of both the phase-field model and Gridap toolbox for simulating fracture in brittle materials. On one hand, the use of the phase-field model, 
which is a continuum approach and uses a diffuse representation of sharp cracks, enables the proposed implementation to overcome such well-known drawbacks of the discrete approach 
for predicting complex crack paths as the need for re-meshing, enrichment of finite-element shape functions, and an explicit tracking of the crack surfaces. On the other hand,
the use of Gridap makes the proposed implementation very compact and user-friendly that requires low memory usage, and provides a high degree of flexibility to the users in defining
weak forms of partial differential equations. Tests on a single-edge notched plate under tension, an L-shaped panel, a notched plate with a hole, a notched beam under symmetric
three-point bending and a notched beam with three holes under asymmetric three-point bending are considered to demonstrate how the proposed Gridap-based phase-field Julia code 
can be used to simulate fracture in brittle materials.

# See the details using the link given below: 

https://journals.sagepub.com/doi/full/10.1177/10812865211071088

# Cite this article: 

@article{rahaman2022open,
  title={An open-source implementation of a phase-field model for brittle fracture using Gridap in Julia},
  author={Rahaman, Mohammad Masiur},
  journal={Mathematics and Mechanics of Solids},
  volume={27},
  number={11},
  pages={2404--2427},
  year={2022},
  publisher={SAGE Publications Sage UK: London, England}
}


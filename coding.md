---
layout: default
title: Coding
---

In this section I enlist all of the libraries I have worked on so far, and maybe motivate you to used them for your own problems! Should you be interested, let me know :). 

1. RegFem

Library used to solve image registration problem, it supports H<sup>1</sup> and elastic regularization with L<sup>2</sup> error, but it can be very easily extended to other models. It supports Dirichlet and Neumann boundary conditions, in both Primal and Mixed formulations, plus many standard pairs of reference and template images to test the proposed methodologies. It is based in FEniCS.

2. Poromechanics

This library deals with the mathematical modeling of cardiac poromechanics, with special emphasis in a multi-compartment formulation of cardiac poromechanics. It contains other features, such as a linearized poroelastic model and inf-sup constant estimation. 

3. Iterative methods for poroelasticity

This library presents a huge range of options for testing iterative splitting schemes for linear poroelasticity. It supports 2-way and 3-way splitting strategies for fixed-stress and undrained approaches, together with Anderson acceleration and optimal mixing strategies through Aitken acceleration to improve Cahouet-Chabard preconditioners for this models. 
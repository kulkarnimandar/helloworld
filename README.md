# helloworld
Learning how to use github.

Here I am going to write what needs to be done in SU2 to implement CSA:

1) Understand how vanLeer 1st order upwind scheme is implemented and create a parallel file for the derivatives of those equations.

2) Understand how the boundary residual is treated and create a similar derivative version for CSA

3) Understand how the implicit solver is implemented and if the Jacobian is w.r.t. the primitive or conserved variables

4) In the CSA time stepping procedure, understand how to use the primary Jacobian instead of calculating it at each time step.

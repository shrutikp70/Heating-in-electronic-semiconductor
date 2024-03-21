<h1>Problem Description:</h1>

This repository presents a solution to a problem involving the application of finite difference schemes to model heating in electronic semiconductor circuits, focusing on the Fourier heat conduction equation in 1D space.

<h3>Task:</h3>

Q1: Problem on Finite Difference Scheme: Heating in Electronic Semiconductor Circuits

<b>Problem Formulation:</b>

The Fourier heat conduction equation in 1D space is given.
Temperature-dependent thermal conductivity 𝑘(𝑇) of silver is considered.
Density (𝜌) and specific heat capacity (𝑐𝑝) of silver are assumed constant.
Initial and boundary conditions are specified.

<b>Objectives:</b>

<b>(a) Temperature Profile Calculation:</b>

Calculate temperature profiles at specific locations using explicit and implicit finite difference numerical schemes, as well as the Crank-Nicolson method.
Perform calculations for at least 5 cycles of 𝜋.

<b>(b) Von-Neumann Stability Criterion:</b>

Ensure adherence to the Von-Neumann stability criterion in the explicit scheme.
Investigate the behavior of the solution when the stability criterion is exceeded.
Compare results between explicit and implicit schemes for solution accuracy.

<b>(c) Computational Efficiency:</b>

Vary the number of internal grid points and estimate the computational time needed to solve the tri-diagonal matrix using classical matrix inversion techniques versus the Thomas algorithm.

<b>(d) Temperature Variation Analysis:</b>

Plot temperature profiles at 𝜕 = 0 and length-averaged temperature for different values of 𝜋.
Determine any phase differences observed in the average temperature response.
Determine the critical value of 𝜋 beyond which temperature variations at the other end are minimal and analyze its dependence on 𝛼.

<b>Instructions:</b>

Clone this repository to your local machine.

Execute the provided code files to implement finite difference schemes and perform calculations.

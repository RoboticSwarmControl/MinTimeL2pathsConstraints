# Minimum-Time Planar Path with $L_2$ Velocity and Acceleration Limits and Two Constant Control Inputs

Optimal control solutions are often formulated using $L_\infty$ constraints, even for systems better modeled with $L_2$ constraints.
Given starting and ending positions and velocities, $L_2$ bounds on the acceleration and velocity, and the restriction to no more than two, constant control inputs, this paper provides routines to compute the minimal-time path. Closed form solutions are provided for reaching a position in minimum time with and without a velocity bound, and for stopping at the goal position.
 A numeric solver is used to reach a goal position and velocity with no more than two constant control inputs. If a coasting phase at the terminal velocity is needed, this requires solving a non-linear equation with a single parameter.

 This repository contains a pdf appendix that provides the equations too long for the conference paper.
 In the folder Code, there are three (Mathematica)[https://www.wolfram.com/mathematica/] files:

1. MinimumTimeL2velandaccelConstraintsV14.nb -- full code for mathematics of shortest path
2. PaperFiguresShowingPt1WithArrows.nb -- generates figures in the paper
3. ReachPointFastest.nb -- code for reaching a point (without stopping or matching a velocity)

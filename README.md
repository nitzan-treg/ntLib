# ntLib
This is an open source library of Houdini HDA's (Houdini Digital Assets)
It includes tools for simulating dynamics, procedural generation and generative art.

## About 
This is my way to give back to the community, I'm sharing my development with you so we can all learn from it. A lot of the tools are discovered through RnD and study of math

I welcome you to join the adventure and share your own expirmients

* Discord: https://discord.gg/z5DpSC9U
* Youtube: https://www.youtube.com/channel/UCe6hY7_rXJ-iQrdDT0ZiyRw
* Website: https://www.nitzan-tregerman.com/

# Tools



## Extrude Subidivision

This node takes an input polygon surface, and divides each face to create a “Extrude shaped” surface. It is similar to the Subdivide node in that it divides up all or part of a surface allowing you to increase areas of local detail.

Explainer video here:
https://vimeo.com/775089386

<img height="200" src="Images/Extrude_subdivision.gif">

## Velocity From Curves

A utility tool that generates a velocity field from a curve, allows to control the following forces:

* Follow force - pushing along the curve tangent
* Suction force - push velocity toward nearest point on the curve
* Orbit force - push velocity around the curve
* Curl Noise - adds Curl noise to the velocity

<img height="200" src="Images/velocity_from_curve.gif">

# Upcoming Tools

### 2D Smoke Solver (Beta)
bla bla bla bla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla bla

<img height="200" src="Images/smoke_solver.gif">

### SDF Growth Solver (Beta)

bla bla bla bla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla bla

<img height="200" src="Images/sdf_growth.gif">

### Infection Solver (Alpha)

### Super Diamond (Beta)

bla bla bla bla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla blabla bla bla

<img height="200" src="Images/super_diamond.gif">

### Points from Curves (Beta)
an expiriment to test the limits of VEX.
I attempted to make everything into a single wrangler

### DOP wrangler (Beta)
the whole idea of this node is to have a solver only execute a single wrangle snippit every solved frame

### 3D Chlandi Noise (Beta)
based on the following article
I tried to copy the formula and generate chlandi noise from it
# Fracture_network-mesh
This repository contains the initial mesh file for the numerical example: "Example 3: Flow through a 2D porous media with fracture network" of the work:

S. Caucao, G.N. Gatica, and L.F. Gatica: A Banach spaces-based mixed finite element method for the
stationary convective Brinkman-Forchheimer problem. (2023).

Available in: <a href="" target="_blank">update</a>


To load the mesh in FreeFem++, use the code:

mesh Th = readmesh("Fracture_network-mesh.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

22: right and top boundaries

4: left boundary

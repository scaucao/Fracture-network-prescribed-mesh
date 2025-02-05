# Fracture_network-prescribed-mesh
This repository contains the mesh file for the numerical example "Example 3: Flow through a 2D porous media with fracture network" from the paper:

S. Caucao, G.N. Gatica, and L.F. Gatica: A Banach spaces-based mixed finite element method for the stationary convective Brinkman-Forchheimer problem. Calcolo, vol. 60, 4, article: 51, (2023). 
Available in: <a href="https://doi.org/10.1007/s10092-023-00544-2" target="_blank">10.1007/s10092-023-00544-2</a>

To load the mesh in FreeFEM, use the code:

mesh Th = readmesh("Fracture_network-mesh.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

22: right and top boundaries

4: left boundary

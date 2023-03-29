# Fracture_network-prescribed-mesh
This repository contains the initial mesh file for the numerical example: "Example 3: Flow through a 2D porous media with fracture network" of the work:

S. Caucao, G.N. Gatica, and L.F. Gatica: A Banach spaces-based mixed finite element method for the stationary convective Brinkman-Forchheimer problem. Preprint 2023-10, Centro de Investigación en Ingeniería Matemática (CI²MA), Universidad de Concepción, (2023). 

Available in: <a href="https://ci2ma.udec.cl/publicaciones/prepublicaciones/prepublicacionen.php?id=516" target="_blank">https://ci2ma.udec.cl/publicaciones/prepublicaciones/prepublicacionen.php?id=516</a>

To load the mesh in FreeFem++, use the code:

mesh Th = readmesh("Fracture_network-mesh.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

22: right and top boundaries

4: left boundary

# Flow around cylinder using OpenFOAM
This repo contains the files required to run a flow around a cylinder at Re = 100. The goal of this project is to run the simulation in openFOAM v8 and use this information to compute the modal structures of the flow using POD and DMD, which can be found [here](https://github.com/smkondo/oscillatingcylinder).
To run the simulation first create the mesh using blockMesh and run using simpleFoam, a steady-state solver in OpenFoam.

The resulting animation of the flow is also attached in the repo as "velocity.ogv" The downloaded video can be viewed on google chrome.

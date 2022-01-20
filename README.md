In this solver, the energy equation has been added to the icoFoam solver in OpenFOAM 6. It can be used to simulate the incompressible, laminar flow of Newtonian fluids regarding heat transfer occurred. The programming language used is C++.

You can easily compile this solver in your user directory by opening a new terminal in the directory and typing the below commands :
./wclean
./wmake

Furthermore, some steps need to be taken to validate and test the extended solver. You can modify the Cavity test case by creating a volScalarField ( T ) in the directory zero and defining boundary conditions the initial temperature value inside the cavity. Then, it is needed to create a diffusionProperties dictionary in the constant directory and define the diffusivity (DT) parameter. Finally, the discretization method and how the temperature matrix can be solved should be addressed correctly in system/fvScheme and fvSolution.

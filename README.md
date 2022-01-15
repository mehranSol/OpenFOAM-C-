In this solver, the energy equation has been added to the icoFoam solver in OpenFOAM 6. It can be used to simulate incompressible, laminar flow of Newtonian fluids. 
Inside the test case :
Suppose you want to simulate a Lid-Driven cavity with regard to heat transfer occurred, you need to create a volScalarField ( T ) in the directory zero and define boundary condtions and the initial value of temperature inside the cavity. Then, create a diffusionProperties dictionary in constant directory and define diffusivity (DT) as it has been used in energy equation.

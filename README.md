In this solver, energy equation has been added to icoFoam solver in OpenFOAM 6. It can be used to simulate incompressible, laminar flow of Newtonian fluids. 
Inside the test case :
If you want to simulate lid-Driven cavity with regard to heat transfer, you need to creat a volScalarField ( T ) in directory zero and define boundary condtions and initial value of temperature inside the cavity. Then, creat a diffusionProperties in constant directory and define diffusivity (DT) as it is used in energy equation.

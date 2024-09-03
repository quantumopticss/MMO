# MMO
COMSOL simulation of force between two magnets and solid mechanics about plate
Realted to Magnetic Mechanical Oscillator  (A problem in IYPT 2023)

1. In Ke:
We use "solid mechanics" modele of Comsol. A load
F was applied at the top, and we used a steady-state solver to calculate the displacement
at the top under the load F , comparing it with the theoretical value.
We considered the movable part length of the plate L and the load F as two
independent variables and used the ”parametric sweep” function to solve our model:
A. Set F to 0.15N and sweep the plate length L in the range from 4 to 15cm.
B. Set L to 10.5cm and sweep the load F in the range from 0 to 0.15N 

2. In Fm:
We use "Magnetic Fields, No Currents" module of COMSOL. Using the built-in
"Force Calculation" function, we calculated the interaction force Fm between the two
magnets. We solved this using the steady-state solver and scanned the variation of Fm
with d.

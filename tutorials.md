# Tutorials
# T1 measurement 
## Theoretical background
Longitudinal relaxation times are usually measured using the inversion recovery experiment.
In this experiment the equilibrium magnetization is first inverted by applying a 180º pulse. After the
inversion the magnetization relax longitudinally during a delay _d_ trying to return to its equilibrium state. 
The amount of longitudinal magnetization $$ M_z(t) $$ after delay _d_ can be read by appling a 90º pulse which converts it 
to observavel transversal magnetization.
The depdendence of longitudinal magnetization as a function of delay _d_ is described by the following equation 

$$ M_z(d) = M_0 ( 1 -2e^{-d/T_1} ) $$

Fitting of experimental datay for an array of delay times _d_ will provide the T1 of a particular spin or spin group.

## Performing T1 experiments in the Q-one 300 MHz spectrometer
From here we will illustrate how to measure 1H T1 relaxation times in the Q-One 300 MHz spectrometer as exemplified in a 
D<sub>2</sub>O saturated solution of zidovudine, an antiretroviral drug.
### Preparative steps
After insertion of the sample in the spectrometer check the tuning in the proton channel and tune the probe if necessary.
Lock and shim the sample as described here and record a 1H experiment. Callibrate the 1H 90º pulse.
### Inversion recovery experiment
Create a new experiment in the window, and choose the template . Open the  p1 proton pulse to the value previously determined which should be 
around. Important: high power pulses should have lenghts of 10-20 us. Application of high power long pulses can damage the NMR probe. 
Adjust the spectral window and O1 values to the desired values (xxx and xxx parameters) To ensure full recovery of the signals the recycling time,
which is the sum of relaxation delay and acquistio times must be larger than $ 5T_1$. The default values in the xxx template are () and () . 
To be on the safe side and if nothing is know about the possible T_1 values a d1 value of 30 s can be employed.


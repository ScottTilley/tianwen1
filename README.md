# tianwen1
Doppler data from TIANWEN-1

Daniel Estévez kindly provided a GMAT and template Jupyter-Notebook scripts to allow for the comparison of TIANWEN-1's received Doppler data to that generated by the state vector modeling with GMAT. 

To run the GMAT script you'll need GMAT2020. It will print a warning about the simulation date being outside the range of EOP parameters. This is not very important, but it can be easily fixed by downloading an updated EOP parameter file from

http://hpiers.obspm.fr/iers/series/opa/eopc04_IAU2000

and placing it in

data/planetary_coeff/eopc04_08.62-now

inside the GMAT installation folder.

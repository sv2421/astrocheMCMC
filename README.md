# astrocheMCMC
Astrochemical parameter estimation for dark molecular clouds.

Eventual requirements: Python 2.7, astrochem, numpy, emcee, matplotlib, 
corner.

Currently seeing if we're going to use Astrochem or its python wrapper.
Of course we would like to use the python wrapper, but our first bench-
marking results suggest that the wrapper isn't giving the right results.

UPDATE: 1/24/17, the wrapper is working, we just didn't know the times
were in terms of seconds on the solver.

Our goal is to use astrochem output and observed abundances in TMC-1 to
infer input parameters like temperature, density, CRIR, Av, and age.

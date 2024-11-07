# CHBE-481
Modeling a bioreactor growing yeast through three stages - an initial batch fermentation, a fed-batch fermentation with constant glucose concentration, and a fed-batch fermentation with a constant oxygen uptake rate. Made for UBC Capstone course + CHBE 481.

Note: many of the ODE's are sensitive to initial conditions, so if you get weird graphs when changing S_floor or initial biomass concentration, try playing around with the initial guess in fsolve in the problematic regimes.

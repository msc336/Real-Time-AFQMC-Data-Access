# Real-Time-AFQMC-Data-Access


This repository contains data from the article titled "Real-time dynamics of strongly correlated fermions with auxiliary field quantum Monte Carlo" by M. S. Church and B. Rubenstein.

The data is organized in 6 directories labeled by the Model #, with # = 1,...,6

The survival probabilities plotted in Fig.'s 2-7 of the above manuscript are divided up into each of the six directories according to the Model #.

The Model 6 directory also contains the charge densities appearing in Fig. 10.

Each data file contains a single column of data: the value of the survival probability, charge density, or standard deviation at each time step. The first row corresponds to the time t = 0, and the time increases by dt = 0.05 with each successive row.

Each file is labeled according to the Model #, the computational method, and the value of the repulsive interaction U. The label 'SD' is used to indicate a file containing the standard deviation at each time step. Finally, the charge density files are additionally labeled by the lattice site number.

Please forward any questions via email to matthew_church@brown.edu

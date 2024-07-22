For more information please read the Report.

This project was developed during the course "Mathematical Models for Biomedicine" at Politecnico di Torino, in which I have reproduced the results obtained in the paper "Agent-Based and Continuum Models for Spatial Dynamics of Infection by Oncolytic Viruses" by Morselli et al.

The results of the PDE solution are stored in the folder "./<Simulations|Figures>/results". I did not save the figures of all times, only the numpy array, to then plot and save the images with additional information using the notebook Results.ipynb (used to create the plots in the Report).

Information on the simulations:
SIM 1
2D random movement, pop_unit = 2 for uninfected and infected too. Using pop_unit != 1 for infected is not a good approximation, this simulation is not displayed in the report.

SIM 2, 3, 4
2D random movement (delta=0.1 tau=0.2) and reference parameters

SIM 5, 6, 7, 8, 9
1D random movement (delta=0.05 tau=0.2) and reference parameters

SIM 10, 11, 12
1D pressure walk and reference parameters

SIM 13, 14
2D pressure walk and reference parameters

SIM 15
2D pressure walk Ri=Ru

SIM 16
2D pressure walk Ri=Ru, q=q/5, beta(q,p) optimal given the changed q

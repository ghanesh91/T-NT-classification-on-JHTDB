# T-NT-classification-on-JHTDB
Apply SOM method to identify T-NT interface on JHTDB's transitional turbulent boundary layer. The code was used in JHU's Statistical Learning for Engineers course during Fall 2019.
Read Wu et al (2019) "Application of a self-organizing map to identify the turbulent-boundary-layer interface in a transitional flow" to know in detail about the SOM method.

How to run the scripts?
1. Run the script generate_training_data.ipynb - This code downloads the velocity and velocity gradient data at specified number of grid points from the JHTDB's Transitional turbulent boundary layer data. The data is stored in MATLAB's ".mat" file format.
2. Run the script SOM_training.ipynb - This script does the SOM training and gives the weights associated with the input vector components. These weights can be used to perform T/NT classification on a given test data.

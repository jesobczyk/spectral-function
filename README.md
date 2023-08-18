# Spectral function of oxygen 16 from coupled-cluster theory

Spectral function is tabularized separately for protons and neutrons. Files ending in "_low" and "_high" correspond to the uncertainty of the spectral reconstruction.



# How to read SF files

1st line:

33 **(number of energy bins)** 56 **(number of grid points in momentum)**

2nd line:

2.500 **(minimum value of energy)** 0 **(minimum value of momentum)**

3rd line:

118.000 **(maximal value of energy)** 560 **(maximal value of momentum)**


### Next, the values of SF are printed out in the following format:



for i in range (number of grid points in momentum):

  **p_i**

  for j in range (number of energy bins):

  **E_j , S(p_i,E_j)**


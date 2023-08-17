# MrFIT_loop
loop to write MrFIT input files for all peak data in a directory
inputs:
peakdatafolder - path to folder where all peak data files are located
r1, r2 - min and max radii to seach between (nm)
m01, m02 - the min and max of the m0 term in a Cauchy expression for the realpart of the refractive index
n1, n2 - min an dmax mode orders to search

modify the files pathes for where the parameters.in file should be and when the MrFIT exicutible file is located.

Will loop through all the peak data files and return the typical MrFIT outputs for each dataset. 

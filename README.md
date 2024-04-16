# Valvetracking
Generates a dynamic slice prescription based on long-axis cine

This Matlab code comes with a data structure 'SET' in the Data folder.
This is the output of Segment software after using "TVnet" plugin on RV 2ch and 4ch cines (both can be downloaded, as described in the code). 

SET is loaded by MainScriptExportValvetrackingSlice.m the main script.
The mainscript uses multiple functions included here. 
The output provides the center of the valve and the normal to the valve plane in physical coordinates of the scanner. 

The output folder contains the results of the code, namely some figures as visualization tools and  a file for use on the scanner. 

for questions contact Jerome Lamy at lamy.jerome@proton.me or Dana Peters at dana.peters@yale.edu



### NBOanalysis.py 
generates NBO descriptors for any connectivity of interest form all .log files (Gaussian output files) in the directory (example: Azidobocphenylalanine.log). The connectivity of interest (here Azide with C, N1, N2, N3) is detailed in a Excel table with the atom numbers associated with each atom (columns) in a given functional group for each molecule (rows) (example: Atom Labels.xlsx).
![image](https://user-images.githubusercontent.com/119889793/206613969-f36a85e1-5029-4334-b2cb-269a0056bf2d.png)
The output is a table with every bonding, anti-bonding and non-bonding orbital localized between the specified atoms (example: NBO analysis.xlsx). 
For expanding the script to other functionalities, the columns should be modified. The directory needs to feature the same number of .log files (in the same order) as there are rows in the input table. A naming scheme starting with numbers e.g. 001_XXX.log is recommended. 

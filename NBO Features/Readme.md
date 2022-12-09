### NBOanalysis.py 
generates NBO descriptors for any connectivity of interest form all .log files (Gaussian output files) in the directory (example: Azidobocphenylalanine.log). 
![image](https://user-images.githubusercontent.com/119889793/206614238-0faa6d8e-d709-4982-992e-7183f1d516bf.png)
The connectivity of interest (here Azide with C, N1, N2, N3) is detailed in a Excel table with the atom numbers associated with each atom (columns) in a given functional group for each molecule (rows) (example: Atom Labels.xlsx).
![image](https://user-images.githubusercontent.com/119889793/206614462-90191469-e336-4c22-92d6-0008368b8b1c.png)
The output is a table with every bonding, anti-bonding and non-bonding orbital localized between the specified atoms (example: NBO analysis.xlsx). 
![image](https://user-images.githubusercontent.com/119889793/206614388-a5cdf2e1-9b66-44c3-a217-d1601dab2b53.png)
For expanding the script to other functionalities, the columns should be modified. The directory needs to feature the same number of .log files (in the same order) as there are rows in the input table. A naming scheme starting with numbers e.g. 001_XXX.log is recommended. 

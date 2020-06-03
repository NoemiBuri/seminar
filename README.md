# 2019-end-member-mixing-model
### Python 3.7.2, JetBrains PyCharm Community Edition 2018.3.5
This project is part of my master thesis “Abflussseparation mittels stabiler Isotopen - Bestimmung der Wasserherkunft nach Regen, Schnee- und Gletscherschmelze in drei alpinen Einzugsgebieten” (hydrological separation with stable isotopes- determination of the water origin into rain, snow- and glacier melt in three alpine catchments). The master thesis is embedded in a research project of the hydropower company Kraftwerke Oberhasli AG and the University of Bern.
Further information about the background of the script is available in the **Report_ EMMA.pdf**.
Author: Noemi Buri, noemi.buri@students.unibe.ch, University of Bern, Seminar Geodata analysis and modelling 2019

## Goal
The goal of this script is to control a set of data on its suitability for doing an end-member-mixing-analysis (EMMA). Therefore, the mixing triangle is shown, and the user can check, if the investigated sample is within the triangle. If this is the case the percentual amount of the three different water origins is given. Further information about the EMMA is given in the Report_EMMA.pdf. Vector calculations are used to solve the EMMA.

## Workflow
In the following part the workflow of the script is described.
### 1. import
Firstly, the packages numpy, math, sympy and matholpot.lib.pyplot are installed.
### 2. read data from user
Here the user is gettin asked for his import data. 
The script is based on vector calculations. 
auteilen in a b und c 
x und y  information pro komponenten
a besteht aus ax und ay etc.





If you feel more comfortable to import your data with a csv-file you can use the following code:

x=np.loadtxt(r"C:\--insert file path --\test.csv", skiprows=1, dtype=float, delimiter=";")

a=x[0,:]

b=x[1,:]

c=x[2,:]

p=x[3,:]

### 3. define triangle

### 4. triangle calculations

### 5. plot

## Output


# 2019-end-member-mixing-model
### Python 3.7.2, JetBrains PyCharm Community Edition 2018.3.5
This project is part of my master thesis “Abflussseparation mittels stabiler Isotopen - Bestimmung der Wasserherkunft nach Regen, Schnee- und Gletscherschmelze in drei alpinen Einzugsgebieten” (hydrological separation with stable isotopes- determination of the water origin into rain, snow- and glacier melt in three alpine catchments). The master thesis is embedded in a research project of the hydropower company Kraftwerke Oberhasli AG and the University of Bern.
Further information about the background of the script is available in the #Report_ EMMA.pdf.
Author: Noemi Buri, noemi.buri@students.unibe.ch, University of Bern, Seminar Geodata analysis and modelling 2019

## Goal
what is EMMA
use of it (really short, more in pdf)

## Workflow

### 1. import

### 2. read data from user

With following code, it is possible to import the data from a csv-file:

x=np.loadtxt(r"C:\--insert file path --\test.csv", skiprows=1, dtype=float, delimiter=";")

a=x[0,:]

b=x[1,:]

c=x[2,:]

p=x[3,:]

### 3. define triangle

### 4. triangle calculations

### 5. plot

## Output


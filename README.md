# semiconductors
Performing prediction and Inference tasks on Semiconductors data
The data set was originally from from the Superconducting Material Database
maintained by Japan's National Institute for Materials Science(NIMS) and pre-
possessed by Kam. It contains 21,263 material records, each of which have 82
columns: 81 columns corresponding to the features extracted and the last 1 col-
umn of the observed Tc values. Among those 81 columns, the rst column is the
number of elements in the material, the rest 80 columns are features extracted
from 8 properties (each property has 10 features). Detailed data preparation
process can be found in.

Dataset: train.csv

train.csv can be used to train and validate prediction models and build a description
(21,263 material records). Each record consists of 82 columns, contain-
ing number of elements (column 1), features extracted from 8 properties
(columns 2-81) and the critical temperature (column 82). 

Following tasks are being perfomed:
1. Perform the detailed EDA and selecting features
2. Build few models and compare them
3. Analyzing and Interpreting the results
4. Providing the statistical reasons for the results.

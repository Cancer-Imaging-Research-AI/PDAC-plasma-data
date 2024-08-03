# PDAC-plasma-data
This repository contains **supplementary data** for the article:
### Artificial Neural Network Detection of Pancreatic Cancer from 1H MR Spectral Patterns of Plasma Metabolites

Meiyappan Solaiyappan, Santosh Kumar Bharti, Raj Kumar Sharma, Mohamad Dbouk, Wasay Nizam, Malcolm V. Brock, Michael G. Goggins, Zaver M. Bhujwalla

Submitted to **Nature Communications Medicine**

The MR spectral data, acquired using the ZGPR sequence, used for the sole purpose of training and evaluating blinded-test plasma samples is provided under **JHU Academic Software License Agreement** (document included in the repository).

The data is provided as a MATLAB data structure with self-explanatory variable names and consists of binned spectral data matrix acquired from the plasma samples belonging to normal, disease and malignant groups. The three groups (normal, disease, and malignant) can be identified by their respective class-ids: 1,2,and 3.

The file 'trainingspectra.mat' contains spectral data for the training samples used in the study (58 normal, 53 disease and 59 malignant)

The file 'blindedtestspectra.mat' contains spectral data for the blinded-test samples used in the study (19 normal, 10 disease, 16 malignant).



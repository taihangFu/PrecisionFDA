# PrecisionFDA NCI-CPTAC Multi-omics Enabled Sample Mislabeling Correction

## Aim 
Human sample labeling or annotation errors could arise during sample transferring, sample
tracking, large-scale data generation, and data sharing/management. There is a pressing need to
have computational programs to automatically screen for and to correct such incorrect sample
labels or annotations. 

## Background 
This is the US FDA challenge, which will be released on September 24, 2018
(https://precision.fda.gov/mislabeling). In this project, we will be focusing only on the “Stage one”
part of the challenge. Given (1) clinical and (2) proteomic data for both
training and test set. 

The aim is to identify and correct mislabels in the test dataset. For
details please the description paper here: https://www.nature.com/articles/s41591-018-0180-
x.pdf.


## Summary of key aspects:
* Required outputs:
  1. Probability of each sample been mislabelled; and
  2. A predicted list of mislabelled samples from training and test dataset, respectively.
* Evaluations:
  1. Compare to the ground truth in training data, and test data (if such information is provided on the FDA website later on).
  2. Benchmark the prediction accuracy (consider class imbalance etc.).
* Additional outputs:
  1. All other visual analytic results.
  2. All other tables of results that are useful.

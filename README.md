# 1000G-Compression-Analysis
Final project for BIO514 Data Structures and Algorithms

1. Context
The 1000 Genomes Project is the largest public catalogue of human variation and genotype data. These data were collected between 2008 and 2015, with the goal of identifying genetic variants with sufficient frequency (at least 1% in the populations studied). Our data was a subset of the full 1000 Genomes data, containing only a single chromosome. Specifically, we had around 800000 SNPs from 1094 subjects (2188 haplotypes).

2. Objective
Our task for these data was three-fold: first, we compress the dataset by taking advantage of the data structure (i.e., sparsity). Second, we identify the degree to which there exist distinct subpopulations within the data using Principal Component Analysis (PCA). Third, we identify a subset of genetic loci whose similarity has maximum distance (via matrix norms) to the overall similarity matrix (determined in task 2).

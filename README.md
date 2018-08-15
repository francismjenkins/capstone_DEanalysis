# capstone_revised
Differential expression TCGA dataset

This repository is a work in progress. The goal is to compare different DE analysis techniques e.g. manual (using Python to code the statistical tests) vs package based solutions (e.g. Bioconductor packages such as edgeR and DESeq2). We will also look at the different statistical utilities in Python (e.g. Bayesian methods, t-test, z-score, etc.). We will then compare the aggregate time required to complete a full analysis, using each different approach, and looking at factors such as the degree of complexity and coding time required to implement each of the different solutions.

This is intended to begin a series of repositories comparing different approaches to solving common problems in bioinformatics. Following this analysis, we will look at single cell RNA-seq analysis (an increasingly popular laboratory technique using assays such as droplet based microfluidics), classification problems using tree based methods, and at least one implimentation of neural networks in the context of computational biology (using Tensorflow). All work will be done using Jupyter Notebooks or Rstudio. 

Bioinformatics is increasingly shifting to Python as the language of choice. While R has many more packages and a much longer lineage of providing solutions for bioinformatics, because many basic Python packages (Numpy, scipy, etc.) were written in C, and because of differences in the basic architecture of R and Python, in many cases Python is faster. The differences in speed tend to become more pronounced as the size of the dataset under analysis increases. In the context of bioinformatics, this can impose burdensome limitations and inefficiencies.

Here, we hope to provide basic guidelines for many common tasks in bioinformatics, and demonstrate how they should be coded in Python. We  will also discuss the strengths/weaknesses of each approach and quality control/testing.

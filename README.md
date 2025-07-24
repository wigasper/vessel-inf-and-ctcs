# README

**We will update this notebook with data, cell outputs, and more detailed comments/notes upon publication.**

Currently, we are providing code that can be used to reproduce the main results presented in our work.

This is provided in `reproducing_results.ipynb` and uses the censored data available as supplementary material
and included in this repository. This data has been censored to remove any PHI and is not the original data,
and should produce identical results to those presented in the paper for most analyses. Some analyses
may have slight differences resulting from censoring or processing of the raw data containing PHI. For
example, any survival analyses using patient age as a covariate will be slightly different, since we have
censored the age for patients with advanced ages to protect PHI.
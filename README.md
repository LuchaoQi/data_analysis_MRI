# Data analysis bcaffo lab



[R package](https://github.com/bcaffo/MRIcloudT1volumetrics)



### Summary

> This is a compositional data analysis project based on MRI data. The goal is to perform PCA analysis and predict the Age of patients based on PC scores of ROIs. All functions are intended to be built into [`MRIcloudT1volumetrics`](https://github.com/bcaffo/MRIcloudT1volumetrics) package.
* Convert MRI volumes to compositional data

* PCA

* Multinomial prediction `multinom` on Age based on `PC scores`

* Low ACC still need to be solved

---

1/10/2020

**Updates**

**Goal**

We want to find the most predictable region and the most important variable to investigate associations b/w ROIs

**Method**

conditional independence graph ~ volumetric MRI

- Differ across age/gender
- Sparse version

Gaussian lasso

Lasso regression/ Elastic net

**Goal**

Investigate if correlation change across age under `telencephalon`

**Method**

Permutation test

**Results**

```R
# data22data31   2  10
# "CerebralNucli_L CerebralNucli_R"
# data22data26   1  12
# "CerebralNucli_L WhiteMatter_R"
# data26data31   4  14
# "CerebralNucli_R WhiteMatter_R"
```
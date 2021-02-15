# Data analysis - bcaffo lab

### Summary

> Data analysis project on MRI data. 
>
> One goal is to perform PCA analysis and predict the age of patients based on PC scores of ROIs. All functions are incorporated into [`MRIcloudT1volumetrics`](https://github.com/bcaffo/MRIcloudT1volumetrics) package.
>
> Another goal is to explore changes of conditional dependencies of volumetric MRI across different levels. Also, we are curious if conditional dependencies differ across age/gender? Methods include gaussian graphical lasso and permutation test.
Permutation results:

```R
# data22data31   2  10
# "CerebralNucli_L CerebralNucli_R"
# data22data26   1  12
# "CerebralNucli_L WhiteMatter_R"
# data26data31   4  14
# "CerebralNucli_R WhiteMatter_R"
```
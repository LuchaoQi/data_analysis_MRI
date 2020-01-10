# Data analysis bcaffo lab



### Summary

> This is a compositional data analysis project based on MRI data. The goal is to perform PCA analysis and predict the Age of patients based on PC scores of ROIs. All functions are intended to be built into [`MRIcloudT1volumetrics`](https://github.com/bcaffo/MRIcloudT1volumetrics) package.
* Convert MRI volumes to compositional data

* PCA

* Multinomial prediction `multinom` on Age based on `PC scores`

  ```R
  PCA$x #PC scores
  PCA$rotations #Can be used to visualize the importance of different features i.e. ROIs
  ```

* Low ACC still need to be solved

---

1/10/2020

Updated

> We want to find the most predictable region and the most important variable to investigate associations b/w ROIs

Method

> conditional independence graph ~ volumetric MRI
>
> - Differ across age/gender
> - Sparse version
>
> Raw correlation
>
> Lasso regression/ Elastic net
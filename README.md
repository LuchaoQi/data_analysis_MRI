# Data analysis bcaffo lab



[R package](https://github.com/bcaffo/MRIcloudT1volumetrics)



### Summary

> This is a compositional data analysis project based on MRI data. The goal is to perform PCA analysis and predict the Age of patients based on PC scores of ROIs. All functions are intended to be built into [`MRIcloudT1volumetrics`](https://github.com/bcaffo/MRIcloudT1volumetrics) package.
* Convert MRI volumes to compositional data

* PCA

* Multinomial prediction `multinom` on Age based on `PC scores`

  ```R
  PCA$x #loadings
  PCA$rotations #a matrix whose columns contain the eigenvectors
  ```

* Low ACC still need to be solved

---

1/10/2020

Updates

> We want to find the most predictable region and the most important variable to investigate associations b/w ROIs

Method

> conditional independence graph ~ volumetric MRI
>
> - Differ across age/gender
> - Sparse version
>
> Gaussian lasso
>
> Lasso regression/ Elastic net

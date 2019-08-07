# Data analysis bcaffo lab

- Master's program from 2019 to 2020

> Check MRI project [here](<https://github.com/LuchaoQi/data_analysis_bcaffo_lab/tree/master/MRI%20data%20analysis>).
>
> Check MRIPCA package [here](https://github.com/LuchaoQi/MRIPCA).
>
> Check rnhanes project survival analysis [here](https://github.com/LuchaoQi/rnhanesdata).

## MRI project workflow

> This is a compositional data analysis project based on MRI data. The goal is to perform PCA analysis and predict the Age of patients based on PC scores of ROIs. All functions are intended to be built into [`MRIcloudT1volumetrics`](https://github.com/bcaffo/MRIcloudT1volumetrics) package.
* Convert MRI volumes to compositional data

* PCA

* Multinomial prediction on Age based on `PC scores`

  ```R
  PCA$x #PC scores
  PCA$rotations #Can be used to visualize the importance of different features i.e. ROIs
  ```

* Low ACC still need to be solved

  

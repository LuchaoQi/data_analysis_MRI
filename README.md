## Workflow

* Convert MRI volumes to compositional data

* PCA

* Multinomial prediction on Age based on `PC scores`

  ```R
  PCA$x #PC scores
  PCA$rotations #Can be used to visualize the importance of different features i.e. ROIs
  ```

* Low ACC still need to be solved

  
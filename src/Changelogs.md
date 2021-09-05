# Changelogs

## Sept 1st, 2021

* Clarified TODOs:
    * Write down overview and plans, see [Overview.md](Overview.md) [x]
    * Set up logs [x]
    * Check what attributes need to be included in each voxel of a volume [ ]

## Sept 4th, 2021

Finished the first milestone in [Overview](Overview.md):

* Test on easiest examples of density summation

  **Worst Example:**

  Prediction:

  ![image-20210904221130061](images/bunny_pred_worst.png)

  Reference:

  ![image-20210904221241553](images/bunny_ref_1.png)

  **Best example:**

  Prediction:

  ![image-20210904220727448](images/bunny_pred_best.png)

  Reference:

  ![image-20210904220948209](images/bunny_ref_2.png)

  

* Test on examples of DVR

  Predictions:

  ![image-20210904225826853](images/heart_preds.png)

  References:

  ![image-20210904225922422](images/heart_refs.png)
  
  ## Sept 5th, 2021
  
  In the NanoVis meeting, some issues are pointed out:
  
  * Volumes are not large enough. 128^3 is just 2 million. Need to scale the model to 256^3 and see what happens. Maybe 512^3, since 3D convolutions and DVR in DeepDVR are volume-resolution-agnostic. [ ] 
  * Like in Sept 1st, check what attributes need to be included in each voxel of a volume [ ]
      * Decide what to do when multiple atoms partially occupy a voxel [ ]


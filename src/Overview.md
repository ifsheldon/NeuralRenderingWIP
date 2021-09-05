# Overview

This project aims to develop a neural renderer which takes atomistic models in the representation of volumes and outputs tilt images that look similar to those taken from CryoEM in labs.

## Pipelines

We want to have a pipeline like the below.



![pipeline](./images/pipeline.png)



Now in the context of Direct Volume Rendering, from DeepDVR, we have



![dvr_pipeline](./images/DVR_pipeline.png)



Then we would like to see if the model of DeepDVR can be adapted to generating tilt projections.

## Milestones

1. Test reproducibility of DeepDVR. Estimate Done Before: Sept 6th [x]
    * Test on easiest examples of density summation [x]
    * Test on examples of DVR [x]
2. Collect data for transfer learning for tilt image projection. Estimate Done Before: Sept 12th [ ]
    * Decide attributes in voxels [ ]
    * Decide resolution of volumes (see Changelogs/Sept 5th) [x]
        * Try out volumes with DeepDVR of various resolutions.
    * Get volumes of atomistic models [ ]
    * Get Pseudo Ground Truth from TEM simulator [ ]
3. Train models to generate clean tilt projections. Estimate Done Before: TBD [ ]
4. Decide the architecture of models for generating noisy tilt projections. Estimate Done Before: TBD [ ]

Back to [Projects List](../../README.md#ProjectsList)

# UKF tractography with additional seeding and stopping options

## Key Investigators

- Fan Zhang (BWH, HMS)
- Yogesh Rathi (BWH, HMS)
- Lauren J O'Donnell (BWH, HMS)

# Project Description

<!-- Add a short paragraph describing the project. -->

In this project, we will include brain tissue segmentation maps into the existing unscented Kalman filter (UKF) framework (Malcolm et al 2010, IEEE TMI; Reddy et al 2016, Front. Neuroscience) to inform fiber tracking seeding and stopping. Segmentations of WM, GM and CSF are computed using a deep learning based method that performs tissue segmentation using diffusion MRI data (Zhang et al 2021, Neuroimage). The WM segmentation will be used for tractography seeding, and the GM/CSF segmentations will be used for tractography stopping.

## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Add WM/GM/CSF segmentation maps.
1. Add seeding and stopping masks.
1. Improve input check to handle multiple input options.

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

1. Describe specific steps of **what you plan to do** to achieve the above described objectives.
1. ...
1. ...

## Progress and Next Steps

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE. If there are specific steps that you could not complete then you can describe them here, too. -->

1. Describe specific steps you **have actually done**.
1. ...
1. ...

# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

![UKF-WMGMCSF](https://user-images.githubusercontent.com/7855446/149682553-d16fef74-102a-4013-993b-bf1144b72521.png)

# Background and References

<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->

Zhang, F., Breger, A., Cho, K. I. K., Ning, L., Westin, C. F., O’Donnell, L. J., & Pasternak, O. (2021). Deep learning based segmentation of brain tissue from diffusion MRI. NeuroImage, 233, 117934.

Reddy, C.P. and Rathi, Y., 2016. Joint Multi-Fiber NODDI Parameter Estimation and Tractography Using the Unscented Information Filter. Frontiers in Neuroscience, 10.

Malcolm, J.G., Shenton, M.E. and Rathi, Y., 2010. Filtered multitensor tractography. IEEE transactions on medical imaging, 29(9), pp.1664-1675.


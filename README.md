# apply_ChangeOS
This repository aims to apply the ChangeOS framework which was developed in the study "Building damage assesment with a deep object-based semantic change detection framework" (https://doi.org/10.1016/j.rse.2021.112636). I applied the framework for a natural disaster that was not covered in the paper (Haiti Earth Quake, 2010). The original repository can be found here: https://github.com/Z-Zheng/ChangeOS/tree/master. 

The data was acquired via the Maxar/DigitalGlobe Open Data Program. The pre- and post-disaster images were preprocessed using Q-GIS. The following pre-processing steps were conducted:
- Crop images to cover the same region
- Georeferencing & pixel alignment 
- Resize to fit the models input size (via python)

The results are not accurate. This is probably due to poor image quality.



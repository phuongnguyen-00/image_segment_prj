####################################
# Cyst Segmentation in OCT Images  #
# Using Classical Image Processing #
####################################

## Author: Phuong Hoang Nguyen
## Date: 10th November 2025

#########################
## PROJECT DESCRIPTION ##
#########################

In this project, a classical image segmentation approach for retinal cyst detection in OCT images is 
proposed. The performance of the method will be evaluated using the Dice coefficient, comparing 
automated segmentation results against ground truth annotations from ten OCT images.

#######################
## TECHNOLOGIES USED ##
#######################
- Python
- NumPy
- scikit-image
- Matplotlib
- Jupyter Notebook

#########################
## DIRECTORY STRUCTURE ##
#########################
 ### - ann_dir
   ####     10 Ground truth images, expected results
### - img_dir
   ####     10 Orginal images
### - Hoang_Phuong_Nguyen_Retinal_Cysts_Segmentation.ipynb
   ####     Main notebook containing:
   - Cyst segmentation pipeline
   - Single-image walkthrough for each preprocessing step
   - Batch-processing mode for all images
 ### - README file
   ####      This file, Description of the project

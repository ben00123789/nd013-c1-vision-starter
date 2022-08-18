# Project Writeup Template

## Project overview: 
**This section should contain a brief description of the project and what we are trying to achieve. Why is object detection such an important component of self-driving car systems?**

detect cars
sensing -> decision

## Set up: 
**This section should contain a brief description of the steps to follow to run the code for this repository.**

## Dataset
### Dataset Analysis: 
**This section should contain a quantitative and qualitative description of the dataset. It should include images, charts, and other visualizations.**

training images number
validation, testing number

### Cross-validation: 
**This section should detail the cross-validation strategy and justify your approach.**

## Training
### Reference experiment: 
**This section should detail the results of the reference experiment. It should include training metrics, Tensorboard charts, and a detailed explanation of the algorithm's performance.**

1st 220817 class classification is good, need to check iou & AP

### Improve on the reference: 
**This section should highlight the different strategies you adopted to improve your model. It should contain relevant figures and details of your findings.**

classification_weight: 1.0 -> 0.5

RandomRGBtoGray
RGBtoGray

RandomResizeMethod
ResizeImage
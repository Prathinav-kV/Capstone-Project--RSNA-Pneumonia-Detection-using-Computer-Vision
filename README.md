# Capstone-Project--RSNA-Pneumonia-Detection-using-Computer-Vision

Pneumonia is a global health problem that does not understand social or cultural strata, causing millions of deaths each year. It is an infection affecting either one or both of the lungs, causing inflammation in the air sacs or alveoli.Now to detect Pneumonia, we will need the detect these inflammations in the lungs. The objective is to build an algorithm that can detect visual signals for Pneumonia in medical images or chest radiographs, and automatically locate lung opacities. 

## Skills and Tools

CNN, Computer Vision, UNET architecture, Transfer learning, Mobilenet

## Conclusion

The RSNA Pneumonia Detection Dataset was used for our analysis. While our aim was to theoretically detect “lung opacities”, there were lung opacities that weren't pneumonia related.  From EDA, we found three classes: "Normal", "No Lung opacity/ Not Normal", "Lung Opactity."  We tried many models:  Basic CNN, CNN with Transfer Learning using VGG16 and Resnet50 and UNET (MobileNet Backbone). We were succesfully able to do a comparitive analysis of above models.  Hyper-parameter tuning, Image Augmentation helped in increasing model performance.

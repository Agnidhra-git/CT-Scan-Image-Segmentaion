# CT-Scan-Image-Segmentaion  
##CT Scan Image Segmentation with Deep Learning  
This project explores the application of deep learning techniques for the segmentation of CT scan images, a crucial task in medical image analysis. The primary goal is to accurately identify and delineate anatomical structures or regions of interest within CT scans, aiding in diagnosis and treatment planning.  
##Key Features:  
**Models:** Implements and compares two state-of-the-art convolutional neural network (CNN) architectures:  
*UNet:* Known for its precise localization and ability to capture fine-grained details.  
*SegNet:* Designed for real-time processing and memory efficiency.  
**Custom Loss Function:** Utilizes a combined loss function incorporating binary cross-entropy and Dice loss to optimize segmentation performance, particularly for small structures common in medical images.  
**Data Preprocessing:** Includes resizing and normalization of CT scan images to ensure consistent input for the models.  
**Data Augmentation:** Employs data augmentation techniques to enhance model robustness and generalization.  
**Evaluation:** Assesses model performance using the Dice coefficient, a standard metric for measuring segmentation accuracy.  
###Results:  
Achieved Dice coefficients of 0.8595 (UNet) and 0.8390 (SegNet) on a test set of CT scan images, demonstrating the effectiveness of both models in accurately segmenting anatomical structures.

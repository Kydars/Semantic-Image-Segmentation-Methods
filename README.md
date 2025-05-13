# Semantic Image Segmentation Methods

This repository contains the implementations and results of two semantic image segmentation models: a Random Forest algorithm and a U-Net convolutional neural network. These models were developed to segment images of natural environments, specifically using the WildScenes dataset.

### Results Based on Evaluation Metrics

* **Random Forest Algorithm**
  * **Mean IoU**: 0.3147  
  * **Accuracy**: 0.6279  
  * **Mean F1**: 0.4452  

* **U-Net Convolutional Neural Network**
  * **Mean IoU**: 0.6021  
  * **Accuracy**: 0.8261  
  * **Mean F1**: 0.7175  

### Metric Definitions

- **Mean Intersection over Union (Mean IoU)**: The average IoU across all classes. IoU measures the overlap between predicted segmentation and ground truth, calculated as the area of overlap divided by the area of union.

- **Accuracy**: The proportion of correctly classified pixels relative to the total number of pixels in the image. It reflects overall prediction correctness.

- **Mean F1 Score**: The average F1 score across all classes. The F1 score is the harmonic mean of precision and recall, balancing their trade-off.

### Dataset

The models were trained using the V-01 section of the **WildScenes 2D Semantic Segmentation Dataset**, which includes labeled images and LiDAR point clouds captured in natural outdoor environments.  
Dataset available here: [WildScene2D](https://data.csiro.au/collection/csiro:61541)

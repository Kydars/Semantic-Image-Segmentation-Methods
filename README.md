# Semantic-Image-Segmentation-Methods

This repository contains the implementations and results of the development of the random forest algorithm
and the u-net convolutional model in semantically segmenting images of wild scenes. 

### Results based on Metrics

* **The Random Forest Algorithm**
    * Mean IoU: 0.3147404756238944
    * Accuracy: 0.6278699239095052
    * Mean F1: 0.4452154429954437
* **The U-Net Convolutional Neural Network**
    * Mean IoU: 0.6020750928429215
    * Accuracy: 0.8261184692382812
    * Mean F1: 0.7175161183666644

### Metric Definitions

- **Mean Intersection over Union (Mean IoU)**: The average IoU across all classes. IoU measures the overlap between the predicted segmentation and the ground truth, defined as the area of overlap divided by the area of union.
  
- **Accuracy**: The ratio of correctly classified pixels to the total number of pixels in the image. It measures the overall correctness of the model's predictions.

- **Mean F1 Score**: The average of the F1 scores across all classes. The F1 score is the harmonic mean of precision and recall, and it balances the trade-off between the two.

This repository uses the V-01 section of the WildScenes 2D semantic segmentation dataset, containing both labeled images and lidar point clouds in natural environments, to train the two models.  
Available here: [WildScene2D](https://data.csiro.au/collection/csiro:61541)

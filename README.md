# Fruit Segmentation and Detection with Mask-RCNN
- Fruit detection and segmentation using transfer learning on the Mask-RCNN model already trained on the famous COCO Dataset
- Link to the repo that works on TF2.x: https://github.com/ahmedfgad/Mask-RCNN-TF2
- Coco weights can be downloaded from: https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

## Objective:
- The objective of this work is to detect individual fruits and obtain pixel-wise mask for each detected fruit in an image. To this end, we presents a deep learning approach, to detection and pixel-wise segmentation of fruits based on the state-of-the-art instance segmentation framework, Mask R-CNN.
- Identifying a fruit in an image and drawing a bounding box on it
## Data:
- The data we're using is from Kaggle's Fruit Images for Object Detection competition https://www.kaggle.com/mbkinaci/fruit-images-for-object-detection
- We're dealing with images (unstructured data) so it's probably best we use deep learning/ transfer learning.
- There are 3 classes of fruits (Bananas , apples and oranges)
- There are 240 images in the training set
- There are 60 images in the test set
## Mask RCNN:
The Mask R-CNN model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.
## References:
- https://arxiv.org/pdf/1703.06870.pdf
- https://github.com/SriRamGovardhanam/wastedata-Mask_RCNN-multiple-classes
- https://github.com/matterport/Mask_RCNN
- https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46


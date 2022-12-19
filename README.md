## An-Image-Censoring-System-on-Real-Time-Bidding
## Dataset created using OLDv4 toolkit [link](https://github.com/EscVM/OIDv4_ToolKit)
## Description
An image filtering system for a real-time bidding website based on YOLO-v3 object detection algorithm.
## Improvements
Improved the loss function by changing loss function to Loss_GIoU= 1 - GIoU. In the original loss funciton, when prediction bounding boxes of an object does not overlap with true bounding boxes,IoU = 0, and the gradient become zero. In our modified loss function, gradient will not be zero even if it does not overlap.
## Results
Our testing set achieved 90.15% precision and 92.63% F1-score. Our location of objects is also more accurate and previouly not-detected objects are detected

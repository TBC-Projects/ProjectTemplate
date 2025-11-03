# First steps
## OpenCV
Details: 
Resources: 

## Possible Models
* Integrating custom model
  * Specs?
* Haar Cascade Classifier
  * File: haarcascade_frontalface_default.xml
  * Found in: opencv/data/haarcascades/
  * Algorithm: Haar feature-based cascade classifier.
  * Pros: Fast, lightweight.
  * Cons: Not as accurate as modern DNNs.
* DNN Face Detector (ResNet-based)
  * Files:
    * Deploy.prototxt
    * res10_300x300_ssd_iter_140000.caffemodel
  * Model: Single Shot Multibox Detector (SSD) with ResNet-10 backbone.
  * Pros: Much more accurate than Haar.
  * Cons: Slightly slower.
## Frameworks (maybe)
* PyTorch
  * Can increase accuracy
  * Will need more setup and memory - possible slower runtime
  * Higher accuracy - Slower model
  * Favored in research - considered more flexible?
  * User friendly
* TensorFlow 
  * Steeper learning curve
  * Considered better for scalability and deployment?

## Additional Resources:
[Building a Computer Vision Model with OpenCV and Python
Ganesh-KSV/vit-face-recognition-1 at main](https://codezup.com/building-computer-vision-model-opencv-python/)

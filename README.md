# obj_detection
Repository aimed to collect scripts for image recognition, detection, and localization:

1. Detection_SSD.ipynb allows to detect objects of variouse classes using SSD:
  i. dowloads pretrained object classifier: SSD model and labels
  ii. function that takes an image and detect objects on it, optionaly can be shown all the objects or a selected groupd
2. Object localization allows to find an object and its location on an image. Since classification model is build on top of VGG16 the model need to be trained on the object that has to be detected in future
  i. combines a background image, an object of interest, and its location for training
  ii. build neuaral network on top of VGG16 that has separate chanels for detection, classification, and localization
3. Classification.ipynb
   i. uses ImageDataGenerator to load image by portion
   ii. implements simple CNN to make image classification
 

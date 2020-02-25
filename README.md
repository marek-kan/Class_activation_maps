# Class activation maps

This repository showcases how keras-vis can be used to create Grad-CAM or to explore CNN clasificator. All details are coverd in two notebooks:
 * vgg16_activations: where I explore class activation on pretrained model, inspired by https://fairyonice.github.io/Grad-CAM-with-keras-vis.html
  * CNN_activations: where I take VGG16 pretrained model and train it on my custom dataset. Dataset contains 6 classes, its not labled so its more about classification task rather than object detection.
  
The next task I want to try is to train my custom object detecion model with this utility. Until then I hope this will help some aspiring computer vision engineers :)

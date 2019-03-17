# Flower-Classifier_VGG16_Transfer-Learning
Building a Flower Classifier using Transfer Learning.

Flower-17 was created by the University of Oxford's Visual Geometry Group at the Department of Engineering.

Dataset contains 17 categories of flowers commonly found in the UK. There are 80 images of each flower in the dataset.

Approach:
         
         (i) Use a pre-trained VGG-16 with all its weights except the top layer frozen.
         
         (ii) Train only the Fully-Connected / Dense Layers with a final output of 17.

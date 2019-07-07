# Udacity Deep Learning Nanodedree Dog Breed Clissifier

This is dog breed classifier project for Udacity's Deep Learning Nanodegree program. In this project, I develop code for an image classifier in **Jupiter Notebook** using **Keras** over **Tensorflow**. This code must be able to:

* Detect whether an image contains a dog or human, and distinguish between the two.
* If given an image of a dog, the model predicts the canine’s breed with at least 60% accuracy. Random chance is only 0.75% since there are 133 dog breeds (classes) in the dataset.
* If given an image of a human, the model identifies the dog breeds the person most resembles.

After exploring different CNN models, including **VGG**, **ResNet**, **InceptionV3**, and **Xception**, I chose Xception model because it showed the best test accuracy. Using **learning transfer** I added and trained two final layers on top of pretrained CNN to do the final classification of dog breeds.

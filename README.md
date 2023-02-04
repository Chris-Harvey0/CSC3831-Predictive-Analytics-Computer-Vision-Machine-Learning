# CSC3831-Predictive-Analytics-Computer-Vision-Machine-Learning
## Overview
This project involved completing three separate tasks involving the AddNIST dataset.
The AddNIST dataset is based on the widely used NIST dataset which includes thousands of images of hand-written numbers.
One AddNIST image includes three images from the NIST dataset with each image being in one of the red, green or blue colour channels.
These images are layered on top of each other and the end goal of tasks two and three is to calculate the total of the numbers in each image added up minus one.
## Task 1
This was the simplest of the tasks because this made use of the normal NIST dataset.
This meant that a very simple model could be used and very high accuracies could still be obtained.
Because this model only needed to classify each image into what number it represented accuracies of very close to 100% were obtained.
## Task 2
This task involved using the AddNIST dataset and made use of transfer learning.
For this I researched the available pre-trained models that were available through Keras.
I selected the VGG16 model because of its relatively high accuracies compared to the other models and reasonable train times.
For transfer learning the chosen model needs to be incorporated into a model which handles the input of the images and the output decision layer.
This model was very slow to train but managed to produce reasonable accuracies of 
## Task 3
This task also required use of the AddNIST dataset.
But for this task I needed to create my own model rather than using transfer learning like task two.
This model required quite a bit of optimisation to achieve the best results but the train times were much better than the model from task two.
And in the end the results obtained were better from this model as well.

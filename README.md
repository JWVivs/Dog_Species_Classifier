# Dog Species Classifier
Using deep learning to classify images of various dog species.

# Objective
Build an image classifier that is capable of accurately identifying the breed of a dog. Perhaps an application could be built that would allow the user to input an image of a dog, and they would receive the breed of the dog, as well as some interesting facts regarding the breed.

This will be accomplished by using a convolutional neural net (CNN), which was trained on resnet34.

# Results
The model was able to predict the breed of the dog with an error rate of 0.134 (accuracy of 86.6%). Considering the time saved by using a CNN that has been trained on resnet34, the accuracy could arguably suffice for a user. However; if a lower error rate is desired, more tuning would need to be done.

# Data Source/Resources Used
The Stanford Dogs dataset was used, which features 20,580 images of 120 different dog breeds. It can be found here: http://vision.stanford.edu/aditya86/ImageNetDogs/main.html

Inspiration for the project and walkthrough can be found here:
https://github.com/PlayingNumbers/ball_image_classifier

# Tools
Google Colab

# Application of Convolutional Neural Network in Dog Breed Classification

The goal of this project is to build covolutional neural networks (CNN) to classify breeds of dogs.  CNN is often used in image classification because it takes proximity of different pixel in images into account when classifying images.  CNN is both build from scratch and also by utilizing famous CNN architecture such as VGG16 and Resnet50.  Finally, the trained CNN is also used classify human faces according to their similarity to different breed of dogs.

I have chosen this project as Capstone project of **Data Science NanoDegree Program**, offered by Udacity

## Libraries used in the project
The main libraries used in this project are summarized as follow:
- OpenCV
- Keras (for creating CNN)
- random
- timeit
- os
- pathlib
- glob
- sklearn
- requests
- Matplotlib

All the coding for this project are summarized in **dog_app.ipynb**

## Findings

The model via transfer learning utilziing Resnet50 architecture achieve an accuracy of more than 60%.  It is then further used to classify dog and human images download from the Internet.  Unforunately, the algorithm is unable to recognize some of the human faces

## Conclusion
There was 8 main steps that I followed to complete this project:
* Step 1: Import Datasets
* Step 2: Detect Humans
* Step 3: Detect Dogs
* Step 4: Create a CNN to Classify Dog Breeds (from Scratch)
* Step 5: Use a CNN to Classify Dog Breeds (using Transfer Learning)
* Step 6: Create a CNN to Classify Dog Breeds (using Transfer Learning)
* Step 7: Write your Algorithm
* Step 8: Test Your Algorithm

 It is found that it is quite difficult to assemble CNN from scratch and it takes a lot of time to train the model. Here, transfer learning helps a lot as it utilizes pre-trained world-class architecture which helps to reduce training time and also drastically improve accuracy of the classifier. Unfortunately, all classifiers are not perfect and there will be some error. The accuract that I obtained at the end of my analysis was ~ 80%.

Further, there are various other ways to improve our CNN architecture for dog breeds:

* We can try to change the architecture of layers, or use more fully connected layers and deeper network, although it might not necessarily improve the results.

* We can use GridSearch function to tune the hyperparameters further and get better results. Parameters such as optimizer, loss function, activation function, epoch, and etc.

* We can try different dropout layer and dropout rate in order to reduce overfitting and achieve more accurate testing results.

* We can improve the training process by improving our data set by augmentation (so our model can be robust to image scaling, translation, occlusion, and etc.)

## Medium Blog Post
I have written a [Medium](https://khajeh.medium.com/first-of-all-thanks-for-being-here-and-reading-this-post-hope-you-enjoy-ce5d2bb1a630) Post for this project as well. 

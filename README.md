![alt text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/01/python-machine-learning-project-handwritten-digit-recognition-1-640x480.jpg)

# Handwritten-Digit-Recognition
  
## Table of content
  * [Overview]
  * [Installation]
  * [Project Details]
  * [Technologies used]
  
## Overview
The handwritten digit recognition is the ability of computers to recognize human handwritten digits. It is a hard task for the machine because handwritten digits are not perfect and can be made with many different flavors. The handwritten digit recognition is the solution to this problem which uses the image of a digit and recognizes the digit present in the image.

![alt text](https://camo.githubusercontent.com/3cb372f63ef7bf9417d49b33a9ff444f8b2ac8f9/68747470733a2f2f6b75616e686f6f6e672e66696c65732e776f726470726573732e636f6d2f323031362f30312f6d6e6973746469676974732e676966)



## Installation
The code is written in Python 3.7 in Jupyter Notebook. If you dont have it you can first download Anaconda platform [here](https://docs.anaconda.com/anaconda/install/), where You will find the Jupyter Notebook within it. Jupyter Notebooks are powerful, versatile, shareable and provide the ability to perform data visualization in the same environment.It also allows data scientists to create and share their documents, from codes to full blown reports. They help data scientists streamline their work and enable more productivity and easy collaboration. Due to these and several other reasons you will see below, Jupyter Notebooks are one of the most popular tools among data scientists.

After installing Anaconda, you have to install "keras" library to build the model. For that you have to run the following code in anaconda prompt.
`pip install keras`.

## Project Detail
### Workflow of the project:
   * [Importing the libraries and loading the dataset]
   * [Preprocessing the data]
   * [Creating the model and training it]
   * [Creating GUI to predict digits]
   
### Importing the libraries and loading the dataset
In the main file(`Digit_recognizer_main`), first of all, we are going to import all the modules that we are going to need for training our model. The Keras library already contains some datasets and MNIST is one of them. So we can easily import the dataset and start working with it. The mnist.load_data() method returns us the training data, its labels and also the testing data and its labels.

### Preprocessing the data
The image data cannot be fed directly into the model so we need to perform some operations and process the data to make it ready for our neural network. The dimension of the training data is (60000,28,28). The CNN model will require one more dimension so we reshape the matrix to shape (60000,28,28,1).

### Creating the model and training it
Now we will create our CNN model in Python data science project. A CNN model generally consists of convolutional and pooling layers. It works better for data that are represented as grid structures, this is the reason why CNN works well for image classification problems.

The model.fit() function of Keras will start the training of the model. It takes the training data, validation data, epochs, and batch size.

After training, we save the weights and model definition in the ‘mnist.h5’ file.

### Creating GUI to predict digits
Now for the GUI, we have created a new file(`Digit_recognizer_app`) in which we build an interactive window to draw digits on canvas and with a button(i.e Recognize) we can recognize the digit. The Tkinter library comes in the Python standard library. We have created a function predict_digit() that takes the image as input and then uses the trained model to predict the digit.

Then we create the App class which is responsible for building the GUI for our app. We create a canvas where we can draw by capturing the mouse event and with a button, we trigger the predict_digit() function and display the results.

![alt text](https://drive.google.com/file/d/1JAGtyXba_ZYQ88bijGETbyZTHqTpFuxe/view?usp=sharing)

## Technologies Used
![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![](https://miro.medium.com/max/600/0*LZQf7b4u8f97izwV.png)
![](https://static.javatpoint.com/python/images/tkinter-tutorial.png)
![](https://static.javatpoint.com/tutorial/numpy/images/numpy-tutorial.png)
![](https://learncreategame.com/techart/wp-content/uploads/sites/2/2016/06/pil-Maya-Python-Compile.jpg)



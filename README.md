# K9Klassifier
This project is an AI model that classifies dog breeds using machine learning algorithms. The model is trained on a dataset of dog images and can predict the breed of a dog in an image with high accuracy.

## Installation

To install the required packages, run the following command:


pip install -r requirements.txt


## Usage

To use the model to classify dog breeds, run the following command:


python predict.py --image_path <path_to_image>


Replace <path_to_image> with the path to the image you want to classify.

The model will output the predicted breed of the dog in the image.

## Dataset

The dataset used to train the model is the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/). It contains 20,580 images of 120 breeds of dogs.

## Model

The model is built using a convolutional neural network (CNN) architecture. It consists of multiple layers of convolutional and pooling layers, followed by fully connected layers and a softmax layer for classification.



## Credits

This project was developed by [Johanan Oppong Amoateng]. The code is released under the [MIT License](LICENSE).

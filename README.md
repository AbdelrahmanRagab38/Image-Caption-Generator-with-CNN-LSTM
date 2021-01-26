# Image-Caption-Generator-with-CNN-LSTM
In this  project, we will be implementing the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory).

The Dataset of  the Project
For the image caption generator, we will be using the Flickr_8K dataset. 

direct link to download the dataset (Size: 1GB).

Flicker8k_Dataset : https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip

Flickr_8k_text :  https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip

The Flickr_8k_text folder contains file Flickr8k.token which is the main file of our dataset that contains image name and their respective captions separated by newline(“\n”).

# Pre-requisites

Make sure you have installed all the following necessary libraries:

tensorflow
keras
pillow
numpy
tqdm


# Project File Structure
Downloaded from dataset:

Flicker8k_Dataset – Dataset folder which contains 8091 images.
Flickr_8k_text – Dataset folder which contains text files and captions of images.

### files of the project.

Models – It will contain our trained models.

Descriptions.txt – This text file contains all image names and their captions after preprocessing.

Features.p – Pickle object that contains an image and their feature vector extracted from the Xception pre-trained CNN model.

Tokenizer.p – Contains tokens mapped with an index value.

Model.png – Visual representation of dimensions of our project.

Testing_caption_generator.py – Python file for generating a caption of any image.

Training_caption_generator.ipynb – Jupyter notebook in which we train and build our image caption generator.


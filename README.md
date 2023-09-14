# BollySibling

This GitHub repository contains code for a face recognition system that identifies Bollywood celebrities based on the uploaded images. It uses deep learning techniques and the VGGFace model for feature extraction and similarity comparison. Here's how you can use and understand this project:

## Getting Started

To run this project, you need to follow these steps:

### Data Preparation

1. Organized celebrity images in a directory structure where each actor/actress has their folder inside a 'data' directory. The directory structure should look like python list.


### Feature Extraction

Run the feature extraction script to generate embeddings for each image. The embeddings will be saved in 'embedding.pkl':



## Running the Web Application

After completing the initial setup and feature extraction, run the web application to identify Bollywood celebrities from uploaded images.

### Usage

1. Upload an image of a Bollywood celebrity.
2. The application will display the uploaded image on the left side.
3. On the right side, it will predict the Bollywood celebrity in the image.
4. The predicted celebrity's name will be displayed below the image.

## How it Works

- The project uses the MTCNN face detection model to locate faces in the uploaded image.
- It then extracts facial features using the VGGFace model.
- The extracted features are compared to a database of pre-extracted features from Bollywood celebrity images.
- The closest match is considered as the predicted celebrity.


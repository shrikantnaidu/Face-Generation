# Face-Generation

This project trains a Deep Convolutional Generative Adversarial Network (DCGAN) on a dataset of faces to generate new, realistic images of human faces.

## Overview
- dlnd_face_generation.ipynb - Jupyter notebook containing the project code and explanations
- problem_unittests.py - Unit tests for model solutions
- processed_celeba_small/ - Directory of preprocessed CelebA face images

## Dependencies
Python 3.x
PyTorch
Torchvision
Matplotlib
Numpy

## Usage
To run the Jupyter notebook:

1. Clone this repository
2. Install dependencies
3. Run jupyter notebook in the repository directory
4. Open dlnd_face_generation.ipynb

The notebook contains sections on:

- Loading and visualizing the CelebA dataset
- Defining discriminator and generator models
- reating loss functions and optimizers
- Training the GAN
- Visualizing generated samples
- Preprocessed CelebA images are provided in processed_celeba_small/. New images can be generated after training the GAN.

## Acknowledgements
The CelebA dataset is from http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

This project was completed as part of the Udacity Deep Learning Nanodegree. The starting code and dataset were provided by Udacity.

## License
The contents of this repository are covered under the MIT License.
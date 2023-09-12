# DS203_Image_denoising
## Introduction 

This project was completed as part of the DS203 course at IIT Bombay, under the guidance of Professor Amit Sethi. The goal of this project was to design and implement a Deep Learning Image Denoising Autoencoder using the Keras library. In this README, we will discuss the project's objectives, the techniques used, its significance, and the enjoyable aspects of working on this project.

## Project Objectives
The primary objectives of this project were as follows:

*Data Preparation*: Download and preprocess the MNIST dataset, which consists of hand-written digit images.

*Data Noising*: Introduce noise into the original dataset to simulate real-world scenarios where data can be corrupted.

*Autoencoder Design*: Create a Convolutional Autoencoder architecture to denoise the corrupted images and reconstruct clean images.

*Training and Evaluation*: Train the Autoencoder model on the noisy dataset and evaluate its performance in terms of loss and accuracy.

*Visualization*: Visualize the original images, noisy images, and the denoised images to assess the model's effectiveness.

## Methodology
### Data Preparation
The MNIST dataset, consisting of grayscale images of handwritten digits, was downloaded and preprocessed.
The images were normalized by scaling pixel values between 0 and 1.
Noise was introduced to create a noisy dataset.
### Autoencoder Architecture
A Convolutional Autoencoder architecture was designed. It consists of an encoder and a decoder.
The encoder uses convolutional layers to extract features from the noisy images and reduce their dimensionality.
The decoder then upsamples the encoded features to reconstruct clean images.
### Training
The model was trained using various optimizers, including 'Adadelta' and 'Adam', to minimize the binary cross-entropy loss.
Training was performed over 100 epochs with a batch size of 128.
### Evaluation and Visualization
The model's performance was evaluated on both training and testing datasets.
Visualizations were generated to compare original, noisy, and denoised images.
## Significance
This project is significant for several reasons:

*Image Denoising*: It demonstrates the practical application of deep learning in image denoising, a fundamental problem in computer vision with broad real-world applications.

*Hands-On Experience*: It provided hands-on experience in working with real-world datasets, data preprocessing, and model development using Keras.

*Experimentation*: The project allowed for experimentation with different autoencoder architectures and optimization techniques, enhancing understanding and skills in deep learning.

## What I Enjoyed
During the course of this project, I had the opportunity to gain valuable insights and skills in various aspects of deep learning and data science, including:

*Exploration of Optimizers*: I explored and experimented with different optimizers such as 'Adadelta' and 'Adam' to train the autoencoder model effectively. This experience helped me understand how different optimization algorithms can impact training dynamics and convergence.

*In-Depth Study of Autoencoders*: Designing the Convolutional Autoencoder architecture for image denoising involved a deep dive into the theory and practical aspects of autoencoders. I gained a comprehensive understanding of how autoencoders work, their applications, and how to fine-tune their architectures for specific tasks.

*Hyperparameter Tuning*: The project involved extensive hyperparameter tuning, including batch size, learning rate, and the number of convolutional layers. This hands-on experience in hyperparameter optimization was a valuable lesson in model fine-tuning.

*Data Preprocessing*: I learned the importance of data preprocessing, including normalization and introducing controlled noise into datasets. This skill is crucial in preparing data for machine learning tasks.

*Collaborative Work*: Collaborating with Professor Amit Sethi and fellow students in the DS203 course provided exposure to teamwork, peer feedback, and collective problem-solving. It was an opportunity to learn from others' perspectives and experiences

# STATS 507 Final Project
# William Meynardie
# Classifying Images of Animals Using the Vision Transformer

### William Meynardie's Final Project for Stats 507

This project allows you to classify images of 90 different species of animals. It uses the mertcobanov/animals dataset to train the Vision Transformer on images of animals. It fine-tunes this pre-trained model, and then uploads the fine-tuned model to Hugging Face.

generate-animals-vit.ipynb: Generates the fine-tuned model using the animals dataset. WARNING: this file takes a total of close to an hour to run, but once it runs, the model is uploaded to Hugging Face and it can be retrieved quickly.

use-animals-vit.ipynb: This file pulls the fine-tuned model from Hugging Face and applies it to any images. The code is currently set up to pull images from the "samples" folder to display and classify them, but it can be modified to display any images.

The package requirements for this code can be found in 'requirements.txt'.

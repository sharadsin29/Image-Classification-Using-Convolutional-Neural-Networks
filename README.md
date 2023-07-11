# Image Classification Using Convolutional Neural Networks and Transfer Learning

This repository contains my project on Image Classification using Convolutional Neural Networks (CNNs) and Transfer Learning. 

## Project Description

The project includes several tasks:

1. **Transfer Learning:** Fine-tuning pre-trained ResNet-50 model on the Oxford Pet Dataset. The project demonstrates how to fine-tune a pre-trained model on a new task, comparing the effect of training the entire network versus only the output layer.

2. **Training a CNN from Scratch:** Implementing and training a small CNN from scratch on the CIFAR-10 dataset. The CNN includes three hidden convolutional layers and uses the Mish activation function.

3. **Adding Batch Normalization:** Modifying the small CNN by adding batch normalization. This part of the project explores the impact of batch normalization on the training process and model performance.

4. **Optimizing the CNN Architecture:** Further optimizing the small CNN architecture to improve performance. This involves experimenting with different architectures, including changing filter sizes, considering alternative normalization functions (EvoNorm), and more advanced optimizers (AdamW).

The project includes extensive results, such as training and test loss curves for both ResNet-50 and Swin-T models, accuracy reports, and error analysis. 

## Technologies Used

The project was implemented using Python and the following libraries and frameworks:

- PyTorch
- PyTorch Lightning
- fastai
- Matplotlib
- NumPy
- Weights & Biases


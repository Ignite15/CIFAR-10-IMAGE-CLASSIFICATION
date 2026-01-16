# CIFAR-10-IMAGE-CLASSIFICATION


Overview

This project implements a multi-level deep learning pipeline for image classification on the CIFAR-10 dataset. The work progresses from a baseline transfer learning model to advanced architectures and ensemble techniques, demonstrating both practical implementation and analytical depth.
All experiments are implemented in PyTorch and executed using Google Colab with GPU support.

Dataset
CIFAR-10 (60,000 images, 10 classes)

Official split:
50,000 training images
10,000 test images
Validation set (10,000 images) is derived from the training set to maintain an effective 80-10-10 split

Levels Completed

Level 1: Baseline transfer learning using ResNet-18

Level 2: Data augmentation, regularization, and partial fine-tuning

Level 3: Custom CNN with Squeeze-and-Excitation attention

Level 4: Ensemble learning using multiple architectures

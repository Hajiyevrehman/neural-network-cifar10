# Neural Network for Multi-class Classification (Part 2)

## Overview

This project focuses on training and testing a neural network model for multi-class classification using the CIFAR10 dataset. It builds upon the neural network components implemented in Part 1.

## Project Structure

project_root
├── README.md (this file)
├── classification_nn.ipynb (main notebook)
├── get_datasets.py (dataset download script)
├── layers/
│   ├── linear.py
│   ├── relu.py
│   ├── softmax.py
│   ├── loss_func.py
│   └── sequential.py
└── utils/
    ├── trainer.py
    └── optimizer.py

## Dataset Preparation

Before starting, download the CIFAR10 dataset by running:


2. Navigate to and open `classification_nn.ipynb`.

3. Run through the cells in the notebook to train and test the neural network on the CIFAR10 dataset.

## Usage Tips

- Run all code cells in the notebook sequentially.
- Answer all inline questions in the designated areas.
- Aim for vectorized implementations to avoid using for loops.
- Do not change the random seed where it is set to ensure reproducibility.


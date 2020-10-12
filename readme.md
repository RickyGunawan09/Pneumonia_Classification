# Pneumonia Classification

This is a Pytorch based convolutional neural network for detecting pneumonia in frontal-view chext X-ray images.

<div align=center><img width="600" height="220" src="./screenshot/Capture.PNG"/></div>

## Dataset

The project uses data from the [Chest X-Ray Images](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) dataset on kaggle.

There are 5,863 chest X-Ray images (JPEG) and 2 categories (Normal/Pneumonia).

## Prerequisites

- Google Colaboratory

## Usage

1. Clone this repository.

2. Download chest X-ray images from [kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

3. Run `ModelCNN_upto_93%`

## Results

- Model with dropout in the fully connected layers achieves a test accuracy of 91%.
  - run `ModelCNN_upto_93.ipynb`


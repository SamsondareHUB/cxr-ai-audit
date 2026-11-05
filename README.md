# A Deployment-Oriented Audit of a Pretrained Chest X-ray Classifier

This repository contains the code, figures, and results for a rapid audit of a pretrained chest X-ray AI model for pneumonia detection.

## Research question

Does a pretrained chest X-ray classifier provide useful discrimination, calibration, and clinically meaningful operating characteristics for pneumonia triage?

## Dataset

- PneumoniaMNIST
- 4,708 training images
- 524 validation images
- 624 test images
- Binary labels: normal (0) and pneumonia (1)

## Model

- ResNet-18 pretrained on ImageNet
- Frozen convolutional backbone
- Fine-tuned final classification layer
- Images resized from 28 x 28 to 224 x 224
- Five training epochs

# Citrus Disease Detection Using Image Processing

This project uses deep learning and transfer learning to classify citrus fruit images into two disease classes: **Citrus Canker** and **Black Spot**.

The project compares multiple CNN architectures, including **ResNet50**, **VGG16**, **EfficientNetB0**, and **MobileNetV2**. The best-performing model was **ResNet50**, achieving **97.79% accuracy** with **0.9779 precision, recall, and F1-score** on the test set.

## Project Type

Research Project / Paper Manuscript

## Models Used

* ResNet50 — Proposed model
* VGG16 — Baseline model
* EfficientNetB0 — Baseline model
* MobileNetV2 — Baseline model

## Techniques

* Image resizing to 224x224
* Image preprocessing and normalization
* Image filtering
* Data augmentation
* Transfer learning
* CNN-based binary classification
* Accuracy/loss curve evaluation
* Confusion matrix evaluation

## Dataset

The dataset contains citrus fruit images classified into two categories from Kaggle:

* Citrus Canker
* Black Spot

Dataset split:

* Training images: 2,032
* Testing images: 407



## Results

| Model          | Accuracy | Precision | Recall | F1-score |
| -------------- | -------: | --------: | -----: | -------: |
| ResNet50       |   97.79% |    0.9779 | 0.9779 |   0.9779 |
| VGG16          |   97.54% |    0.9754 | 0.9754 |   0.9754 |
| EfficientNetB0 |   97.05% |    0.9706 | 0.9705 |   0.9705 |
| MobileNetV2    |   95.33% |    0.9546 | 0.9533 |   0.9532 |



## Paper

This repository is related to the paper/manuscript:

**Citrus Disease Detection Using Image Processing**

Authors: Saif Mohamed, Hassan Abdallah, Marawan Mohamed, Abdelrahman Medhat, and Mohamed Fathi.


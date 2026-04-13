https://www.kaggle.com/competitions/pig-posture-recognition

# Kaggle Pig Posture Recognition

PyTorch-based image classification project for pig posture recognition in a Kaggle competition.

## Overview

This repository contains my Kaggle computer vision project on **pig posture recognition**.  
The goal of the project was to build an image classification pipeline that can accurately classify pig posture images using deep learning models.

I developed and tested multiple notebook versions, with a focus on improving validation performance and leaderboard results through model selection, augmentation, training strategy, and inference-time techniques.

## Results

### Individual Result
- **Model:** ConvNeXt
- **Score:** **F1 = 0.948**
- **Rank:** **12th out of 101 teams**

### Team Result
- **Model:** EfficientNet
- **Score:** **F1 = 0.956**
- **Rank:** **7th out of 101 teams**

## Main Contributions

- Built an end-to-end **PyTorch-based image classification pipeline**
- Trained a **ConvNeXt-based model** for pig posture recognition
- Improved training with techniques such as:
  - data preprocessing
  - augmentation
  - checkpoint-based experimentation
  - hyperparameter tuning
- Contributed to a team submission based on **EfficientNet**

## Repository Structure

- `pig_posture_recognition_version_19.ipynb`  
  Earlier experiment notebook

- `pig_posture_recognition_version_22.ipynb`  
  Improved experiment notebook with the final ConvNeXt-based approach

## Methods

The project focused on building a practical competition pipeline for image classification.  
The notebooks include the overall workflow for:

- data loading and preprocessing
- model training
- validation
- checkpoint saving
- inference and submission generation

## Tech Stack

- **Language:** Python
- **Framework:** PyTorch
- **Environment:** Jupyter Notebook

## Motivation

This project was conducted to strengthen my practical experience in:

- computer vision
- image classification
- deep learning experimentation
- competition-oriented model improvement

It also served as a foundation for my later research interests in **Embodied AI**, **robot learning**, and **vision-based perception**.

## Future Improvements

Possible next steps include:

- refactoring notebook code into modular Python scripts
- adding clearer experiment tracking
- comparing more backbones under the same validation setup
- improving reproducibility with a dedicated requirements file

## Author

**Jiho Kang**  
Seoul National University of Science and Technology  
Department of Mechanical and Automotive Engineering

GitHub: [jiho021027-netizen](https://github.com/jiho021027-netizen)

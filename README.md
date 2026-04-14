# IIoT Attack Detection using Ensemble Learning

[![DOI](https://zenodo.org/badge/1210323814.svg)](https://doi.org/10.5281/zenodo.19567561)

## Description
This project presents an ensemble-learning approach for detecting cyber-attacks in Industrial Internet of Things (IIoT) environments using the X-IIoTID dataset.

## Features
- Data preprocessing (cleaning, encoding, normalization)
- SMOTE for handling class imbalance
- PCA for dimensionality reduction
- Machine learning models:
  - Random Forest
  - Extra Trees
  - KNN
- Ensemble soft voting classifier

## Dataset
X-IIoTID dataset (not included in this repository).

## Usage
1. Upload the X-IIoTID dataset to Google Colab or local environment.
2. Update the dataset path in the notebook.
3. Run all cells sequentially.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
  
  ## Dataset
The X-IIoTID dataset is not included in this repository.
Please obtain it from the official source and update the dataset path before running the code.

## Citation
If you use this work, please cite the corresponding research paper.

## Notes
This code supports binary and multiclass classification tasks.

## Code Availability
The source code is publicly available on GitHub and archived with a DOI via Zenodo:
https://doi.org/10.5281/zenodo.19567561

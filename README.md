# IIoT Attack Detection using Ensemble Learning

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

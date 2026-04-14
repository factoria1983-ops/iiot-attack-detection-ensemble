# IIoT Attack Detection using Ensemble Learning

## Description

This project presents an ensemble-learning approach for detecting cyber-attacks in Industrial Internet of Things (IIoT) environments using the X-IIoTID dataset. The proposed system combines multiple machine learning models to improve detection accuracy and robustness.

## Dataset Information

The study utilizes the X-IIoTID dataset, a publicly available benchmark dataset designed for intrusion detection in IIoT environments. It contains both normal and malicious network traffic representing realistic industrial scenarios and diverse cyber-attack types.

The dataset can be accessed from:
https://www.unb.ca/cic/datasets/iiot-dataset-2023.html


Note: The dataset is not included in this repository. Please download it from the official source and update the dataset path before running the code.

## Code Information

This repository includes the implementation of the proposed ensemble-learning framework. The main components are:

* Data preprocessing scripts (cleaning, encoding, normalization)
* SMOTE for handling class imbalance
* PCA for dimensionality reduction
* Individual classifiers:

  * Random Forest
  * Extra Trees
  * K-Nearest Neighbors (KNN)
* Ensemble model using soft voting

## Usage Instructions

1. Download the X-IIoTID dataset from the official source.
2. Upload the dataset to your working environment (e.g., Google Colab or local machine).
3. Update the dataset file path in the script or notebook.
4. Install the required dependencies.
5. Run the code step by step (or execute all cells if using a notebook).

## Requirements

* Python 3.x
* pandas
* numpy
* scikit-learn
* imbalanced-learn
* matplotlib
* seaborn

You can install dependencies using:
pip install -r requirements.txt

## Methodology

The methodology followed in this project includes:

1. Data preprocessing:

   * Cleaning missing values
   * Encoding categorical features
   * Feature normalization

2. Handling class imbalance:

   * Synthetic Minority Over-sampling Technique (SMOTE)

3. Feature reduction:

   * Principal Component Analysis (PCA)

4. Model training:

   * Training multiple machine learning classifiers

5. Ensemble learning:

   * Combining classifiers using soft voting

6. Evaluation:

   * Performance assessed using standard classification metrics

## Citations

If you use this work, please cite the corresponding research paper.

## Code Availability

The source code is publicly available and archived with a DOI:
https://doi.org/10.5281/zenodo.19567561

## License

This project is provided for research and academic purposes. (Specify a license if applicable, e.g., MIT License)

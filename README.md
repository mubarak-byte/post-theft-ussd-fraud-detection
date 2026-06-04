# Post-Theft USSD Fraud Detection in Nigerian Mobile Banking

This repository contains the synthetic dataset and Python notebook used for the study:

**Modeling Post-Theft USSD Fraud: Behavioural Sequence or Discrete Events? A Comparative Machine Learning Evaluation for Nigerian Mobile Banking**

## Overview

This project focuses on detecting post-theft USSD fraud in Nigerian mobile banking using machine learning. USSD banking is widely used in Nigeria because it allows users to perform banking transactions without internet access. However, when a phone is stolen with the registered SIM card still active, fraudsters may attempt to take over the victim’s mobile banking access.

The study models post-theft USSD fraud as a behavioural fraud detection problem. It uses a threat-model-based synthetic dataset and compares different machine learning models to determine whether post-theft USSD fraud is better detected as a behavioural sequence or as a set of discrete high-signal events.

## Repository Description

Synthetic dataset and machine learning framework for post-theft USSD fraud detection in Nigerian mobile banking.

## Contents

The repository contains:

- `USSD_fraud_detection.ipynb`  
  Google Colab notebook containing the dataset generation, preprocessing, model training, cross-validation and evaluation.

- `ussd_fraud_dataset_v10.csv`  
  Synthetic dataset generated for the study.

- `requirements.txt`  
  List of Python packages required to run the notebook.

- `README.md`  
  Project documentation.

## Dataset

The dataset file is:

```text
ussd_fraud_dataset_v10.csv

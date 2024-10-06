# DNA-Binding Protein Region Prediction

This project focuses on predicting DNA-binding protein regions using a dataset of 9000 samples, which includes both DNA-binding and non-DNA-binding proteins. The goal is to accurately classify these proteins based on their features.

## Dataset

The dataset consists of 9000 samples, containing labeled data for DNA-binding and non-DNA-binding proteins. The features for model training are extracted using **Amino Acid Composition (AAC)**.

## Models

Three different machine learning models were implemented to classify the proteins:

1. **Dense Neural Network (DNN)**
2. **Support Vector Machine (SVM)**
3. **Random Forest**

Among these models, the **Random Forest** model done the best performance.

## Evaluation Metrics

The model performance was evaluated using the following metrics:

- **Accuracy Score**
- **Precision Score**
- **Recall Score**
- **F1 Score**
- **ROC AUC Score**

These metrics provide a comprehensive evaluation of the models' capabilities in correctly classifying DNA-binding and non-DNA-binding proteins.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/SinhaAfroz/DNA-binding-protein-region-prediction.git
   cd DNA-binding-protein-region-prediction
   ```

2. Install the required packages
```
pip install -r requirements.txt
```

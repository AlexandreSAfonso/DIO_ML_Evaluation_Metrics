# Classification Model Performance Evaluation Project

This project aims to calculate the main metrics for evaluating data classification models.
Metrics include Accuracy, Sensitivity (sense or Recall), Specificity, Precision, and F-Score.
In addition, the ROC (Receiver Operating Characteristic) curve is also generated with the area under the curve (AUC) to evaluate the model's performance.

## Features

- **Calculation of Evaluation Metrics**: 
  The code calculates model performance evaluation metrics, including:
  - **Accuracy**
  - **Sense (Recall)**
  - **Specificity**
  - **Precision** and
  - **F-Score**

- **Curve ROC**:
  The code generates the **ROC Curve** (Receiver Operating Characteristic) and calculates the area under the curve (**AUC**).
  This curve is useful for evaluating the binary classification ability of the model, indicating how well the model separates the classes.

## Requirements

- **Python** 3.x
- **Bibliotecas**:
  - `matplotlib`
  - `numpy`
  - `scikit-learn`

You can install the dependencies in a Python environment with the following command:

```bash
> pip install matplotlib numpy scikit-learn

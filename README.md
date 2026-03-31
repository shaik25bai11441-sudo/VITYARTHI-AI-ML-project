# House Price Prediction (Basic ML Project)

## About the Project

This is a simple machine learning project where I tried to predict house prices based on a few factors like area, number of bedrooms, and age of the house.

The main goal of this project was to understand how a basic ML model works from start to finish.

---

## Tools Used

* Python
* pandas
* numpy
* scikit-learn

---

## Dataset

I used a small dataset (`INPUT_house_data.csv`) which contains:

* area (in sq ft)
* bedrooms
* age
* price

---

## What the Code Does

* Reads the dataset
* Splits it into training and testing data
* Trains a Linear Regression model
* Checks how well the model performs using:

  * MSE
  * RMSE
  * R² score
* Takes user input and predicts house price

---

## Results

* R² Score is around **0.97**
* RMSE is around **8000**

Since the dataset is very small, results may change slightly if the data split changes.

---

## How to Run

1. Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

2. Keep the `house_data.csv` file in the same folder

3. Run the Python file:

```bash
python filename.py
```

---

## Example

Input:

```
Area: 1300  
Bedrooms: 3  
Age: 6  
```

Output:

```
Predicted Price: ₹263,787
```

---

## Limitations

* Works only within these ranges:

  * Area: 800–2000
  * Bedrooms: 1–4
  * Age: 1–15
* works on Very small dataset.
* Not highly accurate for real-world use.

---

## What I Learned

* An end-to-end machine learning workflow, including problem definition, data collection and preprocessing, feature engineering, model selection, training, validation, and deployment considerations.
  
* Techniques for training models: choosing appropriate algorithms , splitting data into training/validation/test sets , selecting loss functions and optimizers, tuning hyperparameters, and employing regularization to prevent overfitting.
  
* Methods for evaluating model performance: using metrics appropriate to the task (example- accuracy, precision/recal,  ROC-AUC for classification; MAE, RMSE for regression) , constructing and interpreting confusion matrices , performing cross-validation and assessing model calibration and robustness.
  
* Procedures for receiving input and producing predictions reliably: validate and preprocess incoming data, handle missing or malformed values, apply the same feature transformations used during training, generate appropriate outputs (probabilistic scores or point estimates), and prepare the inference pipeline for batch or real-time deployment with logging, monitoring, and error-handling to ensure correctness and performance.

---

## Future Improvements

* Expand the dataset to increase representativeness and model generalization.
  
* Incorporate additional features and perform feature engineering to capture more predictive signal.
  
* Experiment with alternative model architectures and algorithms , including ensemble methods and hyperparameter tuning , to identify better-performing approaches.

---

## Author

Shaik mahammed Sahil

# oibsip_taskno-1
# Iris Flower Classification

This project implements a classification model to predict the species of iris flowers based on sepal and petal dimensions using the famous Iris dataset. The model employs Logistic Regression and achieves high accuracy.

---

## Dataset

The dataset used is the Iris dataset, which contains 150 samples of iris flowers belonging to three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each sample includes the following features:
- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`

---

## Project Workflow

1. **Importing Dependencies**  
   Libraries like `numpy`, `pandas`, and `scikit-learn` are used for data manipulation and model building.

2. **Data Collection and Analysis**  
   - Loaded the dataset using `pandas`.
   - Performed exploratory data analysis to understand the data distribution and identify missing or inconsistent values.

3. **Data Preprocessing**  
   - Checked for missing values, null values, and outliers.
   - Encoded the target variable (`Species`) using `LabelEncoder`.

4. **Train-Test Split**  
   - Split the dataset into training and testing sets (80-20 split) while maintaining the class distribution using stratified sampling.

5. **Model Building**  
   - Trained a Logistic Regression model using the training set.
   - Tuned parameters like `max_iter` and utilized the `lbfgs` solver.

6. **Evaluation**  
   - Evaluated the model using accuracy metrics:
     - Training accuracy: **97.50%**
     - Testing accuracy: **96.67%**

7. **Prediction System**  
   - Developed a prediction system to classify iris flowers based on input features.

---

## Key Results

- The Logistic Regression model showed excellent performance with an accuracy of **96.67%** on the test set.
- The model was able to predict the species of a new flower input successfully.

---

## How to Run

1. Clone this repository.
2. Ensure you have Python installed with the following libraries:
   - `numpy`
   - `pandas`
   - `scikit-learn`
3. Run the script in a Python environment:
   ```bash
   python iris_classification.py

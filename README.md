# Flower Classification using Iris Dataset

## Project Overview

This project is a Machine Learning classification model built using the **Iris dataset**. The goal is to classify a flower into one of three species based on its measurements.

The project includes:

- Loading and exploring the Iris dataset
- Performing Exploratory Data Analysis (EDA)
- Visualizing relationships between flower features
- Training classification models
- Comparing model accuracy
- Evaluating predictions using a confusion matrix
- Saving the trained model and scaler
- Predicting flower species using custom user input

---

## Dataset

This project uses the built-in **Iris dataset** from `scikit-learn`.

Target classes:

- Setosa
- Versicolor
- Virginica

Features used:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

---

## Project Structure

```bash
Syntecxhub_Flower_Classification/
│
├── Flower_Classification.ipynb
├── flower_classifier.pkl
├── flower_scaler.pkl
└── README.md
```

---

## Workflow

### 1. Load Dataset
The Iris dataset is loaded using `sklearn.datasets`.

### 2. Exploratory Data Analysis
Performed basic EDA such as:

- checking dataset shape
- class distribution
- summary statistics
- missing values

### 3. Data Visualization
Created visualizations to understand feature relationships, including:

- pair plots
- scatter plots
- heatmap

### 4. Model Training
Trained classification models such as:

- Logistic Regression
- Decision Tree Classifier

### 5. Model Evaluation
Compared model performance using:

- Accuracy Score
- Classification Report
- Confusion Matrix

### 6. Model Saving
Saved trained files using pickle:

- `flower_classifier.pkl`
- `flower_scaler.pkl`

### 7. Prediction
Used custom input values to predict flower species.

---

## How to Run

### Clone Repository

```bash
git clone <Dikshitha-Reddy-Vanga/Syntecxhub_Flower_Classification>
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

Open Jupyter Notebook and run:

```bash
Flower_Classification.ipynb
```

---

## Output Files

### `flower_classifier.pkl`
Saved trained classification model.

### `flower_scaler.pkl`
Saved scaler used for feature transformation before prediction.

---

## Future Improvements

Possible improvements for this project:

- Build a web app using Flask or Streamlit
- Add model deployment
- Accept real-time user input through UI
- Compare more classification algorithms

---

## Conclusion

This project demonstrates an end-to-end Machine Learning workflow for flower species classification using the Iris dataset.

It covers:

- Data analysis
- Visualization
- Model building
- Model evaluation
- Prediction

The trained model can accurately predict the species of a flower based on its measurements.

---

## Author

Dikshitha Reddy Vanga

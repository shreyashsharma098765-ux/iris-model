# Iris Flower Classification Model 🌸

This project is a Machine Learning-based Iris Flower Classification system that predicts the species of an iris flower using its features such as sepal length, sepal width, petal length, and petal width.

## Project Overview

The model was trained using the famous **Iris Dataset** and classifies flowers into the following categories:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The project uses trained `.pkl` files for deployment and prediction purposes.

## File Descriptions

* **iris.ipynb.ipynb**
  Jupyter Notebook containing data preprocessing, model training, evaluation, and model saving code.

* **iris_model.pkl**
  Stores the trained machine learning classification model.

* **feature_columns.pkl**
  Contains the feature column names used during prediction.

* **label_encoder.pkl**
  Stores the label encoder used to convert flower species labels into numerical values and vice versa.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Pickle

## Features

* Iris flower species prediction
* Trained ML model using Iris dataset
* Saved model deployment using `.pkl` files
* Data preprocessing and label encoding

## How to Run the Project

1. Install the required libraries:

```bash id="8z1m4p"
pip install pandas numpy scikit-learn
```

2. Open the Jupyter Notebook:

```bash id="v71q2a"
jupyter notebook
```

3. Run the `iris.ipynb.ipynb` notebook to train or test the model.

## Future Improvements

* Add a Streamlit frontend UI
* Deploy the model online
* Improve model visualization
* Add prediction probability display

---

⭐ If you like this project, consider giving it a star on GitHub!




# Diabetes Progression Prediction Using ANN

## 📌 Project Overview

This project focuses on predicting diabetes disease progression using an Artificial Neural Network (ANN) Regression model.

The project uses a diabetes dataset to train a neural network model that predicts the disease progression value based on the given input features.

TensorFlow and Keras are used to build and train the ANN model, while Scikit-learn is used for data splitting and feature scaling.

## 🎯 Objectives

- Load and understand the diabetes dataset.
- Separate input features and target variable.
- Split the dataset into training and testing sets.
- Apply StandardScaler for feature scaling.
- Build an ANN regression model.
- Train the model using the Adam optimizer.
- Visualize actual vs predicted values.
- Analyze prediction error distribution.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## 📂 Project Structure

```text
Diabetes-Progression-Prediction-Using-ANN/
│
├── DIABETS_REGRESSION.ipynb
├── 3_diabetes_regression.csv
└── README.md
```

## ⚙️ Project Workflow

### 1. Import Libraries
Imported the required Python libraries for data handling, visualization, preprocessing, and ANN model development.

### 2. Dataset Loading
Loaded the diabetes regression dataset using Pandas.

### 3. Feature and Target Separation
- Input Features (X): All columns except `disease_progression`.
- Target Variable (y): `disease_progression`.

### 4. Train-Test Split
Split the dataset into training and testing sets using an 80:20 ratio with `random_state=42`.

### 5. Feature Scaling
Applied StandardScaler to scale the training and testing input features.

### 6. ANN Model Building
Created a Sequential Artificial Neural Network with:
- Input layer with 64 neurons and ReLU activation.
- Hidden layer with 32 neurons and ReLU activation.
- Output layer with 1 neuron for regression prediction.

### 7. Model Compilation
Compiled the ANN model using:
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)
- Evaluation Metric: Mean Absolute Error (MAE)

### 8. Model Training
Trained the ANN model using:
- Epochs: 100
- Batch Size: 16

### 9. Prediction and Visualization
Generated predictions using the test dataset and visualized:
- Actual vs Predicted Disease Progression.
- Prediction Error Distribution.

## 📊 Visualizations

The project includes two visualizations:

1. **Actual vs Predicted Scatter Plot:** Compares actual disease progression values with predicted values.
2. **Prediction Error Distribution:** Shows the distribution of differences between actual and predicted values.
<img width="1389" height="490" alt="image" src="https://github.com/user-attachments/assets/fe69fc3e-9719-4fcf-8520-40eb2aac6f50" />

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Diabetes-Progression-Prediction-Using-ANN.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
   ```

3. Make sure `3_diabetes_regression.csv` is available in your working directory.

4. Update the CSV file path in the notebook if required.

5. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `DIABETS_REGRESSION.ipynb` and run all cells.

## 📌 Conclusion

This project demonstrates the use of an Artificial Neural Network for predicting diabetes disease progression as a regression task. It covers data preprocessing, feature scaling, model training, prediction, and visualization.

## 👨‍💻 Author

Your Name

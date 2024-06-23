# Diabetes Prediction Using Artificial Neural Networks

This project focuses on predicting diabetes in patients using an Artificial Neural Network (ANN) model. The dataset used for this analysis is sourced from Kaggle and contains various features such as glucose level, blood pressure, skin thickness, and BMI, among others, which are used to predict the likelihood of diabetes.

## Dataset

The dataset used for this project is the [Diabetes dataset from Kaggle](https://www.kaggle.com/datasets/mshoaibishaaq/pakistani-diabetes-dataset). It consists of several medical predictor variables and one target variable (Outcome - 0 for non-diabetic, 1 for diabetic).

## Project Workflow

1. **Data Preprocessing**
   - Loading the dataset.
   - Handling missing values.
   - Feature scaling and normalization.
   - Splitting the dataset into training and testing sets.

2. **Model Architecture**
   - Building an Artificial Neural Network (ANN) with the following layers:
     - Input layer
     - Hidden layers with activation functions
     - Output layer with a sigmoid activation function for binary classification

3. **Model Training**
   - Compiling the model with appropriate loss function and optimizer.
   - Training the model on the training data.

4. **Model Evaluation**
   - Evaluating the model on the test data to determine its accuracy
   - Generating a confusion matrix to visualize the model's performance.

## Tools and Technologies

- **Google Colab:** The Integrated Development Environment (IDE) used for this project.
- **Python Libraries:** 
  - TensorFlow and Keras for building and training the ANN.
  - Pandas and NumPy for data manipulation.
  - Matplotlib and Seaborn for data visualization.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-ann.git

# neural-network-challenge-2
Module Challenge 19

Employee Attrition and Department Prediction 🧠🔍
Overview
This project uses a neural network with multiple outputs to predict both employee attrition and department based on HR data. The model leverages a shared architecture with branching output layers to simultaneously predict:

Whether an employee will leave the company (attrition) 👋
Which department the employee belongs to 🏢

Project Structure

Data Preprocessing: Cleaned and prepared HR data for modeling 🧹
Feature Engineering: Selected relevant features and encoded categorical variables ⚙️
Model Architecture: Built a neural network with shared layers and dual output branches 🏗️
Training & Evaluation: Trained the model and evaluated its performance on test data 📊

Key Features

Multi-output neural network architecture 🔀
Shared layers with task-specific output branches 🌿
Dropout regularization to prevent overfitting 🎯
Class imbalance considerations in model evaluation ⚖️

Results
The model achieved:

86% accuracy on department prediction 🎉
42% accuracy on attrition prediction 📉

The lower accuracy on attrition prediction is likely due to class imbalance in the dataset, as employee turnover is typically a rare event compared to retention.
Future Improvements
Possible enhancements to the model include:

Implementing class weights or resampling to address imbalance 🔧
Feature engineering to create more predictive variables ✨
Hyperparameter tuning to optimize model performance 🔍
Exploring alternative evaluation metrics like precision, recall, and F1-score 📏

Installation and Usage
bashCopy# Clone the repository
git clone https://github.com/YOUR-USERNAME/neural-network-challenge-2.git

# Navigate to the project directory
cd neural-network-challenge-2

# Open the Jupyter notebook
jupyter notebook attrition.ipynb
Technologies Used

Python 3 🐍
TensorFlow/Keras 🧠
Pandas 🐼
NumPy 🔢
Scikit-learn 🧰

Resources

TensorFlow Multi-output Models 🔗
Handling Imbalanced Data in Classification ⚖️
HR Analytics: Using Machine Learning to Predict Employee Turnover 📈
IBM HR Analytics Employee Attrition & Performance Dataset 📊
Neural Networks with Multiple Outputs 🧠
🪨💣 Rock vs Mine Prediction using Machine Learning
📌 Project Overview

This project uses a Logistic Regression machine learning model to classify sonar signals as either a Rock (R) or a Mine (M). The model is trained on the Sonar Dataset and can predict the type of object based on sonar signal measurements.

The project was developed using Python and Google Colab, demonstrating the complete machine learning workflow from data preprocessing to model evaluation and prediction.

🎯 Objectives
Build a binary classification model using Logistic Regression.
Train the model using sonar signal data.
Predict whether an object is a rock or a mine.
Understand machine learning concepts such as data preprocessing, model training, and evaluation.
📊 Dataset

The project uses the Sonar Dataset from the UCI Machine Learning Repository.

Dataset Information
Total Instances: 208
Features: 60 numerical attributes
Target Classes:
R = Rock
M = Mine

Each feature represents the energy of a sonar signal within a particular frequency band.

🛠️ Technologies Used
Python
Google Colab
NumPy
Pandas
Scikit-learn
⚙️ Machine Learning Workflow
Import required libraries
Load the dataset
Explore and preprocess data
Split data into training and testing sets
Train the Logistic Regression model
Evaluate model performance
Predict object type (Rock or Mine) using new input data
🚀 How to Run the Project
Clone the Repository
git clone https://github.com/your-username/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction
Install Dependencies
pip install numpy pandas scikit-learn
Run the Project

Open the notebook in Google Colab or Jupyter Notebook and execute all cells.

📈 Model Performance

The Logistic Regression model was trained and evaluated using a train-test split. Performance metrics such as training accuracy and testing accuracy were used to assess the model.

🔍 Example Prediction

Input:

input_data = (0.02, 0.03, ...)

Output:

The object is a Mine

or

The object is a Rock
📂 Project Structure
Rock-vs-Mine-Prediction/
│
├── sonar_data.csv
├── Rock_vs_Mine_Prediction.ipynb
├── README.md
└── requirements.txt
📚 Learning Outcomes

Through this project, I gained practical experience in:

Data preprocessing
Binary classification
Logistic Regression
Model evaluation
Machine Learning workflow using Scikit-learn
👩‍💻 Author

Imashi Bandara

Machine Learning & Data Science Enthusiast

⭐ Acknowledgements
UCI Machine Learning Repository
Scikit-learn Documentation
Google Colab Platform

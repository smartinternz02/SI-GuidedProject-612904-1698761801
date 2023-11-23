#Fetal Health Monitoring System
Overview:
This project focuses on the development of a fetal health monitoring system utilizing machine learning algorithms. The system analyzes decelerations and relevant parameters to assess the health condition of the fetus. This README file provides comprehensive information about the project, including instructions on usage and contributions.

Table of Contents
Introduction
Features
Installation
Usage
Contributing
Introduction
Fetal health monitoring is crucial for prenatal care, evaluating the well-being of the fetus through the analysis of parameters such as maternal age, blood pressure, heart rate, and uterine contractions. This project aims to develop a fetal health monitoring system using machine learning algorithms. The system processes a dataset containing parameters related to fetal health and maternal well-being, employing machine learning to assess the fetus's health condition based on input parameters.

Features
Data Preprocessing
The system includes modules for data preprocessing, encompassing tasks such as data cleaning, feature selection, and normalization. Ridge regression is utilized for feature selection, and Min-Max scaling normalizes input data to ensure uniformity and prevent feature dominance.

Exploratory Data Analysis (EDA)
EDA capabilities help understand dataset characteristics, identify patterns, outliers, and variable relationships. Visualizations, statistical summaries, and data profiling provide insights, guiding preprocessing and modeling.

Oversampling with SMOTE
To address class imbalance, Synthetic Minority Over-sampling Technique (SMOTE) is incorporated, generating synthetic samples for the minority class, balancing the dataset.

Machine Learning Algorithms
The system supports various algorithms, with Random Forest employed for its ability to handle complex relationships between features. Models are trained on preprocessed and balanced data to classify fetal health conditions effectively.

Model Evaluation
Evaluation metrics, including accuracy, precision, recall, F1 score, and confusion matrix, assess model performance.

Graphical User Interface (GUI)
A user-friendly GUI allows data loading, model selection and training, and visualization of predictions and model performance.

Installation
To install and set up the fetal health monitoring system:

Clone the repository:

bash
Copy code
git clone https://github.com/edilauxillea/FetalAI.git
Navigate to the project directory:

bash
Copy code
cd fetalai
Set up a virtual environment (optional):

bash
Copy code
python3 -m venv venv
source venv/bin/activate
Install required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
To use the fetal health monitoring system:

Ensure the virtual environment (if created) is activated, and you are in the project directory.

Run the GUI application:

bash
Copy code
python gui.py
The GUI window will appear, allowing you to load data, select and train machine learning models, and evaluate their performance.

Follow the instructions in the GUI to perform tasks such as data loading, preprocessing, model selection, training, and performance evaluation.

Explore visualization features in the GUI to analyze prediction results and model performance.

Customize and extend the system by modifying the existing codebase according to specific requirements.

Project Documentation
All files related to brainstorming, ideation, and planning are located in the "project documentation" folder. HTML files are stored in the "templates" folder.

Feel free to contribute to the project and enhance its capabilities!

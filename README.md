# End-to-End Machine Learning Project: Student Performance Prediction

## 📌 Project Overview
This is an end-to-end Machine Learning project designed to predict a student's math score based on various demographic and socio-economic factors (such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course). 

The project covers the entire machine learning lifecycle: from Exploratory Data Analysis (EDA) and data preprocessing to model training, evaluation, and finally deploying a user-friendly web interface using Flask.

## 🚀 Technologies Used
* **Programming Language:** Python
* **Web Framework:** Flask
* **Machine Learning:** Scikit-Learn, CatBoost, XGBoost
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Frontend:** HTML, CSS

## 📁 Project Structure
The repository is structured professionally to separate concerns, making it scalable and easy to maintain:

```text
End-to-End-Machine-Learning-Project/
│
├── artifacts/              # Stores output files like trained models (model.pkl), preprocessors, and data splits (train.csv, test.csv)
├── notebook/               # Jupyter notebooks containing EDA and model experimentation
│   ├── data/               # Raw dataset (stud.csv)
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
├── src/                    # Contains the core source code of the project
│   ├── components/         # Modules for data ingestion, transformation, and model training
│   ├── pipeline/           # Training and prediction pipelines integrating the components
│   ├── exception.py        # Custom exception handling module
│   ├── logger.py           # Logging module for tracking project execution
│   └── utils.py            # Helper functions used across the project
├── templates/              # HTML templates for the Flask web application (home.html, index.html)
├── app.py                  # Main entry point for the Flask web application
├── requirements.txt        # List of project dependencies and libraries
└── setup.py                # Setup script to package the project as a Python module
## Project Structure
<img width="5875" height="917" alt="1" src="https://github.com/user-attachments/assets/586f5358-be66-4776-953f-132b84939a23" />

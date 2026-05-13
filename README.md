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
<img width="5875" height="917" alt="1" src="https://github.com/user-attachments/assets/586f5358-be66-4776-953f-132b84939a23" />

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
```
## 📊 Model Performance
Multiple regression models were trained and evaluated. The performance was measured using R2 Score, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

The Ridge and Linear Regression models yielded the best results on the test data.
<img width="337" height="349" alt="models_per" src="https://github.com/user-attachments/assets/5aabe0fb-9045-4a9a-9c2e-322997dcbc59" />

## 🛠️ Installation and Setup

To run this project locally, follow these steps:

**1. Clone the repository:**

```bash
git clone [https://github.com/AyaRabee21/End-to-End-Machine-Learning-Project.git](https://github.com/AyaRabee21/End-to-End-Machine-Learning-Project.git)
cd End-to-End-Machine-Learning-Project

```

**2. Create a virtual environment:**
It is highly recommended to use a virtual environment to manage dependencies.

```bash
python -m venv venv

```

**3. Activate the virtual environment:**

* For **Windows**:
```bash
venv\Scripts\activate

```


* For **macOS/Linux**:
```bash
source venv/bin/activate

```



**4. Install the required dependencies:**

```bash
pip install -r requirements.txt

```

**5. Run the Flask Web Application:**

```bash
python app.py

```

**6. Access the App:**
Open your web browser and go to `http://127.0.0.1:5000/` to interact with the prediction interface.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

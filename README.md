# 🚦 AI Traffic Predictor

A machine learning project for analyzing and predicting traffic volume in Bengaluru using historical traffic data, data preprocessing, and Automated Machine Learning (AutoML) techniques.

## 📌 Overview

Traffic congestion is a major urban challenge that affects daily commutes, travel time, and transportation planning. This project explores how machine learning can be used to analyze traffic patterns and estimate traffic volume from available traffic data.

The project combines data analysis, feature preparation, model experimentation, and an interactive application to demonstrate an end-to-end traffic prediction workflow.

## ✨ Key Features

- **Traffic Volume Prediction:** Uses historical traffic data to estimate traffic volume.
- **Data Preprocessing:** Prepares datasets for machine learning experiments.
- **Exploratory Data Analysis:** Examines data patterns and relationships using profiling and analysis tools.
- **Automated Machine Learning:** Uses AutoML frameworks to simplify model comparison and pipeline development.
- **Interactive Application:** Provides a Streamlit-based interface for interacting with the prediction workflow.
- **Model Experimentation:** Supports iterative experimentation with different data preparation and modelling approaches.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computations |
| Scikit-learn | Machine learning utilities and preprocessing |
| PyCaret | Automated machine learning and model comparison |
| TPOT | Automated machine learning pipeline optimization |
| Streamlit | Interactive web application |
| YData Profiling | Exploratory data analysis and dataset profiling |
| Pickle | Serialization of Python objects and trained models, where used |

## ⚙️ How It Works

1. **Data Input:** Loads the available Bengaluru traffic dataset.
2. **Data Preparation:** Cleans and prepares the data for analysis and modelling.
3. **Exploratory Analysis:** Examines dataset characteristics and identifies useful patterns.
4. **Model Experimentation:** Applies machine learning and AutoML tools to explore suitable prediction pipelines.
5. **Prediction:** Uses the selected model and relevant input features to estimate traffic volume.
6. **Application Interface:** Presents the prediction workflow through an interactive Streamlit application.

## 📂 Project Structure

The repository contains the project inside the following directory:

```text
Traffic-Predictor/
├── README.md
└── Bangalore-Traffic-Prediction-App-AutoML-tpot-pycaret-ydataprofiling--main/
    ├── main7.py
    ├── main.py
    ├── main2.py
    ├── main3.py
    ├── ...
    ├── Banglore_traffic_Dataset.csv
    ├── Traffic_Test_Dataset.csv
    └── Cleaned_Traffic_Test_Dataset.csv
```

The listed Python scripts represent different iterations of the application and experimentation workflow. Dataset files support data preparation, testing, and analysis.

## 🚀 Getting Started

### Prerequisites

- Python
- pip
- The project files and required datasets

### 1. Clone the Repository

```bash
git clone https://github.com/Lavanya77-mvn/Traffic-Predictor.git
cd Traffic-Predictor
```

### 2. Navigate to the Project Directory

```bash
cd Bangalore-Traffic-Prediction-App-AutoML-tpot-pycaret-ydataprofiling--main
```

### 3. Install Dependencies

If the project contains a `requirements.txt` file, install its dependencies:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies required by the application and its selected model pipeline.

### 4. Run the Application

If `main7.py` is the working Streamlit entry point, run:

```bash
streamlit run main7.py
```

Open the local URL displayed in the terminal to access the application.

## 🎯 Applications

- Traffic pattern analysis
- Traffic volume estimation
- Machine learning experimentation
- Automated model selection and pipeline development
- Data-driven transportation analysis

## ⚠️ Limitations

Predictions depend on the available dataset, the selected model, and the input features. Estimated traffic volume should not be interpreted as guaranteed live traffic conditions unless a live data source is explicitly integrated.

## 🔮 Future Improvements

- Evaluate different models using consistent validation metrics.
- Improve feature engineering and data quality.
- Add clear model evaluation reports and visualizations.
- Develop a more comprehensive prediction interface.
- Explore integration with real-time traffic data sources.

## 📄 Project Information

**Category:** Machine Learning · AutoML · Data Science

**Primary Language:** Python

**Focus:** Traffic Prediction and Data Analysis

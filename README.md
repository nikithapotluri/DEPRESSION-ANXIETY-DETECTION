# DEPRESSION-ANXIETY-DETECTION

This project aims to predict the severity of **depression** and **anxiety** using various machine learning models. The project uses labeled data containing psychological features, standardizes the data, trains multiple models, and evaluates their performance.

## 🧠 Problem Statement

Mental health issues such as depression and anxiety are increasingly common, and early detection through data-driven methods can be helpful in diagnosis and treatment. This project builds ML models that classify the severity of depression and anxiety based on input features.

## 📁 Dataset

- The dataset should contain labeled values for:
  - `depression_severity`
  - `anxiety_severity`
  - and associated features (e.g., survey responses, psychological scores)
- Ensure the dataset is preprocessed and split into training and test sets:
  - `x_train`, `x_test`
  - `y_train`, `y_test`

> **Note**: Dataset is not provided in this repository. Please use your own or any open-source mental health dataset.

## 📌 Technologies Used

- Python

## 📊 Evaluation Metrics

- Accuracy Score
- Precision, Recall, F1-Score
- Confusion Matrix (visualized using Seaborn heatmaps)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mental-health-ml.git
   cd mental-health-ml

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook or Python script:
   python mental_health_prediction.py


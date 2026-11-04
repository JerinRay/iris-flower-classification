# 🌸 Iris Flower Classification using Machine Learning

A Machine Learning-powered web application built with **Python and Streamlit** to classify Iris flowers into three species based on their physical measurements.

## 📌 Project Overview

This project uses supervised machine learning to predict the species of an Iris flower based on four input features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The application provides an interactive Streamlit interface where users can enter flower measurements and obtain a predicted species.

The model is trained and evaluated using the Iris dataset.

## 🎯 Project Objectives

- Build a supervised machine learning classification model.
- Perform data analysis and model training using Python.
- Evaluate model performance using classification metrics.
- Visualize model performance through a confusion matrix.
- Deploy an interactive prediction interface using Streamlit.
- Integrate a trained model into a web application.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Scikit-learn | Machine learning |
| Matplotlib | Data visualization |
| Seaborn | Visualization |
| Streamlit | Web application |
| Joblib / Pickle | Model serialization |
| Jupyter Notebook | Model development and experimentation |

## 📊 Dataset Description

The project uses the Iris flower dataset, containing measurements from three flower species:

1. Setosa
2. Versicolor
3. Virginica

**Input Features:**

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

**Target Variable:** Iris Species

## 🧠 Model Development

The machine learning workflow includes:

1. Dataset loading and exploration.
2. Data preprocessing.
3. Feature selection.
4. Model training.
5. Model evaluation.
6. Model serialization.
7. Integration with Streamlit.

The trained model is stored in the `models/` directory and loaded by the application for predictions.

## 📈 Model Evaluation

The training notebook includes the following evaluation methods:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

### Observed Test Results

The displayed notebook evaluation shows:

| Metric | Result |
|---|---:|
| Test Accuracy | 100% |
| Test Samples | 30 |
| Correct Predictions | 30 |
| Incorrect Predictions | 0 |

The confusion matrix shows correct classification for all three Iris species in the displayed test set.

*Note: These are the results shown in the current notebook execution, not a guarantee of performance on unseen real-world data.*

## 📁 Project Structure

```text
iris-flower-classification/
│
├── models/
│   ├── feature_ranges.json
│   ├── iris_model.joblib
│   ├── iris_model.pickle
│   └── model_info.json
│
├── app.py
├── training.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/JerinRay/iris-flower-classification.git
```

### 2. Navigate to the Project Directory

```bash
cd iris-flower-classification
```

### 3. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 4. Activate the Virtual Environment

For macOS / Linux:

```bash
source venv/bin/activate
```

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

```text
http://localhost:8501
```

## 🚀 Application Features

- Interactive flower measurement inputs.
- Machine learning-based species prediction.
- Trained model integration.
- Easy-to-use Streamlit interface.
- Classification of three Iris flower species.

## 🔮 Future Improvements

- Compare multiple classification algorithms.
- Implement hyperparameter optimization.
- Add interactive data visualizations.
- Improve model explainability.
- Deploy the application to Streamlit Community Cloud.
- Add more comprehensive model validation.

## 👨‍💻 Author

**JerinRay**

GitHub: https://github.com/JerinRay

Project Repository: https://github.com/JerinRay/iris-flower-classification

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with Python, Machine Learning, and Streamlit.**
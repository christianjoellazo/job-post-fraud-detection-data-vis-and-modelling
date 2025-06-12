# job-post-fraud-detection-data-vis-and-modelling

# 🕵️‍♂️ Job Post Fraud Detection

This project identifies and classifies fraudulent job postings using machine learning and data visualization techniques. It utilizes a dataset sourced from Kaggle: [Real or Fake Job Posting Prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction).

## 📌 Objectives

- Understand the characteristics of fraudulent job postings
- Visualize patterns and trends in the dataset
- Train a machine learning model to predict fraud likelihood

## 📁 Dataset

The dataset `fake_job_postings.csv` contains job descriptions along with a `fraudulent` column (target variable: 1 = fake, 0 = real). It includes fields such as:

- `title`
- `location`
- `company_profile`
- `description`
- `requirements`
- `benefits`
- and more...

## 🛠️ Features Implemented

- 📊 Data Exploration & Visualization
- 🧹 Data Cleaning & Preprocessing
- 🔍 Feature Engineering (e.g., text length, keyword presence)
- 🤖 Classification using machine learning models
- 📈 Model evaluation using accuracy, precision, recall

## 🚀 Setup Instructions

1. **Clone this repository** (or download this notebook):
    ```bash
    git clone https://github.com/yourusername/job-post-fraud-detection.git
    cd job-post-fraud-detection
    ```

2. **Install dependencies**:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
    ```

3. **Run the notebook**:
    Open `job-post-fraud-detection-data-vis-and-modelling.ipynb` in Jupyter or Google Colab.

4. **Dataset download**:
    The dataset is pulled automatically using:
    ```python
    import kagglehub
    kagglehub.dataset_download("shivamb/real-or-fake-fake-jobposting-prediction")
    ```

## 🧠 Model Insights

- Fake posts often have vague descriptions, no benefits, or empty company profiles.
- Classification models (e.g., Logistic Regression, Random Forest) can detect these patterns with >90% accuracy after cleaning.

## 🧾 License

MIT License. This project is for educational and research purposes.

---

*Created on 6/12/2025 as part of a hands-on data science activity.*

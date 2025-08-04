# 🧠 Personality Type Predictor

This project builds a machine learning model that predicts whether a person is an **introvert** or **extrovert** based on behavioral and social interaction features. The model uses a **Random Forest Classifier** trained on labeled survey data.

## 📌 Project Description

This notebook aims to explore personality traits through a set of features like:
- Time spent alone
- Stage fear
- Social event attendance
- Frequency of going outside
- Feelings after socializing
- Size of friend circle
- Posting frequency on social media

These features are used to predict the **Personality Type** of individuals (either `Introvert` or `Extrovert`) using supervised machine learning techniques.

---

## 🔍 Dataset

The dataset is stored in a CSV file and contains the following columns:
- `Time_spent_Alone` *(numeric)*
- `Stage_fear` *(categorical: Yes/No)*
- `Social_event_attendance` *(numeric)*
- `Going_outside` *(numeric)*
- `Drained_after_socializing` *(categorical: Yes/No)*
- `Friends_circle_size` *(numeric)*
- `Post_frequency` *(numeric)*
- `Personality` *(target: Introvert/Extrovert)*

---

## 🧪 Project Workflow

1. **Data Loading & Wrangling**
    - Reads the CSV file
    - Displays structure and missing values

2. **Exploratory Data Analysis**
    - Uses `Seaborn` and `Matplotlib` for correlation heatmaps
    - Checks multicollinearity between features

3. **Data Preprocessing**
    - Label Encoding for categorical variables
    - Standard Scaling of features

4. **Model Training**
    - Splits data into training and test sets
    - Trains a `RandomForestClassifier`
    - Evaluates model performance using accuracy and classification report

5. **Hyperparameter Tuning**
    - Uses `GridSearchCV` to optimize the Random Forest model

---

## 🧰 Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📈 Results from visuaization File

#### Countplot

** Class Imbalance:**

- The dataset is imbalanced, with a significantly higher number of Extroverts compared to Introverts.

- Extroverts: Approximately 13,000 samples.

- Introverts: Approximately 4,500 samples.

- This imbalance could impact model performance, especially if the model tends to predict the majority class more frequently

---


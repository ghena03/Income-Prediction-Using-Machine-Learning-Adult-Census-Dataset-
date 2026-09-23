# 💰 Income Prediction Using Machine Learning

An end-to-end Machine Learning project that predicts whether an individual's annual income is **above or below $50K** using demographic and socioeconomic information from the **Adult Census Income Dataset**.

The project combines **Data Analysis, Machine Learning, and a Telegram Bot** to turn the trained model into an interactive application.

>  **My First AI/ML Project**
>
> This was my **first hands-on project in Artificial Intelligence and Machine Learning**. I built it as a learning experience to understand the complete ML workflow — from working with a real-world dataset and preprocessing the data to training a model, evaluating its performance, and integrating the model into a Telegram Bot.

---

## 📌 Project Overview

The goal of this project is to predict an individual's income category based on information such as:

* Age
* Workclass
* Education
* Education Number
* Marital Status
* Occupation
* Relationship
* Race
* Gender
* Capital Gain
* Capital Loss
* Hours per Week
* Native Country

The model predicts one of two income categories:

* **`<=50K`**
* **`>50K`**

---

## 🤖 Telegram Bot

To make the project more practical and interactive, I also developed a **Telegram Bot** that allows users to interact with the Machine Learning model directly through Telegram.

Instead of running predictions manually through a notebook, users can provide the required information through the bot and receive an income prediction.

### 🔄 How It Works

```text
User
  ↓
Telegram Bot
  ↓
User Information
  ↓
Data Preprocessing
  ↓
Trained ML Model
  ↓
Income Prediction
  ↓
Prediction Returned to User
```

This allowed me to take the Machine Learning model beyond experimentation in a Jupyter Notebook and integrate it into a real user-facing application.

---

## 🧠 Machine Learning Workflow

The project follows an end-to-end Machine Learning pipeline:

```text
Adult Census Dataset
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Data Preprocessing
        ↓
Feature Encoding
        ↓
Train / Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Income Prediction
        ↓
Telegram Bot Integration
```

---

## 🔍 Exploratory Data Analysis

The dataset was explored to understand the relationships between different features and income.

The analysis includes examining:

* Income distribution
* Education and income relationships
* Age and income patterns
* Working hours and income
* Occupation and income
* Categorical feature distributions
* Relationships between demographic and socioeconomic attributes

Data visualization was used to identify patterns and better understand the dataset before building the Machine Learning model.

---

## ⚙️ Data Preprocessing

Because the dataset contains both numerical and categorical features, preprocessing was required before training the model.

The preprocessing process includes:

* Handling missing values
* Cleaning categorical data
* Encoding categorical variables
* Preparing numerical features
* Splitting the data into training and testing sets
* Preparing user input for prediction

---

## 🤖 Machine Learning

The processed dataset is used to train a classification model that learns patterns from the available data and predicts the income category of previously unseen data.

The model is evaluated using common classification metrics, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🛠️ Technologies Used

### Programming Language

* **Python**

### Data Analysis & Visualization

* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

### Machine Learning

* **Scikit-learn**

### Development

* **Jupyter Notebook**

### Application Integration

* **Telegram Bot API**

---

## 📂 Project Structure

```text
Income-Prediction-Using-Machine-Learning-Adult-Census-Dataset/
│
├── 📓 Jupyter Notebook
├── 🤖 Telegram Bot
├── 📊 Dataset
├── 📄 README.md
└── ...
```

The exact file structure may vary depending on the current repository contents.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ghena03/Income-Prediction-Using-Machine-Learning-Adult-Census-Dataset.git
```

### 2. Navigate to the Project

```bash
cd Income-Prediction-Using-Machine-Learning-Adult-Census-Dataset
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

If the Telegram Bot uses an additional Telegram library, install the required package according to the bot implementation.

### 4. Run the Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells to reproduce the analysis and Machine Learning workflow.

---

## 📊 Dataset

This project uses the **Adult Census Income Dataset**, a widely used dataset for classification and Machine Learning experiments.

The dataset contains demographic and employment-related information that can be used to classify individuals according to their annual income.

---

## 🎓 What I Learned

Since this was my **first practical AI/ML project**, it helped me build a foundation in several important areas:

* Understanding the Machine Learning workflow
* Working with real-world datasets
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Data visualization
* Handling categorical data
* Feature preparation
* Training classification models
* Evaluating model performance
* Making predictions on new data
* Integrating a Machine Learning model into an application
* Building a Telegram Bot
* Connecting AI/ML concepts with a practical user-facing application

Most importantly, this project gave me my first experience with taking an idea from **raw data → Machine Learning model → working application**.

---

## 🔮 Future Improvements

Some possible improvements include:

* Comparing multiple Machine Learning algorithms
* Hyperparameter tuning
* Feature selection and engineering
* Improving prediction performance
* Handling class imbalance
* Improving the Telegram Bot interface
* Adding more detailed prediction explanations
* Building a web-based interface
* Deploying the model as an API
* Containerizing the application with Docker

---

## 👩‍💻 Author

### Ghena Ali

**Computer Engineering Graduate**

GitHub: [@ghena03](https://github.com/ghena03)

---

## ⭐ Project Note

This project represents the **beginning of my journey in Artificial Intelligence and Machine Learning**.

It was my **first hands-on AI/ML project**, where I learned how to work with a real dataset, build and evaluate a Machine Learning model, and then integrate that model into a Telegram Bot to create a more practical user experience.

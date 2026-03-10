---

# 🏠 Predictive Modelling-Based Automatic Valuation Model (AVM) for Residential Properties in Malaysia

A machine learning–driven **Automatic Valuation Model (AVM)** and **Housing Market Risk Assessment System** designed to estimate residential property prices and analyze housing market conditions in Malaysia.

This project integrates **property transaction data, macroeconomic indicators, and market sentiment signals** to build predictive models and provide transparent housing market insights for buyers, real estate professionals, and policymakers.

---

# 📌 Project Overview

The Malaysian residential property market often suffers from **information asymmetry**, where buyers and investors lack reliable estimates of a property's true market value. Online property portals frequently display **asking prices**, which may differ significantly from actual transacted prices.

This project addresses that issue by developing a **data-driven Automatic Valuation Model (AVM)** that predicts realistic property price ranges using historical transaction data and macroeconomic factors.

The system is composed of **three analytical components**:

1. **Property Price Prediction (AVM)**
2. **Housing Market Sentiment Index**
3. **Housing Market Risk Assessment**

Together, these components provide a **holistic view of the Malaysian property market**.

---

# 🎯 Objectives

The main objectives of this project are:

* Develop a **machine learning-based Automatic Valuation Model (AVM)** for predicting residential property prices in Malaysia.
* Construct a **Housing Market Sentiment Index** using Google Trends search volume data.
* Analyze **housing market risk and cycle conditions** using macroeconomic indicators.
* Deploy the predictive model as an **interactive web application** for public use.

---

# 🧠 Methodology

The project follows a **three-step analytical framework**.

---

## Step 1: Property Price Prediction (Automatic Valuation Model)

Machine learning models are trained on property transaction data to estimate residential property prices.

### Models Implemented

* **Multiple Linear Regression (MLR)**
* **Random Forest Regression**
* **Artificial Neural Networks (ANN)**

### Evaluation Metrics

Models are evaluated using:

* **RMSE (Root Mean Square Error)**
* **MAE (Mean Absolute Error)**
* **R² (Coefficient of Determination)**

The best-performing model is selected for deployment in the final system.

---

## Step 2: Malaysian Housing Sentiment Index

Public sentiment toward the housing market is captured using **Google Trends search volume data**.

### Process

1. Select relevant **property-related keywords** (e.g., "house price Malaysia", "home loan Malaysia").
2. Retrieve search interest values from **Google Trends**.
3. Aggregate and normalize the search data.
4. Construct a **composite Housing Sentiment Index**.

This index captures **market optimism or pessimism** reflected through online search behavior.

---

## Step 3: Housing Market Risk Assessment

Macroeconomic indicators are used to assess **housing market cycle risks**.

Key indicators include:

* GDP growth
* Interest rates
* Housing supply indicators
* Loan impairment statistics
* House Price Index trends

These variables are analyzed to identify **periods of market overheating, stability, or downturn risk**.

---

# 📊 Data Sources

The system integrates multiple official Malaysian datasets:

### 1️⃣ NAPIC Property Transaction Data

Source:
**National Property Information Centre (NAPIC)**

Contains:

* Residential property transaction prices
* Property characteristics
* Location attributes
* Transaction timing

---

### 2️⃣ CEIC Macroeconomic Data

Macroeconomic indicators sourced from **CEIC CDMNext platform**, including:

* GDP growth
* Inflation
* Interest rates
* Construction activity
* Housing supply indicators

---

### 3️⃣ Bank Negara Malaysia (BNM)

Banking system indicators used for financial risk analysis:

* Impaired housing loan statistics
* Household debt indicators

---

### 4️⃣ Google Trends Data

Google Trends provides **search interest signals** reflecting market sentiment.

Example keywords:

* "house price Malaysia"
* "buy house Malaysia"
* "home loan Malaysia"
* "property Malaysia"

---

# ⚙️ System Architecture

The project pipeline consists of the following stages:

```
Data Collection
      ↓
Data Cleaning & Feature Engineering
      ↓
Machine Learning Model Training
      ↓
Model Evaluation & Selection
      ↓
Sentiment Index Construction
      ↓
Housing Market Risk Analysis
      ↓
Web Application Deployment
```

---

# 💻 Technology Stack

### Programming

* Python

### Machine Learning

* Scikit-learn
* TensorFlow / Keras
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Web Application

* React (Frontend)
* Flask / FastAPI (optional backend)

### Development Environment

* Jupyter Notebook
* Python Virtual Environment

---

# 📈 Example Features Used in the Model

Typical model features include:

* Property type
* Built-up area
* Location
* Number of bedrooms
* Transaction year
* Macroeconomic indicators
* Market sentiment index

---

# 🌐 Web Application (Planned)

The final system will be deployed as a **React-based web application**.

Features will include:

### 🏠 Property Price Estimator

Users can input:

* Property type
* Size
* Location
* Bedrooms

The system returns an **estimated price range**.

---

### 📊 Housing Market Dashboard

Displays:

* Housing Sentiment Index trends
* Housing Market Risk Indicator
* Key macroeconomic drivers

---

# 📂 Repository Structure

```
AVM-Malaysia
│
├── data
│   ├── napic_transactions
│   ├── macroeconomic_data
│   └── google_trends
│
├── notebooks
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── sentiment_index.ipynb
│
├── models
│   └── trained_models
│
├── web_app
│   ├── frontend (React)
│   └── backend (API)
│
├── results
│   └── model_evaluation
│
└── README.md
```

---

# 📊 Example Output

The AVM generates:

* **Estimated Property Value**
* **Prediction Confidence Range**
* **Market Sentiment Level**
* **Housing Market Risk Indicator**

Example:

```
Estimated Property Value: RM 520,000
Prediction Range: RM 490,000 – RM 550,000
Market Sentiment: Neutral
Housing Market Risk Level: Moderate
```

---

# 📚 Academic Context

This project is developed as part of a **Final Year Project (FYP)** focusing on:

**Machine Learning Applications in Real Estate Valuation**

Key research areas include:

* Property price prediction
* Housing market analytics
* Market sentiment analysis
* Financial stability indicators

---

# 🌍 Societal Impact

The system supports **United Nations Sustainable Development Goal (SDG) 11: Sustainable Cities and Communities** by improving **transparency and accessibility of housing market information**.

Benefits include:

* Helping buyers estimate fair property prices
* Supporting real estate professionals in valuation analysis
* Providing policymakers with housing market insights

---

# 🚀 Future Improvements

Potential future enhancements include:

* Integration with **real-time property listings**
* Use of **Natural Language Processing (NLP)** on housing news
* Deep learning models for improved accuracy
* Expanded dataset covering **longer historical periods**
* Geographic visualization using **GIS mapping**

---

# 👨‍💻 Author

**Voon Kai Wen**
Asia Pacific University of Technology & Innovation (APU)

Final Year Project – 2025

---

# 📜 License

This project is developed for **academic research purposes**.
Data sources remain the property of their respective providers.

---


# 📱 Mobile Price Prediction



Predict mobile phone prices using machine learning regression models with an interactive Gradio interface for real-time usage.

---

## 🗂️ Table of Contents

- 📖 Overview
- 💡 Features
- 📊 Dataset
- ⚙️ Installation
- 🚀 Usage
- 📈 Results


---

## 📖 Overview

This project implements a **regression pipeline** to estimate mobile phone prices based on their specifications.

### 🔧 Key Components

- Data Cleaning and EDA
- Feature Scaling
- Model Training (Linear Regression, Random Forest, Gradient Boosting)
- Hyperparameter Tuning using GridSearchCV
- Evaluation with RMSE, MAE, and R²
- Deployment with **Gradio** UI for interactive predictions

---

## 💡 Features

✅ Load and preprocess dataset  
✅ Visualise correlations and outliers  
✅ Train multiple regression models  
✅ Evaluate performance metrics  
✅ Deploy a Gradio-based web app for live predictions

---

## 📊 Dataset

- **File:** `final_mobile_price_data.csv`
- **Description:** Mobile specifications with their respective prices.
- **Source:** Collected from open sources and kaggle

---

## ⚙️ Installation

### 1. Clone this repository

```bash
git clone https://github.com/yourusername/mobile-price-predictor.git
cd mobile-price-predictor
```
### 2. Create virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows
```
### 3. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn gradio
```
## 🚀 Usage

### ▶️ Run the Notebook

1. Open `Final_model_predictor.ipynb` in **Jupyter Notebook**, **VS Code**, or **Google Colab**.

> 💡 **Tip:** Better run it on **Colab with GPU access** for easy and faster execution.

2. Execute all cells sequentially to:
   - Load and analyse data
   - Train and evaluate models
   - Launch Gradio app

---

## 📈 Results

### 🔢 Model Evaluation

| Model                   | RMSE | MAE | R² Score |
|--------------------------|------|-----|----------|
| Linear Regression       | 6608.60   | 5277.82  | 0.84       |
| Random Forest Regressor | 5716.11   | 4226.8  | 0.88       |
| Gradient Boosting       | 5934.55   | 4602.22  | 0.87       |


### 📊 Visual Outputs

- Correlation Heatmap
- Boxplots for outlier analysis
- Feature importance plots (if implemented)

---
### 🌐 Gradio Output Visualization

The **Gradio interface** provides an interactive web-based UI for predicting mobile phone prices:

- 📝 **Input Panel:**  
  Users enter mobile phone specifications (e.g. RAM, ROM, battery capacity, camera resolution) into the respective input fields.

- 🔮 **Output Panel:**  
  Displays the **predicted price** of the mobile phone based on the trained machine learning model.

- 📊 **Interface Design:**  
  Clean, minimalistic layout with labelled input components for ease of use, and real-time inference on submission.

- ⚡ **Execution:**  
  As soon as inputs are provided and **Submit** is clicked, the model processes them and returns the price instantly without needing to refresh or rerun the notebook.

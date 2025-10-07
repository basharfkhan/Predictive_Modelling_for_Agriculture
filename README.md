# 🌱 Soil Measures Analysis
![Farmer in a field](farmer_in_a_field.jpg)

## 📖 Overview
This project focuses on analyzing soil quality measures using Python.  
It combines **data exploration, visualization, and machine learning** to provide insights that can help improve agricultural practices.  

The project is organized into a **Jupyter Notebook** for reproducible analysis and a dataset (`soil_measures.csv`) containing soil metrics.  

---

## 🎯 Objectives
- ✔️ **Data Cleaning**: Handle missing values and ensure data quality.  
- ✔️ **Exploratory Data Analysis (EDA)**: Visualize soil measures and identify key patterns.  
- ✔️ **Modeling**: Build predictive models to estimate soil conditions or crop suitability.  
- ✔️ **Visualization**: Create charts and plots for intuitive understanding.  

---

## 📂 Repository Contents
- **ProjectNotebook.ipynb** → Clean notebook with full analysis (outputs cleared for readability).  
- **soil_measures.csv** → Dataset used for analysis.  
- **farmer_in_a_field.jpg** → Visual asset for project context.  
- **README.md** → Project documentation.  

---

## 🔧 Technologies Used
- **Python**  
- **Pandas / NumPy** → Data manipulation  
- **Matplotlib / Seaborn** → Data visualization  
- **Scikit-learn** → Machine learning (multi-class classification models)  
- **Jupyter Notebook** → Interactive analysis  

---

## 📊 Key Insights 
- The dataset includes **soil nutrient ratios** (Nitrogen, Phosphorous, Potassium) and **pH values**, used to predict the best crop for given soil conditions.  
- **Potassium (K)** is the **most important soil feature** for predicting crops, with the highest F1-score contribution (~0.28).  
- Other features like **Nitrogen (N)** and **Phosphorous (P)** also influence predictions but less strongly.  
- The dataset covers **22 different crops**, including rice, maize, pulses, fruits, and cash crops like cotton and coffee.  
- A multi-class classification approach enables farmers to match soil profiles with the **optimal crop choice** to maximize yield.  

---

## 🚀 Getting Started
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/soil-measures-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook ProjectNotebook_Clean.ipynb
   ```

---

## 📜 License
This project is for educational purposes.  
You are free to use the code with attribution, but please do not use the dataset for commercial purposes without permission.  

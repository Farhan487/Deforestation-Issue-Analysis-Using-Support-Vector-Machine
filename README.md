
## 🌳 Deforestation Issue Analysis Using Support Vector Machine (SVM)

This project uses machine learning (Support Vector Machine) to understand and predict deforestation based on real-world data from different countries.

---

### 📁 Dataset

We used a CSV file: `deforestation_dataset.csv`, which contains data like:

* **CO2 emissions**
* **GDP**
* **Population**
* **Rainfall**
* **Forest loss (in km² and %)**
* **Policy and corruption indexes**

---

### 🔍 Objective

We want to:

1. Find which factors are causing deforestation.
2. Predict forest loss using those factors.
3. Recommend actions to help reduce deforestation.

---

### 🧪 What We Did

#### ✅ 1. Data Preprocessing

* **Loaded the CSV file** using pandas.
* **Cleaned the data** by filling missing values.
* **Converted text columns to numbers** using label encoding.
* **Standardized the data** so the SVM model works better.
* **Split the data** into training and test sets (80/20).

#### ✅ 2. Built the Model

* We used **SVM (Support Vector Machine)** with a linear kernel.
* Predicted the `Tree_Cover_Loss_percent`.
* Measured model performance using:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)
  * R² Score (how well the model fits the data)

#### ✅ 3. Feature Analysis

* Found the most important features (e.g., CO2 emissions, GDP).
* Created graphs to show how each feature affects forest loss.

#### ✅ 4. Reporting and Recommendations

* Made charts like heatmaps and scatter plots.
* Wrote insights and suggestions to reduce deforestation:

  * Strengthen policy laws
  * Reduce emissions
  * Encourage eco-friendly development

---

### 📈 Results

The model was able to:

* Identify key reasons behind deforestation.
* Predict forest loss based on different country statistics.

---

### 🛠 Libraries Used

* `pandas` – data loading and cleaning
* `numpy` – number handling
* `scikit-learn` – machine learning (SVM, preprocessing)
* `matplotlib` & `seaborn` – for plotting and visualizations

---

### 📄 How to Run the Notebook

1. Open the Jupyter Notebook (`.ipynb`) file.
2. Run each cell step by step (from top to bottom).
3. Read the comments and markdown cells to follow the explanation.
4. View the graphs and results to understand what's happening.

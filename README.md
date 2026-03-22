# Diabetes Health Indicators - Exploratory Data Analysis (EDA) 🩸📊

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) to investigate health indicators associated with diabetes. Using Python, the project aims to clean, analyze, and visualize a healthcare dataset to uncover patterns, correlations, and outliers that could indicate higher health risks for individuals.

## ⚙️ Key Insights & Visualizations
By utilizing statistical analysis and data visualization techniques, several critical insights were extracted:
* **Glucose Variability:** A significant variance (1022.51) and standard deviation (31.97) in glucose levels were observed, indicating that outliers in this feature strongly reflect individuals with greater health risks.
* **Feature Correlation:** A heatmap analysis revealed a strong positive correlation between Glucose levels and the final Diabetes Outcome, as well as a noticeable correlation between BMI and Insulin levels.
* **Data Distribution:** * **Pregnancies:** The majority of individuals had between 0 to 5 pregnancies.
  * **Skin Thickness & Insulin:** Heavy skewness and potential missing data (represented as zero values) were identified, highlighting areas that require preprocessing.
* **BMI & Blood Pressure Analysis:** Scatter plots showed a weak direct correlation between BMI and Blood Pressure, while boxplots indicated relatively normal distributions without extreme outliers for blood pressure.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📂 Repository Structure
* `finalPythonProject.ipynb`: The main Jupyter Notebook containing the Python code, statistical functions, and inline visualizations.
* `Images/`: Directory containing the generated charts:
  * Heatmap (`correlation.jpg`)
  * Boxplots (`diabetesBoxplot.jpg`)
  * Scatter plots (`scatterplot.jpg`)
  * Histograms & Distribution plots (`pregnanciesHist.jpg`, `adeHisto.jpg`)
* `paython projectt.docx`: Comprehensive project documentation detailing the statistical significance of the findings.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Youssef/Diabetes-EDA-Python.git](https://github.com/Youssef/Diabetes-EDA-Python.git)

# Task 1: Iris Dataset Analysis

**Internship:** Data Science & Analytics  
**Organization:** DevelopersHub Corporation  
**Author:** Auzah Mansoor
**Date:** 28/11/2025

---

## **1. Introduction**

This project explores the **Iris dataset**, a classic dataset in machine learning and data science.  
The main objective of this task is to **perform data exploration, visualization, and basic modeling** using Python libraries like `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.  

---

## **2. Problem Statement**

We aim to understand the characteristics of different Iris species by analyzing their **sepal and petal measurements**. The task involves:

1. Loading and inspecting the dataset  
2. Performing exploratory data analysis (EDA)  
3. Visualizing relationships between features  
4. Training a simple machine learning model to classify species  
5. Evaluating model performance  
6. Drawing key insights and conclusions  

---

## **3. Dataset Description**

- **Dataset:** Iris  
- **Number of Samples:** 150  
- **Number of Features:** 4 numeric + 1 categorical target (`species`)  
- **Features:**
  - `sepal_length` (cm)  
  - `sepal_width` (cm)  
  - `petal_length` (cm)  
  - `petal_width` (cm)  
  - `species` (target) – three classes: `setosa`, `versicolor`, `virginica`  

- **Source:** Built-in Seaborn dataset  

---

## **4. Data Cleaning and Preparation**

- Checked for missing values → None found  
- All features are numeric (except the target)  
- Dataset is ready for analysis and modeling  

---

## **5. Exploratory Data Analysis (EDA)**

- **Scatter Plots:** Used to observe relationships between sepal and petal dimensions across species  
- **Histograms:** Show distribution of numeric features  
- **Box Plots:** Detect outliers and understand spread of data  
- **Pairplot:** Visualizes pairwise relationships and clusters for each species  

**Key Insights from EDA:**

- `Setosa` is easily separable from other species based on sepal and petal dimensions  
- Petal length and width are the most distinguishing features  
- Sepal width shows some overlap between `versicolor` and `virginica`  

---

## **6. Model Training and Testing**

- **Model Used:** Random Forest Classifier  
- **Steps:**
  1. Split dataset into training (80%) and testing (20%) sets  
  2. Train the model on the training set  
  3. Make predictions on the test set  
  4. Evaluate performance using accuracy and confusion matrix  

- **Evaluation Metrics:**
  - **Accuracy:** ~100% (due to clearly separable classes)  
  - **Confusion Matrix:** Shows perfect classification for all three species  

---

## **7. Conclusion**

- Iris dataset is simple but ideal for practicing **EDA and basic classification**  
- Visualization clearly shows which features are most important for distinguishing species  
- Random Forest model performs extremely well on this dataset  
- Key features for classification: `petal_length` and `petal_width`  
- This task demonstrates a complete workflow: **data understanding → visualization → modeling → evaluation → insights**  

---

## **8. Libraries Used**

- `pandas` – data loading and manipulation  
- `matplotlib` – plotting basic charts  
- `seaborn` – advanced visualizations  
- `scikit-learn` – machine learning modeling and evaluation  

---

## **9. How to Run**

1. Open `Task1_Iris_EDA.ipynb` in VS Code or Jupyter Notebook  
2. Run all cells sequentially  
3. Visualizations will appear inline  
4. Outputs include summary statistics, plots, and model evaluation metrics  

---

## **10. Project Structure**

TASK 1/
│
├─ Task1_Iris_EDA.ipynb # Jupyter Notebook with analysis and visualizations
├─ README.md # Project explanation (this file)


---

## **11. References**

- [Seaborn Iris Dataset Documentation](https://seaborn.pydata.org/generated/seaborn.load_dataset.html)  
- [Scikit-Learn RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)  

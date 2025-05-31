# 🧠 AI & ML Internship Project — 1-Month Internship at Elevate Labs

This repository showcases the work completed during a one-month AI & ML internship at Elevate Labs. The internship focused on hands-on problem solving using Python for data preprocessing, exploratory data analysis (EDA), visualization, and basic machine learning pipeline preparation. The work is organized into four Jupyter Notebooks, each covering a unique task involving real-world datasets.

---

## 📁 Datasets Used

The following datasets were used across the notebooks:

1. **Titanic-Dataset.csv**  
   - Classic survival dataset used for classification tasks and data preprocessing.
2. **Housing.csv**  
   - Housing prices dataset for regression analysis and feature engineering.
3. **data.csv**  
   - Generic CSV used for EDA, correlation analysis, and visualizations.

---

## 📚 Technologies and Libraries

- **Python 3**
- **Jupyter Notebook**
- **pandas** – Data manipulation and analysis  
- **numpy** – Numerical computations  
- **matplotlib** – Data visualization  
- **seaborn** – Advanced visualization  
- **scikit-learn** – Machine learning utilities (e.g., scaling, model building)  
- **missingno** – Missing data visualizations  
- **warnings** – Suppress warnings for cleaner output  
- **os / sys** – File operations and runtime config

---

## 🔍 Summary of Work

### ✅ Task 1 – Titanic Dataset Preprocessing
-  Dataset: `Titanic-Dataset.csv`
-  Started with a structural overview of the dataset, identifying data types and missing values
-  Treated missing entries using techniques like mean, median, and appropriate imputations
-  Converted categorical variables into numeric format using encoding methods to prepare for analysis
-  Standardized numerical features to ensure consistency in scale across variables
-  Used boxplots to spot outliers and removed them to enhance data quality

### ✅ Task 2 – Exploratory Data Analysis on Titanic Dataset
-  Dataset: `Titanic-Dataset.csv`
-  Computed key statistical metrics such as mean, median, and standard deviation to understand data distribution
-  Created histograms and boxplots to visualize patterns, spreads, and potential outliers in numeric features
-  Explored relationships between variables using pairplots and a correlation heatmap
-  Identified trends, anomalies, and interesting patterns within the dataset
-  Drew basic insights about feature behavior based on the visualizations

### ✅ Task 3 – Linear Regression on Housing Data
-  Dataset: `Housing.csv`
-  Loaded and prepared the housing dataset for modeling by performing necessary preprocessing
-  split the data into training and test sets to validate model performance
-  Trained a Linear Regression model using scikit-learn to predict housing prices
-  Assessed the model using error metrics like MAE, MSE, and R² score
-  Visualized the regression line and interpreted model coefficients to understand the effect of input features

### ✅ Task 4 – Logistic Regression for Binary Classification
-  Dataset: `Data.csv`
-  Chose a binary classification dataset and standardized the feature set after splitting it into training and testing subsets
-  Built and trained a Logistic Regression model to classify the data
-  Valuated model performance using a confusion matrix, along with precision, recall, and ROC-AUC metrics
-  Explained the role of the sigmoid function in logistic regression and how it aids in probability prediction
-  Experimented with adjusting the classification threshold to observe changes in prediction outcomes

## 👩‍💻 Author

**Ellora Mallick Banerji**  
MCA | Front-End Developer | Data Science Enthusiast  
[GitHub Profile](https://github.com/elloramallickbanerji)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

# 🛳️ Titanic Dataset Preprocessing with Python

This project involves preprocessing the Titanic dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn. It prepares the data for future machine learning tasks such as survival prediction.

---

## 📁 Dataset Information

The dataset used is `Titanic-Dataset.csv`, which contains the following features:

- `PassengerId`: Unique identifier for each passenger
- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1, 2, or 3)
- `Name`: Passenger’s full name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: # of siblings/spouses aboard
- `Parch`: # of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## 🧪 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn (for scaling)

---

## 🔧 Steps Performed

### 1. **Data Import and Exploration**
- Loaded the dataset using `pandas.read_csv()`
- Explored dataset structure using `.head()`, `.info()`, and `.isnull().sum()`

### 2. **Handling Missing Values**
- Filled missing `Age` values using the **median**
- Filled missing `Embarked` values using the **mode**
- Dropped the `Cabin` column due to excessive missing data

### 3. **Encoding Categorical Variables**
- Converted `Sex` to numerical: `male → 0`, `female → 1`
- One-hot encoded the `Embarked` column using `pd.get_dummies()`

### 4. **Feature Scaling**
- Standardized numerical features (`Age`, `Fare`, `SibSp`, `Parch`) using `StandardScaler` from `sklearn`

### 5. **Outlier Detection and Removal**
- Visualized numerical features using **boxplots**
- Removed outliers using the **Interquartile Range (IQR)** method

---

## 📊 Example Plots

Boxplots were generated to detect outliers in numerical features such as:

- Age
- Fare
- SibSp
- Parch

---

## 📌 Future Work

- Train a machine learning model (e.g., Logistic Regression or Random Forest)
- Evaluate model accuracy and performance
- Deploy the model for predictions

---

## 🧠 Author

**Ellora Mallick Banerji**  
- MCA | Front-End Developer | Data Science Enthusiast  
- [GitHub Profile](https://github.com/elloramallickbanerji)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

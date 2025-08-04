
# 🛠️ Titanic Dataset Preprocessing – Task 1

This project demonstrates fundamental data preprocessing techniques on the Titanic dataset as part of a data science internship task. It includes steps such as handling missing values, encoding categorical data, feature scaling, and detecting/removing outliers.

---

## 📁 Dataset Used
- **Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **File:** `Titanic-Dataset.csv`

---

## ✅ Tasks Completed

### 1. Handling Missing Values
- Filled missing `Age` values with the **median**
- Filled missing `Embarked` values with the **mode**
- Dropped `Cabin` column due to excessive missing data

### 2. Encoding Categorical Features
- Converted `Sex` column into binary format (male → 0, female → 1)
- One-hot encoded `Embarked` column (with drop-first strategy)

### 3. Feature Scaling
- Applied **Min-Max Normalization** on `Age`, `Fare`, `SibSp`, and `Parch` columns

### 4. Outlier Detection and Removal
- Used the **IQR method** to remove outliers in `Age` and `Fare`

### 5. Visualizations
- Boxplots created to compare:
  - Before vs After Outlier Removal
  - Category-based plots (`Survived` vs `Age`)
  - Age groups vs Survival

---

## 📊 Tools & Libraries Used
- `Python`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Sklearn.preprocessing` for MinMaxScaler

---

## 📌 How to Run

```bash
# Clone the repo (if using GitHub)
git clone <your-repo-url>
cd titanic-preprocessing-task

# Install required libraries
pip install pandas matplotlib seaborn scikit-learn

# Run the script
python titanic_preprocessing.py
```

---

## 👨‍💻 Author
**Mathan G**  
AI & ML Intern at Elevate Labs  
August 2025

# Titanic EDA Project Level 1

This project is a beginner-friendly, end-to-end exploratory data analysis (EDA) and machine learning pipeline based on the Titanic dataset. It was completed using Google Colab and focuses on building strong foundations in data analysis, feature engineering, and model evaluation.

---

##  What’s Covered So Far

### **Level 1: Exploratory Data Analysis (EDA)**

#### Phase 1: Data Loading & Inspection
- Loaded the Titanic dataset (from Seaborn)
- Inspected column types, structure, and null values
- Previewed data using `.head()`, `.info()`, and `.describe()`

#### Phase 2: Data Cleaning
- Handled missing values (`age`, `embarked`)
- Dropped irrelevant or high-missing columns (`ticket`, `cabin`, `fare`)
- Converted columns like `survived` and `pclass` to categorical

#### Phase 3: Exploratory Analysis
- Grouped and compared survival by class, gender, and port
- Analyzed distributions of `sibsp`, `parch`, and `embarked`
- Discussed features that are useful vs not (e.g., title, name)

#### Phase 4: Visualization
- Bar plots for survival across gender and class
- Histograms for age distribution
- Box plots to see variation in age by class
- Combined visualizations using `hue` for richer insights

---
### 🔹 **Level 2: Machine Learning Pipeline**

#### 📌 Phase 5: Feature Engineering
- Created `family_size` from `sibsp + parch`
- Encoded categorical columns using One-Hot Encoding
- Scaled numerical features like `age` and `family_size` using `StandardScaler`
- Dropped unused or less predictive columns (`name`, `ticket`, `embarked`)

#### 📌 Phase 6: Model Training
- Split the data into training and test sets (80/20)
- Trained both Logistic Regression and Random Forest models

#### 📌 Phase 7: Model Evaluation
- Used classification report and confusion matrix
- Compared metrics: precision, recall, F1-score, and accuracy
- Accuracy achieved: ~85% for both models
  
---

##  Tools & Libraries Used
- Python (Google Colab)
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

---

## Dataset
- Titanic dataset is loaded from Seaborn's built-in datasets  
  *(No need to download separately)*

---

## 📈 Results Summary

- Both models performed similarly (~85% accuracy)
- Feature engineering improved learning quality
- Logistic Regression slightly underperformed in precision compared to Random Forest
- Strongest predictors: `sex`, `pclass`, `age`, and `family_size`

---

## 📁 How to Run
- Open the [Google Colab Notebook](https://colab.research.google.com/drive/1WEJsh566Ws7JAQimr4AOFGuvBZV5Bf0x?usp=share_link)
- Run cells top to bottom. All required libraries are pre-installed in Colab.

---

## Author
[Dhanush Polasi](<https://github.com/DhanushP545>)
Feel free to connect with me on [LinkedIn](<https://www.linkedin.com/in/dhanush-polasi-7972252a4/>)!

---

## License
This project is open for learning and sharing. Give credit if you reuse or build upon it.

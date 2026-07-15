# Titanic Survival Prediction

**Internship Project | CodTech IT Solutions**

## Objective
Predict whether a passenger would have survived the Titanic disaster, using features like age, sex, passenger class, fare, and family size. This is a supervised **classification** problem.

## Dataset
`Titanic.csv` — 891 passengers with the following key columns:
- `survived` — target (0 = No, 1 = Yes)
- `pclass` — ticket class (1st, 2nd, 3rd)
- `sex`, `age`, `sibsp` (siblings/spouses aboard), `parch` (parents/children aboard)
- `fare`, `embark_town`

## Approach
1. Exploratory Data Analysis (survival by gender, class, age)
2. Data preprocessing (handling missing values, encoding categorical features, feature engineering — family size)
3. Model training using a **Random Forest Classifier**
4. Evaluation using accuracy, confusion matrix, and classification report
5. Feature importance analysis
6. **Interactive demo** — enter a passenger's details and get a live survival prediction

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open `Titanic_Survival_Prediction.ipynb` in Jupyter Notebook or VS Code
3. Run all cells in order
4. In the last cell, enter passenger details when prompted to get a live prediction

## Results
The Random Forest model achieves ~80% accuracy on the test set. Gender and passenger class turned out to be the strongest predictors of survival.

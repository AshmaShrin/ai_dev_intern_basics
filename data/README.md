# 📊 Data folder

Week 4 uses the **Pima Indians Diabetes Database** from Kaggle. The CSV is not stored in this repository, so you download it once.

## Download steps
1. Create a free account at [kaggle.com](https://www.kaggle.com).
2. Open the dataset page: <https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database>
3. Click **Download** (top right) and unzip the file.
4. Put **`diabetes.csv`** in this folder, so the path is:

```
ai_dev_intern_basics/data/diabetes.csv
```

## What is inside?
768 patients, 8 measurements each, plus an `Outcome` column (1 = diabetes, 0 = no diabetes).

```
Pregnancies,Glucose,BloodPressure,SkinThickness,Insulin,BMI,DiabetesPedigreeFunction,Age,Outcome
```

Check the dataset page for the licence and for a description of each column.

> The file is listed in `.gitignore` on purpose: it is good practice not to commit data files you can download.

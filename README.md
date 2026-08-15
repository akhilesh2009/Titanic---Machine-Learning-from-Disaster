# Titanic - Machine Learning from Disaster

This is my first Machine Learning project.  
I participated in the classic Kaggle competition: **Titanic - Machine Learning from Disaster**.

### Competition Link
[https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/competitions/titanic)

---

### Project Overview

The goal of this project is to predict whether a passenger survived the Titanic disaster or not, based on features like:

- Passenger Class (`Pclass`)
- Sex
- Age
- Number of siblings/spouses (`SibSp`)
- Number of parents/children (`Parch`)
- Embarked port

---

### What I Did

1. Loaded and explored the data
2. Handled missing values (mainly `Age`)
3. Encoded categorical columns (`Sex` and `Embarked`)
4. Created train-test split
5. Trained models:
   - Decision Tree → **74.8%** accuracy
   - Random Forest → **82.7%** accuracy
6. Made predictions on the real test set
7. Created and submitted the `submission.csv` file on Kaggle

---

### Models Used

| Model              | Validation Accuracy |
|--------------------|---------------------|
| Decision Tree      | 74.8%               |
| **Random Forest**  | **82.7%**           |

Final model used for submission: **Random Forest**

---

### How to Run

1. Open the notebook in Google Colab or Jupyter
2. Make sure `train.csv` and `test.csv` are in the same folder
3. Run all cells
4. The file `submission.csv` will be generated

---

### Files

- `Titanic_Machine_Learning_from_Disaster.ipynb` → Main notebook
- `train.csv` → Training data
- `test.csv` → Test data
- `submission.csv` → Final predictions

---

### Learnings

- Proper train-test split is important
- Never use `fit_transform` on the test set
- Random Forest usually performs better than a single Decision Tree
- Feature cleaning and encoding matter a lot

---

### Author
Akhilesh

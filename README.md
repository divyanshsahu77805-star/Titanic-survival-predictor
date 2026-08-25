# Titanic - Machine Learning from Disaster

A Data Science and Machine Learning project focused on analyzing passenger data from the Titanic disaster to predict survival outcomes using statistical modeling and classification algorithms.

---

## 📋 Table of Contents

* **Project Overview**
* **Dataset Overview**
* **Project Structure**
* **Setup & Installation**
* **Workflow & Methodology**

---

## 🔍 Project Overview

The objective of this project is to build a predictive model that answers the question: "What sorts of people were more likely to survive?" using passenger data (such as age, gender, socio-economic class, and family size).

---

## 📊 Dataset Overview

The dataset contains physical, demographic, and ticket details of the Titanic passengers:

| Feature | Data Type | Description |
| :--- | :--- | :--- |
| **PassengerId** | Integer | Unique identifier for each passenger |
| **Survived** | Binary (0/1) | Target variable (0 = No, 1 = Yes) |
| **Pclass** | Integer | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| **Name** | String | Passenger name |
| **Sex** | Categorical | Passenger gender (`male` / `female`) |
| **Age** | Continuous | Age in years |
| **SibSp** | Integer | # of siblings / spouses aboard the Titanic |
| **Parch** | Integer | # of parents / children aboard the Titanic |
| **Ticket** | String | Ticket number |
| **Fare** | Continuous | Passenger fare |
| **Cabin** | String | Cabin number |
| **Embarked** | Categorical | Port of Embarkation (`C` = Cherbourg, `Q` = Queenstown, `S` = Southampton) |

---

## 🛠 Project Structure

```text
├── data/
│   ├── train.csv           # Training dataset with ground truth labels
│   └── test.csv            # Test dataset for final evaluation
├── notebooks/
│   └── Titanic_Analysis.ipynb # Exploratory analysis & modeling notebook
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

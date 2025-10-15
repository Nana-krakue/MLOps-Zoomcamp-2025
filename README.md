# 📚 Summary of First Session — Machine Learning Zoomcamp

> Notes from the **Machine Learning Zoomcamp** by [Alexey Grigorev](http://mlzoomcamp.com).  
> These are my personal takeaways from the first session, covering key ML fundamentals, project workflows, and Python tools for data analysis.

---

## 🚗 1. Introduction to Machine Learning with Cars Data
We start with a dataset about cars, which includes **features** (characteristics such as brand, year, mileage) and **target** (price).  
A Machine Learning (ML) model can extract patterns from this data — learning from known examples to predict the price of new, unseen cars.

---

## 🧠 2. Rules-Based Systems vs Machine Learning

| System Type | Description |
|--------------|-------------|
| **Rules-Based Systems** | Involves manually writing code that defines logic and rules to process data. Extracting patterns manually becomes complex as data grows. |
| **Machine Learning** | Models automatically learn patterns from data using **mathematics and statistics**, eliminating the need to hand-code every rule. |

---

## 🔍 3. Supervised Machine Learning
In **supervised learning**, models learn from **labeled data** (where outcomes are known) to make predictions on new data.  
There are three major supervised ML types:

- 🧩 **Classification:** The target is a *category* (e.g., spam or not spam).  
- 📈 **Regression:** The target is a *number* (e.g., car price).  
- 📊 **Ranking:** The output is a *ranked list* of items ordered by importance or score.

---

## 🛠️ 4. CRISP-DM — Cross-Industry Standard Process for Data Mining

CRISP-DM is a structured methodology for organizing ML projects.  
It outlines an **iterative** process of continuous improvement across the following phases:

1. 💼 **Business Understanding:**  
   Identify the problem and define what success looks like. Decide whether ML is necessary — a rule-based solution might suffice.

2. 🔎 **Data Understanding:**  
   Explore the available data, assess its quality, and determine if more data is needed.  
   Good business understanding helps guide this stage.

3. 🧹 **Data Preparation:**  
   Clean and transform raw data into a suitable format for modeling (e.g., handle missing values, normalize, create pipelines).

4. 🤖 **Modeling:**  
   Choose and train models, experiment with different algorithms, and adjust features to improve performance.

5. 📊 **Evaluation:**  
   Measure how well the model performs and determine if it meets business goals.

6. 🚀 **Deployment:**  
   Deliver the model to users (e.g., via an app or API).  
   Consider maintainability, performance monitoring, and continuous model updates.

> ⚙️ This process is **cyclical**, allowing you to revisit earlier stages to refine the model and improve outcomes.

---

## 🏆 5. Model Selection

- Split the dataset into **Training**, **Validation**, and **Test** sets.  
- Train multiple models on the training data, compare them using the validation data, and select the best performer.  
- Finally, test the chosen model on the **test set** to check how well it generalizes to unseen data.

**Note:** After selecting the best model, you can **combine** the training and validation sets to retrain it before final testing.

---

## 💻 6. Setting Up the Environment

Install essential ML and data science tools:

- 🐍 **Python**
- 🔢 **NumPy**
- 📊 **Pandas**
- 📈 **Matplotlib**
- 🧠 **Scikit-learn**

👉 The easiest way to install these tools is via **Anaconda**, which provides an all-in-one data science environment.  
Later in the course, you’ll also use **AWS** for cloud-based computation.

---

## 🔢 7. Introduction to NumPy

NumPy is a core library for **numerical computing** in Python.  
It provides high-performance operations on **arrays** and **matrices**, enabling efficient mathematical computations.

---

## 🔗 8. Linear Algebra Refresher

Covers essential operations like:
- Vector and matrix multiplication  
- Dot products and transposes  
- Creating identity matrices using:
  ```python
  np.eye()

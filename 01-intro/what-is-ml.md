# 🧠 Machine Learning — Summary from ML Zoomcamp by Alexey Grigorev

> Notes and insights from the excellent [ML Zoomcamp](http://mlzoomcamp.com) course by **Alexey Grigorev**.  
> All images and diagrams referenced here are originally from the course material.

---

## 📘 Overview

Machine Learning (ML) is about using **features** and **target information** to **train a model**, which can then be used to **predict unknown targets**.  
In essence, ML is the process of **extracting patterns from data**.

You can imagine a task that’s normally done by an expert — for example, estimating a fair price for a car.  
The expert uses data (brand, mileage, year, condition, etc.) to form an opinion about the price.  
Similarly, a machine learning model learns these **patterns** automatically from data.

---

## ⚙️ Key Concepts

### 🔹 Features
Features are what we **know about an object** — its measurable characteristics.  
In the car example, features could be:
- Brand  
- Year  
- Mileage  
- Engine size  
- Condition  

A **feature** can be a number, string, or even more complex information (like location coordinates).

---

### 🎯 Target
The **target** (or **label**) is **what we want to predict**.

- During training, we use a **labeled dataset** — where both features and the target are known.
- For example, we use many cars (features) with their prices (target) to train a model.
- Later, we can predict the price (target) for a new car based only on its features.

---

### 🧩 Model
A **model** is the output artifact of the training process —  
it contains all the **patterns** learned from the data.

Once trained, the model can:
- Take features of a new, unseen object  
- Predict the target variable (e.g., price of a car)

---

## 🏋️‍♂️ Train a Model

**Model training** is the process of teaching a machine to find relationships between **features** and **targets**.

In simple terms:
> features + target → model

The model learns the hidden patterns that connect input variables (features) to the output variable (target).

---

## 🚀 Use a Model

Training alone doesn’t make a model useful — **applying** it does.

When we use a trained model on **new data (without targets)**, it can **predict** the missing information.

Example:
> Given a new car’s features (brand, year, mileage),  
> the model predicts its price (target).

---

## 🔄 Training vs. Prediction

| Process | Input | Output |
|----------|--------|---------|
| **Training** | Features + Target | Model |
| **Prediction** | Features + Model | Target (Predicted) |

In other words:
- **Training** → teaches the model using known examples  
- **Prediction** → applies the learned knowledge to new cases

---

### 🧾 Summary

- **Machine Learning** is about discovering patterns in data.  
- **Features** represent what we know.  
- **Target** is what we want to predict.  
- **Model** learns from features and target to make future predictions.  
- **Training** builds the model; **Prediction** uses it.

---

📚 *Inspired by and based on course materials from [ML Zoomcamp](http://mlzoomcamp.com) by Alexey Grigorev.*


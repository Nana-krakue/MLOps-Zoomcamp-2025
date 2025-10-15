# 🤖 ML Zoomcamp Notes — by Nana Yaw Krakue

Welcome to my personal notes from the **[ML Zoomcamp](http://mlzoomcamp.com)** course by [Alexey Grigorev](https://linkedin.com/in/agrigorev).  
This repository documents my learning journey in **Machine Learning**, from the foundational theory to practical application.

---

## 🧭 Table of Contents
- [Overview](#-overview)
- [What is Machine Learning?](#-what-is-machine-learning)
- [Core Concepts](#-core-concepts)
  - [Features](#features)
  - [Target (Label)](#target-label)
  - [Model](#model)
- [Training a Model](#-training-a-model)
- [Using a Model](#-using-a-model)
- [Training vs Prediction](#-training-vs-prediction)
- [Summary](#-summary)
- [Acknowledgements](#-acknowledgements)

---

## 📘 Overview

These notes summarize what I’ve learned about how **machines learn from data** and how trained models are used to make predictions on new, unseen information.

The content is based on the clear and practical teaching from **ML Zoomcamp**, an open course for aspiring data scientists and machine learning engineers.

---

## 🧠 What is Machine Learning?

**Machine Learning (ML)** is the process of **using data to train models** that can recognize patterns and make predictions.

Imagine an expert who can estimate a fair price for a car. The expert uses features like brand, year, and mileage to make a judgment.  
Machine learning replicates this by learning those relationships automatically from historical data.

---

## 🧩 Core Concepts

### Features
Features are the **known characteristics** of an object — for example:
- Car brand  
- Year  
- Mileage  
- Engine type  
- Color  

A feature can be numeric, categorical, or even more complex like geolocation.

---

### Target (Label)
The **target** is what we want to **predict**.  
In supervised learning, we use a **labeled dataset** — meaning both features and the target are known.

For example:
> Using car features (inputs) and known prices (target) to train a model.

Later, the model predicts the **price** of a new car with unseen data.

---

### Model
A **model** is the result of training — it contains all learned patterns between **features** and **target**.

Once trained, it can:
- Take new feature inputs
- Predict the likely target value

---

## 🏋️ Training a Model

**Training** is the learning phase.  
The model analyzes examples of input (features) and output (target) to understand the relationship between them.


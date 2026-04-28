# 🚀 MapReduce Web Log Analysis (Big Data Project)

## 📌 Overview

This project demonstrates how to simulate the **MapReduce paradigm** using Python in Google Colab to analyze web server logs.

The goal is to understand how distributed data processing works through the three main phases:

* **Map**
* **Shuffle**
* **Reduce**

---

## 📊 Dataset Description

The dataset consists of simulated HTTP log entries with the following structure:

```
Date, Time, IP, Method, URL, Status, ResponseSize
```

Example:

```
2026-04-28,12:01:32,192.168.1.2,GET,/index.html,200,1024
```

---

## ⚙️ Implemented Tasks

### 🔹 1. Word Count (Introduction)

* Basic MapReduce example
* Counts word occurrences in a text file

---

### 🔹 2. Sales per Region Analysis

* Processes structured CSV data
* Computes total revenue per region

---

### 🔹 3. Web Log Analysis (Main Task)

* Counts number of requests per HTTP status code
* Demonstrates real-world log processing

---

## ⭐ Bonus Exploration

### 🌐 1. Requests per URL

* Identifies the most visited pages
* Helps understand user behavior

---

### 📦 2. Total Response Size per Status

* Measures bandwidth usage per HTTP status
* Highlights system resource consumption

---

### 🚨 3. Error Analysis

* Filters out successful requests (HTTP 200)
* Analyzes only error responses (404, 500, 403)

---

### 🔥 Advanced Analysis

* Combines error count + response size
* Evaluates impact of errors on system performance

---

## 📈 Visualization

The project includes data visualization using **Matplotlib**:

* Bar charts for request distribution
* Pie charts for percentage analysis
* Simple dashboard-style outputs

---

## 🧠 Key Insights

* HTTP 200 responses dominate → system is mostly stable
* Frequent 404 errors indicate missing or incorrect pages
* 500 errors highlight server-side issues
* Most visited pages can be identified using URL analysis

---

## 🛠️ Technologies Used

* Python 🐍
* Google Colab
* Matplotlib
* MapReduce (concept simulation)

---

## 🎯 Learning Outcomes

* Understand the MapReduce programming model
* Apply data processing techniques to real-world logs
* Perform data aggregation and filtering
* Visualize and interpret results

---

## 📂 Project Structure

```
├── main.ipynb              # Base MapReduce tasks
├── bonus_url.ipynb         # URL analysis
├── bonus_size.ipynb        # Response size analysis
├── bonus_errors.ipynb      # Error analysis
├── README.md               # Project documentation
```

---

## 🏁 Conclusion

This project shows how MapReduce can be applied to analyze large datasets efficiently.
Even with a simple simulation, we can extract valuable insights about system performance and user behavior.

---

## 👤 Author

**Hala Mohammed Islam**
Master 1 - IOT
University of Eloued

---

# Pakistan E-Commerce Data Analysis 📊

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Overview
This project analyzes over **1 million transaction records** from Pakistan's largest e-commerce dataset to uncover consumer behaviors and operational bottlenecks. It also implements a **SARIMA** model to forecast future monthly sales revenue.

Project conducted at **HCMC University of Technology and Education (HCMUTE)**.

## 🔑 Key Features
* **Data Preprocessing:** Handled **44% missing data** and cleaned inconsistent formats across 1M+ rows.
* **Exploratory Data Analysis (EDA):**
    * Identified **Cash on Delivery (COD)** as the dominant payment method.
    * Revealed a high **Cancellation Rate (~48.4%)**, specifically in the "Mobiles & Tablets" category.
    * Analyzed seasonal sales trends (peaks in Nov/Dec).
* **Sales Forecasting:** Built and evaluated a **SARIMA(1,0,0)(1,0,0,12)** model to predict monthly revenue trends.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn.
* **Modeling:** Statsmodels (SARIMA), Pmdarima.

## 📂 Dataset
The dataset contains 26 attributes including `item_id`, `status`, `payment_method`, and `grand_total`.
* **Source:** [Kaggle - Pakistan's Largest E-Commerce Dataset](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset/data)

## 🚀 Quick Start
1.  Clone the repo:
    ```bash
    git clone [https://github.com/your-username/pakistan-ecommerce-analysis.git](https://github.com/your-username/pakistan-ecommerce-analysis.git)
    ```
2.  Install requirements:
    ```bash
    pip install pandas numpy matplotlib seaborn statsmodels
    ```
3.  Run the analysis:
    Open `notebook.ipynb` or check the [Google Colab Link](https://colab.research.google.com/drive/1WYNRqLy05ZBviD-rNtOhhz9fdXfTTaK4?usp=sharing).

*May 2025*

# ipl-analysis
# 🏏 IPL Data Analysis & ML‑Ready Data Pipeline

A **real‑world data analysis project** built using the **IPL Complete Dataset (2008–2020)** to demonstrate strong fundamentals in **pandas, NumPy, EDA, visualization, and machine‑learning–ready preprocessing**.

This project is designed to  show *how raw sports data is transformed into insights and model‑ready features*, not just basic plots.

---

## 📂 Dataset

**Source:** Kaggle – IPL Complete Dataset (2008–2020)

Files used:

* `matches.csv` – match‑level information
* `deliveries.csv` – ball‑by‑ball data

The dataset contains a mix of:

* Numeric features (runs, wickets, seasons, margins)
* Categorical features (teams, players, venues, cities)
* Missing and noisy real‑world values

---

## 🧠 Project Objectives

* Perform **exploratory data analysis (EDA)** on IPL match data
* Apply **filtering, sorting, grouping, and aggregation** to answer real questions
* Visualize trends using **pandas + Matplotlib**
* Engineer new performance features from raw data
* Convert categorical data into **ML‑ready numeric format**
* Export final features as **NumPy arrays** for machine learning

---

## 🛠️ Tech Stack

* **Python**
* **pandas** – data manipulation
* **NumPy** – numerical computing
* **Matplotlib** – visualization
* **Jupyter Notebook** – analysis workflow

---

## 📁 Project Structure

```text
ipl-analysis/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebooks/
│   └── ipl_eda.ipynb
│
├── scripts/
│   └── preprocessing.py
│
└── README.md
```

---

## 🔍 Analysis Workflow

### 1️⃣ File I/O & Inspection

* Load CSV files using `pd.read_csv`
* Inspect schema, data types, and missing values
* Identify numeric vs categorical features

### 2️⃣ Indexing & Filtering

* Season‑wise and team‑wise filtering
* Match result analysis (wins, margins, no‑results)
* Multi‑condition queries using logical operators

### 3️⃣ Sorting & Tie‑Breakers

* Ranking matches by win margins
* Sorting with multiple columns as tie‑breakers
* Creating leaderboard‑style outputs

### 4️⃣ Metrics & Grouping

* Matches per season
* Team‑wise total wins
* Aggregations using `groupby` and `agg`

### 5️⃣ Visualization

* Line plots for season trends
* Bar charts for team performance
* Histograms for distribution analysis
* Boxplots for comparative insights

### 6️⃣ Feature Engineering

* Derived metrics such as:

  * Wins per season
  * Performance distributions
* Separation of quantitative and categorical features

### 7️⃣ ML‑Ready Preprocessing

* Handle missing values
* One‑hot encode categorical columns using `get_dummies`
* Convert DataFrame to NumPy arrays
* Split features (X) and target (y)

---

## 📊 Sample Insights

* Team dominance across seasons
* Distribution of large win margins
* Impact of season trends on outcomes
* Clean feature matrices ready for ML models

---

## 🎯 What this project demonstrates

✔ Strong pandas fundamentals
✔ Ability to work with **real, messy datasets**
✔ Clear analytical thinking
✔ End‑to‑end ML data preparation
✔ Professional project organization

---

## 🔮 Future Enhancements

* Player‑level analysis using `deliveries.csv`
* Predict match winners using ML models
* Team performance dashboards
* Advanced feature scaling and pipelines

---

## 🙌 Author

**Ashwini Tadkale**
Data Science & Machine Learning Enthusiast

---

⭐ If you find this project useful, feel free to star the repository!

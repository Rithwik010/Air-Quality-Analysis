# 🌍 Air Quality Analysis in Indian Cities using Python

## 📌 Project Overview

Air pollution has become one of the most critical environmental issues affecting public health and climate. This project analyzes **air quality data from multiple Indian cities** to understand pollution patterns and identify trends in major pollutants.

Using **Python data analysis and visualization libraries**, the project explores pollutant levels such as **PM2.5, PM10, NO₂, SO₂, CO, O₃**, and the **Air Quality Index (AQI)** to discover meaningful insights about air pollution in India.

---

# 🎯 Objectives

* Analyze air pollution levels across different cities in India
* Identify cities with the **highest pollution levels**
* Study **yearly and monthly pollution trends**
* Visualize relationships between different pollutants
* Understand how pollution changes over time

---

# 📊 Dataset

The dataset used in this project contains **daily air quality measurements from Indian cities**.

### Key Features in the Dataset

| Column   | Description                             |
| -------- | --------------------------------------- |
| City     | Name of the city                        |
| Datetime | Date of observation                     |
| PM2.5    | Fine particulate matter concentration   |
| PM10     | Coarse particulate matter concentration |
| NO2      | Nitrogen dioxide levels                 |
| SO2      | Sulfur dioxide levels                   |
| CO       | Carbon monoxide levels                  |
| O3       | Ozone levels                            |
| AQI      | Air Quality Index                       |

---

# 🛠️ Technologies Used

This project was developed using the following tools:

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Advanced statistical visualization
* **Jupyter Notebook / Google Colab**

---

# 🔍 Project Workflow

## 1️⃣ Data Collection

The air quality dataset is loaded using **Pandas** for analysis.

## 2️⃣ Data Cleaning

Data preprocessing steps include:

* Handling missing values
* Converting date columns to datetime format
* Creating new features like **Year and Month**

## 3️⃣ Exploratory Data Analysis (EDA)

EDA is performed to understand:

* Pollution distribution
* Pollutant relationships
* City-wise pollution levels

## 4️⃣ Data Visualization

Different plots are used to visualize patterns in air pollution data.

---

# 📈 Analysis Performed

### 🔹 Yearly Pollution Trends

Average yearly values of **PM2.5, PM10, and AQI** are calculated to analyze how pollution changes over time.

### 🔹 Most Polluted Cities

Cities are ranked based on their **average AQI levels** to identify the most polluted locations.

### 🔹 PM2.5 Analysis

PM2.5 levels are analyzed to understand fine particulate pollution across cities.

### 🔹 AQI Trends for Major Cities

AQI trends are observed for major cities such as **Delhi** to see long-term pollution patterns.

### 🔹 Pollutant Correlation

A **correlation heatmap** is generated to study relationships between different pollutants.

---

# 📊 Visualizations Included

The project includes several visualizations such as:

* 📉 Line Charts for pollution trends
* 📊 Bar Charts for city comparisons
* 🔥 Heatmaps for pollutant correlation
* 📈 Distribution plots for pollutant levels

These visualizations help in understanding **pollution patterns more clearly**.

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/air-quality-analysis.git
```

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 3️⃣ Run the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook Air_Quality_Analysis_.ipynb
```

or run it using **Google Colab**.

---

# 📂 Project Structure

```
Air-Quality-Analysis
│
├── Air_Quality_Analysis_.ipynb
├── city_day.csv
└── README.md
```

---

# 🔮 Future Improvements

* Machine learning models for **AQI prediction**
* Time series forecasting of pollution levels
* Interactive dashboards using **Plotly or Power BI**
* Real-time air quality monitoring integration

⭐ If you found this project useful, consider **starring the repository on GitHub!**

# 🚴‍♂️ Python Hackathon - Cycloergometer Exercise Tests in Elite Athletes

Welcome to the Python Hackathon project! This repository explores cardiorespiratory and physiological performance metrics in elite athletes using data from the [ACTES Cycloergometer Exercise Tests](https://physionet.org/content/actes-cycloergometer-exercise/1.0.0/) dataset hosted on PhysioNet.

---

## 📂 Dataset Source

**Dataset Name**: ACTES - Cycloergometer Exercise Tests in Elite Athletes  
**Source**: PhysioNet  
**Link**: [PhysioNet ACTES Dataset](https://physionet.org/content/actes-cycloergometer-exercise/1.0.0/)  
**Description**:  
The dataset includes data from **32 elite athletes** across **10 different sports**, with time-series and static measurements including:
- Power (Watts)
- VO₂ (Oxygen Consumption)
- HR (Heart Rate)
- RR (Respiratory Rate)
- Phases: Warm-up, Graded Exercise Test (GET), Cool-down
- Anthropometric and demographic details

---

## 📊 Features and Tasks

This project includes a comprehensive set of preprocessing, analysis, visualization, and querying tasks:

### 🔄 Data Preparation
- ✅ Merging multiple files into a single, structured DataFrame  
- ✅ Cleaning and aligning time-series data  
- ✅ Handling missing or noisy measurements

### 🏷️ Labeling and Annotation
- ✅ Labeling time segments into Warm-up, GET (Graded Exercise Test), and Cool-down phases  
- ✅ Assigning HR zones (Zone 1–5) based on max HR thresholds

### 📈 Analytical Tasks
- ✅ VO₂ Max and Heart Rate Variability (HRV) analysis by sport  
- ✅ Calculation of:
  - Time spent in each test phase
  - Inter-Beat Interval (IBI)
  - Body Mass Index (BMI)
  - Maximum Power Output  
  - HR trends during test phases

### 📊 Visualizations
- ✅ Advanced and interactive charts including:
  - 📈 3D Plots  
  - 🥁 Violin Plots  
  - 🍩 Donut Charts  
  - 📉 Regression Plots  
  - 🔥 Heatmaps  

### ❓ Insightful Queries
- ✅ Who is the fittest athlete?
- ✅ What is the VO₂ of the tallest athlete?
- ✅ Which sport demonstrates the highest VO₂ Max on average?
- ✅ How does HR vary across different test phases?

---

## 💡 Goal

To uncover performance insights, detect physiological trends, and visualize athlete efficiency under graded exercise tests using Python-based tools.

---

## 🧰 Tech Stack

- **Python** (pandas, numpy, seaborn, matplotlib, plotly, scipy)
- **Jupyter Notebook**
- **Git/GitHub**
- **PhysioNet** data integration

---


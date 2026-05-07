# Netflix Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix Titles Dataset to identify trends, patterns, and insights from Netflix content data.

The analysis includes:
- Data cleaning
- Summary statistics
- Correlation analysis
- Trend identification
- Data visualization

The goal of this project is to better understand Netflix's content distribution, growth, and viewing patterns.

---

## 🎯 Objective
- Analyze Netflix dataset using Python
- Identify trends and patterns
- Perform statistical analysis
- Visualize important insights using graphs

---

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Dataset
Dataset Used: **Netflix Titles Dataset**

Dataset contains information such as:
- Title
- Type (Movie / TV Show)
- Director
- Country
- Release Year
- Rating
- Duration
- Date Added

---

## 🔍 Steps Performed

### 1. Data Loading
- Imported dataset using Pandas
- Checked dataset structure and data types

### 2. Data Cleaning
- Handled missing values
- Converted date columns
- Extracted numeric values from duration column
- Created additional columns for analysis

### 3. Summary Statistics
Performed statistical analysis to understand:
- Distribution of release years
- Number of Movies vs TV Shows
- Duration patterns

### 4. Correlation Analysis
Analyzed relationships between numerical columns such as:
- Release year
- Duration

### 5. Trend Analysis
Identified:
- Content growth over years
- Most common ratings
- Top contributing countries
- Movie duration distribution

---

## 📊 Visualizations Included
- Movies vs TV Shows Bar Chart
- Content Growth Line Chart
- Top Countries Bar Chart
- Duration Distribution Histogram
- Scatter Plot Analysis

---

## 📈 Key Insights

### Example Insights
- Netflix content increased rapidly after 2016.
- Movies dominate the platform compared to TV Shows.
- USA contributes the highest amount of content.
- Most movie durations are between 80–120 minutes.
- Weak negative correlation exists between release year and duration.

---

## ⚙️ How to Run the Project

### 1. Install Required Libraries

pip install pandas matplotlib seaborn

Run the Python File
python eda_analysis.py

### 📁 Project Structure
Task3-NetflixEDA/
│
├── netflix_titles.csv
├── eda_analysis.py
├── README.md


### 🎥 Output
The project generates:
Statistical summaries
Visual graphs
Trend analysis insights

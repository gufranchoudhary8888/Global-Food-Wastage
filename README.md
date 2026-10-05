# 🌍 Global Food Wastage Analysis

### 📊 Economic & Environmental Impact Analysis of Global Food Waste

This project analyzes global food wastage data to understand **food waste patterns, economic impact, country-level differences, food categories, per-capita waste, and household waste**.

The project uses **Python for data exploration and analysis** and **Power BI for interactive data visualization and dashboard development**.

---

## 🎯 Project Objective

The main objective of this project is to analyze global food waste and identify meaningful patterns that can help understand its **economic and environmental impact**.

The project focuses on questions such as:

* Which countries generate the most food waste?
* Which food categories contribute the most to waste?
* How does food waste change over time?
* Which countries have the highest waste per capita?
* Which countries experience the highest economic loss?
* How significant is household food waste?
* What relationships exist between population, food waste, and economic loss?

---

## 📂 Dataset

The dataset contains **5,000 records and 8 columns**, covering the period **2018–2024**.

### Dataset Columns

| Column                      | Description                                    |
| --------------------------- | ---------------------------------------------- |
| `Country`                   | Country associated with the food waste record  |
| `Year`                      | Year of the record                             |
| `Food Category`             | Category of food being analyzed                |
| `Total Waste (Tons)`        | Total amount of food waste in tons             |
| `Economic Loss (Million $)` | Economic loss associated with food waste       |
| `Avg Waste per Capita (Kg)` | Average food waste per person                  |
| `Population (Million)`      | Population represented in millions             |
| `Household Waste (%)`       | Percentage of waste associated with households |

The dataset was checked for **missing values and duplicate rows**, with the project analysis indicating none were present.

---

## 🛠️ Tools & Technologies

### Python

Used for data exploration, validation, statistical analysis, aggregation, and visualization.

**Libraries:**

* Pandas
* NumPy
* Matplotlib

### Power BI

Used to build the interactive dashboard.

**Power BI features:**

* KPI Cards
* Bar Charts
* Donut Chart
* Trend Analysis
* Interactive Slicers
* Country Analysis
* Category Analysis

### Jupyter Notebook

Used to document and perform the Python-based analysis.

---

## 🔍 Data Analysis Process

### 1. Data Exploration

The dataset was initially explored to understand its structure and characteristics.

Analysis included:

* Dataset shape
* First few records
* Column names
* Data types
* Missing values
* Duplicate records
* Statistical summary

---

### 2. Data Validation

The dataset was checked for:

* Missing values
* Duplicate records
* Data types
* Numerical columns
* Categorical columns
* Value distributions

---

### 3. Descriptive Statistics

Statistical analysis was performed to understand:

* Total food waste
* Total economic loss
* Average household waste
* Minimum values
* Maximum values
* Average values
* Numerical variable distributions

---

### 4. Country Analysis 🌎

Food waste and economic loss were aggregated by country to identify differences in food wastage across countries.

This helps answer:

> Which countries contribute the most to global food waste and economic loss?

---

### 5. Food Category Analysis 🍎

Food waste was grouped by food category to identify which categories contribute most to overall waste.

---

### 6. Year-wise Analysis 📅

Food waste was analyzed from **2018 to 2024** to identify changes and trends over time.

---

### 7. Per-Capita Analysis 👤

Average food waste per capita was compared across countries to understand differences in individual-level waste.

---

### 8. Correlation Analysis 📈

Correlation analysis was performed on numerical variables to explore relationships between variables such as:

* Population
* Total food waste
* Economic loss
* Waste per capita
* Household waste

---

# 📊 Power BI Dashboard

The final analysis was transformed into an interactive Power BI dashboard.

The dashboard allows users to explore food waste patterns using different filters.

## 📌 KPIs

The dashboard includes KPIs such as:

* **Total Food Waste (Tons)**
* **Average Waste per Capita (Kg)**

---

## 📈 Dashboard Visualizations

### 📅 Food Waste Trend

Shows how total food waste changes across different years.

### 🌎 Top Countries by Food Waste

Compares countries based on their total food waste.

### 🍎 Food Waste by Category

Shows the distribution of food waste across different food categories.

### 💰 Economic Loss by Country

Compares the economic loss associated with food waste across countries.

### 👤 Waste per Capita

Shows average food waste per capita across countries.

### 🏠 Household Waste by Category

Compares household waste percentages across different food categories.

---

## 🎛️ Interactive Filters

The dashboard contains slicers for:

* **Year**
* **Country**
* **Food Category**

These filters allow users to interactively explore specific parts of the dataset.

---

## 📸 Dashboard Preview

![Global Food Wastage Dashboard](dashboard.png)

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Exploration
     ↓
Data Validation
     ↓
Data Analysis using Python
     ↓
Aggregations & Statistical Analysis
     ↓
Power BI
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

## 💡 Business Questions Answered

This project helps answer:

1. Which countries generate the most food waste?
2. Which food categories contribute most to food waste?
3. How does food waste change from year to year?
4. Which countries have the highest waste per capita?
5. Which countries experience the greatest economic loss?
6. How significant is household food waste?
7. What relationships exist between population, waste, and economic loss?

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* **Python**
* **Pandas**
* **NumPy**
* **Exploratory Data Analysis (EDA)**
* **Data Validation**
* **Descriptive Statistics**
* **Data Aggregation**
* **Correlation Analysis**
* **Data Visualization**
* **Power BI**
* **Dashboard Development**
* **KPI Design**
* **Interactive Slicers**
* **Business Insight Generation**
* **Data Storytelling**

---

## 📁 Project Structure

```text
Global-Food-Wastage/
│
├── GLOBAL_FOOD_WASTAGE.ipynb
├── global_food_wastage_dataset(6).csv
├── dashboard.png
└── README.md
```

### File Description

| File                                 | Purpose                      |
| ------------------------------------ | ---------------------------- |
| `GLOBAL_FOOD_WASTAGE.ipynb`          | Python analysis and EDA      |
| `global_food_wastage_dataset(6).csv` | Dataset used for the project |
| `dashboard.png`                      | Power BI dashboard preview   |
| `README.md`                          | Project documentation        |

---

## 🚀 How to Run the Python Analysis

### 1. Clone the repository

```bash
git clone https://github.com/gufranchoudhary8888/Global-Food-Wastage.git
```

### 2. Open the project

```bash
cd Global-Food-Wastage
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
GLOBAL_FOOD_WASTAGE.ipynb
```

Make sure the CSV dataset is present in the same directory as the notebook.

---

## 📌 Project Type

**Data Analytics & Data Visualization Project**

This project demonstrates an end-to-end beginner-friendly data analytics workflow:

> **Dataset → Python → EDA → Statistical Analysis → Power BI → Dashboard → Insights**

---

## 👨‍💻 Author

### Gufran Choudhary

**Aspiring Data Analyst**

Skills:
`Python` · `Pandas` · `NumPy` · `Power BI` · `Data Analytics`

GitHub: **@gufranchoudhary8888**

---

## ⭐ If You Like This Project

If you found this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is created for **educational and portfolio purposes**.

🌍 Global Food Wastage Analysis

Economic & Environmental Impact Analysis of Global Food Waste

This project analyzes global food wastage data to understand waste patterns across countries, years, and food categories, along with the associated economic loss, per-capita waste, population, and household waste percentage.

The project combines Python-based data analysis with an interactive Power BI dashboard to turn the raw dataset into meaningful insights and visualizations.

📊 Dashboard Preview



Note: Upload the dashboard screenshot to this repository with the filename dashboard.png so it appears here on GitHub.

🎯 Project Objectives

The main objectives of this project are:

Analyze the overall quantity of food waste.

Compare food waste across different countries.

Identify food categories contributing most to waste.

Analyze food waste trends from 2018 to 2024.

Understand the economic impact of food wastage.

Compare average food waste per capita between countries.

Analyze household food waste percentages.

Present the findings through an interactive dashboard.

📁 Dataset

The dataset contains 5,000 records and 8 columns covering the period 2018–2024.

Dataset Columns

Column

Description

Country

Country associated with the food waste record

Year

Year of the record

Food Category

Category of food being analyzed

Total Waste (Tons)

Total amount of food waste in tons

Economic Loss (Million $)

Economic loss associated with the food waste

Avg Waste per Capita (Kg)

Average food waste per person in kilograms

Population (Million)

Population represented in millions

Household Waste (%)

Percentage of waste associated with households

The analysis confirms that the dataset contains no missing values and no duplicate rows. The year range is 2018–2024.

🛠️ Tools & Technologies

Python

Python

Pandas

Jupyter Notebook

Data Visualization & Dashboard

Power BI

Interactive filters and slicers

KPI cards

Bar charts

Donut chart

Trend analysis

🔎 Data Analysis Performed

The Python notebook performs:

1. Data Exploration

Dataset shape

First few records

Column names

Data types

Missing-value checking

Duplicate-value checking

Statistical summary

2. Descriptive Analysis

Calculated:

Total food waste

Total economic loss

Average household waste

Minimum and maximum values

Statistical summaries of numerical columns

3. Country Analysis

Food waste and economic loss are grouped by country to identify the countries with the highest values.

4. Food Category Analysis

Food waste is grouped by food category to identify which categories contribute most to overall waste.

5. Year-wise Analysis

Food waste is grouped by year to analyze changes and trends between 2018 and 2024.

6. Per-Capita Analysis

Average waste per capita is compared across countries.

7. Correlation Analysis

Correlation between numerical variables is explored to understand relationships within the dataset.

📈 Power BI Dashboard

The dashboard provides an interactive view of the analysis.

KPI Cards

Total Food Waste (Tons)

Average Waste per Capita (Kg)

Visualizations

📅 Food Waste Trend

Shows total food waste by year.

🌎 Top Countries by Food Waste

Compares countries based on total food waste.

🍎 Food Waste by Category

Shows the distribution of food waste across food categories.

💰 Economic Loss by Country

Compares economic loss associated with food waste across countries.

👤 Waste per Capita

Shows average food waste per capita by country.

🏠 Household Waste by Category

Compares household waste percentages across food categories.

Interactive Filters

The dashboard includes filters for:

Year

Country

Food Category

These filters allow users to explore specific parts of the dataset.

💡 Key Insights

The analysis helps answer questions such as:

Which countries generate the most food waste?

Which food categories contribute the most to food waste?

How does food waste change from year to year?

Which countries have the highest waste per capita?

Which countries experience the greatest economic loss?

How significant is household waste across food categories?

What relationships exist between population, waste, economic loss, and per-capita waste?

Important: Dashboard KPI values change when filters such as Year, Country, or Food Category are applied. Therefore, displayed values should be interpreted according to the selected filters.

📂 Project Structure

Global-Food-Wastage/
│
├── GLOBAL_FOOD_WASTAGE.ipynb
├── global_food_wastage_dataset(6).csv
├── dashboard.png
└── README.md

🚀 How to Run the Python Analysis

1. Clone the repository

git clone https://github.com/gufranchoudhary8888/Global-Food-Wastage.git

2. Open the project

cd Global-Food-Wastage

3. Install the required Python library

pip install pandas jupyter

4. Start Jupyter Notebook

jupyter notebook

5. Open

GLOBAL_FOOD_WASTAGE.ipynb

Make sure the CSV dataset is present in the same folder before running the notebook.

📊 Dashboard Workflow

Raw Dataset
     ↓
Data Exploration
     ↓
Data Validation
     ↓
Data Analysis using Python/Pandas
     ↓
Aggregations & KPIs
     ↓
Power BI Dashboard
     ↓
Interactive Insights

🎓 Project Type

Data Analytics / Data Visualization Project

This project demonstrates practical skills in:

Data Cleaning & Validation

Exploratory Data Analysis (EDA)

Data Aggregation

Statistical Analysis

Data Visualization

Power BI Dashboard Development

Business Insight Generation

👨‍💻 Author

Gufran Choudhary

GitHub: @gufranchoudhary8888

⭐ If You Like This Project

If you found this project useful, consider giving the repository a ⭐ on GitHub.

📜 License

This project is intended for educational and portfolio purposes.

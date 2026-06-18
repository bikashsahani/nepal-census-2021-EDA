# 🇳🇵 Nepal Census 2021 — Exploratory Data Analysis

An end-to-end EDA project on Nepal's National Census 2021 data, covering data cleaning, statistical analysis, and visualization using Python.

---

## 📌 Project Overview

The Nepal Census 2021 is the most recent national census conducted by the Central Bureau of Statistics (CBS) of Nepal. This project performs a comprehensive Exploratory Data Analysis (EDA) on the census data to uncover patterns in population distribution, household characteristics, and socioeconomic indicators across Nepal's provinces and districts.

---

## 🎯 Objectives

- Clean and preprocess raw census data for analysis
- Understand the distribution of population across provinces and districts
- Analyze demographic trends (total population by local municipality, sex ration, population density, etc)
- Visualize key socioeconomic indicators
- Derive actionable insights from the data


## 📊 Dataset

- **Source:** Central Bureau of Statistics (CBS), Nepal — [cbs.gov.np](https://cbs.gov.np)
- **Census Year:** 2021
- **File:** `census.csv` (raw) → `census_data_eda.csv` (cleaned)

Key columns in the dataset include 'District', 'Local Level Name', 'Total family number', 'Total household number', 'Total population', 'Total Male', 'Total Female'.

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis environment |


## 🔍 Analysis Highlights

The notebook covers the following sections:

**1. Data Loading & Inspection**
- Loading raw census data
- Initial shape, dtypes, and sample inspection

**2. Data Cleaning**
- Handling missing values
- Fixing inconsistent column names
- Exporting cleaned data to `census_data_eda.csv`

**3. Univariate Analysis**
- 737 unique local level name
- Range of Total family number = 231589
- Range of Total household number = 105524
- There is no mismatch in the total population. Total Male + Total Female = Total population

**4. Bivariate & Comparative Analysis**
- Ghodaghodi Municipality is top must municipality by total population
- Narpa Bhumi Rural Municipality is buttom must municipality by total population
- Manang has the lowest population and Sarlahi has the highest population

**5. Visualizations**
- Bar charts of Top 10 District by population
- histplot by Distribution of Total Population Across Local Levels
- pie chart of Overall Male population Vs overall Female polpulation
- Heatmaps for correlation analysis
- horizontal bar graph of Top 15 Local Level Name with highest Sex Ratio

-----

## 💡 Key Findings
- - 737 unique local level name
- Range of Total family number = 231589
- Range of Total household number = 105524
- Literacy rates vary significantly between provinces...
- Ghodaghodi Municipality is top must municipality by total population
- Narpa Bhumi Rural Municipality is buttom must municipality by total population
- Manang has the lowest population and Sarlahi has the highest population

-----

## 🗺️ Future Work
- [ ] Time-series comparison with Census 2011 data
- [ ] Interactive dashboard using Plotly or Streamlit
- [ ] Statistical hypothesis testing on demographic variables

---

## 👤 Author

**Bikash Sahani**
- GitHub: [@bikashsahani](https://github.com/bikashsahani)

---


## 🙏 Acknowledgements

- [Central Bureau of Statistics, Nepal](https://cbs.gov.np) for the census data
- Open-source Python community for the libraries used in this project

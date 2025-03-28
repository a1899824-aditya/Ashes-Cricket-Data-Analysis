# 🏏 Ashes 2006/07 Cricket Data Analysis – Data Taming in R

This project analyzes the 2006/07 Men’s Ashes Test Series between Australia and England using R for data cleaning, transformation, and visualization.

---

## 📄 Dataset
- `ashes_2007.csv`: Raw dataset with batting performance from 5-test series
- Each row represents a player and columns represent innings performance

---

## 🛠 Tools & Libraries
- R  
- tidyverse: `dplyr`, `ggplot2`, `tidyr`, `stringr`, `forcats`

---

## 🧹 Data Cleaning & Transformation
- Converted wide-format innings data into tidy long format using `gather()`  
- Extracted batting order, runs, and balls faced using `str_match()`  
- Recoded categorical variables and cleaned role/team columns with `fct_recode()`  
- Converted variable types to appropriate data types (factor, numeric, integer)

---

## 📊 Analysis
- Histograms and boxplots of scores  
- Team-based distribution comparisons  
- Scoring rate vs balls faced (scatterplots)  
- Role-based player composition with bar plots  
- Contingency table of roles by team

---

## 📁 Files
- `Assignment2_datataming.Rmd` – Full R code and outputs  
- `Assignment2_datataming.pdf` – Rendered report  
- `ashes_2007.csv` – Dataset used

---

## 📈 Key Insights
- Australia and England had similar score variability with right-skewed distributions  
- Players who faced more balls generally scored more, but not necessarily at a faster rate  
- Australia's team composition leaned more toward batters; all-rounders were equally represented

---

## 👤 Author
Aditya Venugopalan Nediyirippil  
GitHub: [a1899824-aditya](https://github.com/a1899824-aditya)

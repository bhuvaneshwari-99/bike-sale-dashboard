# 🚲 Bike Sale Dashboard — Customer Purchase Analysis

An Excel dashboard analyzing 1,026 customer records to understand who buys bikes and why. Built with PivotTables, PivotCharts, and slicers for interactive filtering by **Marital Status**, **Region**, and **Education**.

![Dashboard Preview](dashboard_preview.png)

## 📊 Project Overview

This project explores a bike retailer's customer dataset to identify the demographic, financial, and lifestyle factors most associated with purchasing a bike. The dataset includes 13 fields per customer: ID, marital status, gender, income, children, education, occupation, home ownership, cars owned, commute distance, region, age, and purchase outcome.

**Tools used:** Excel (PivotTables, PivotCharts, Slicers, Dashboard design)

## 🗂️ Dataset Summary

- **1,026 customer records**, no missing values
- Overall split: **51.8% did not purchase**, **48.2% purchased** a bike — a fairly balanced outcome
- Average income across all customers: **~$56,200**

## 🔍 Key Findings

### 1. Income and Gender
Higher income correlates with bike purchases for both genders, but the effect is stronger for men. Male buyers average **$60,124** in income vs. **$56,208** for male non-buyers — a larger gap than seen for women ($55,774 vs. $53,440). Men also out-earn women overall, regardless of purchase outcome.

### 2. Age Brackets
**Middle-aged customers (31–54)** are by far the largest customer segment and the only age group where buyers outnumber non-buyers (393 buyers vs. 326 non-buyers). Both younger (0–30) and older (55+) customers skew toward *not* purchasing, and represent much smaller segments overall.

### 3. Commute Distance
Customers with **very short commutes (0–1 miles)** are the most likely to buy a bike (207 buyers vs. 171 non-buyers) — likely using it for local commuting. Interest drops off as commute distance increases, with the **10+ mile** group showing the lowest purchase interest (33 buyers vs. 80 non-buyers), presumably because a bike isn't practical for long-distance commuting.

### 4. Marital Status
Single customers purchase at a slightly higher rate (**54.3%**) than married customers (**43.0%**). This may reflect differences in disposable income or lifestyle flexibility.

### 5. Region
**Pacific** customers have the highest purchase rate (**58.9%**), followed by Europe (49.4%) and North America (43.3%) — the lowest of the three regions.

### 6. Education
Purchase rates are fairly similar (45–54%) across Bachelors, Graduate Degree, High School, and Partial College segments. The standout exception is **Partial High School**, which has a notably low purchase rate of just **28.2%**.

### 7. Cars Owned
Purchase likelihood **decreases as car ownership increases** — customers with 0 cars purchase at the highest rate (60.2%), while those with 4 cars purchase at the lowest rate (34.4%). This suggests bikes are partly filling a transportation gap for customers without easy access to a car.

### 8. Children & Home Ownership
Number of children and home ownership status show only weak relationships with purchase behavior — no strong pattern emerges, and rates stay roughly in the 43–57% range across most groups (with the 5-children segment a notable but very small outlier at just 21.4%).

## 💡 Summary Insight

The strongest predictors of bike purchase in this dataset are **age (middle-aged adults), commute distance (short commutes), car ownership (fewer cars), region (Pacific), and education level (anything above partial high school)**. Income matters, but mainly as a secondary factor that amplifies gender-based differences rather than driving purchases on its own.

## 📁 Files

| File | Description |
|---|---|
| `Excel_Project_Dataset.xlsx` | Raw data, working calculations, PivotTables, and final dashboard |
| `dashboard_preview.png` | Static preview image of the dashboard |

## 🚀 How to Use

1. Open `Excel_Project_Dataset.xlsx` in Excel
2. Go to the **Dashboard** sheet
3. Use the slicers (Marital Status, Region, Education) to filter the charts interactively

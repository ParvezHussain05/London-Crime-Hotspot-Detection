# London Crime Hotspot Analysis

## Project Overview

This project analyses crime data from London to identify crime hotspots and understand trends across boroughs.

Using Python and public crime data, the analysis explores:

* Crime trends over time
* Distribution of crime categories
* Boroughs with the highest crime levels

The goal is to demonstrate core data analysis skills including data cleaning, reshaping datasets, exploratory data analysis, and visualisation.

---

## Dataset

Dataset used:

**Recorded Crime Summary Data for London – Borough Level**

Source: Metropolitan Police via the London Datastore.

The dataset contains monthly crime counts for each London borough and crime category.

Columns include:

* MajorText (major crime category)
* MinorText (specific crime type)
* BoroughName
* Monthly crime counts (e.g. 202403, 202404 etc.)

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

## Data Preparation

The dataset is provided in a wide format where each month is a separate column.

The data was reshaped into a long format using the Pandas `melt()` function so that each row represents:

Borough | Crime Category | Month | Crime Count

This structure makes time series analysis and aggregation possible.

---

## Analysis

### 1. Crime Trends Over Time

Total crime across London was aggregated by month to analyse overall crime trends.

![Crime Trend](images/Total_Crime_Over_Time.png) 

---

### 2. Crime by Category

Crime counts were grouped by major category to identify the most common types of crime.

![Crime Category](images/Crime_by_Category.png)

---

### 3. Crime Hotspots by Borough

Crime totals were aggregated by borough to identify areas with the highest levels of crime.

![Crime Borough](images/Crime_Hotspots_by_Borough.png)

---

## Key Findings

* Westminster recorded the highest total crime counts among London boroughs.
* Theft and handling offences are the most common crimes across London.
* Crime distribution varies significantly between boroughs.

---

## How to Run the Project

1. Download the repository
2. Open the notebook in Google Colab or Jupyter Notebook
3. Run all cells in order

---

## Author

Parvez Hussain
Mathematics Degree

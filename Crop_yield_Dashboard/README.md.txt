# Crop Yield Dashboard

## Project Overview
This project demonstrates a **Crop Yield Analysis Dashboard** using **Python** for data preprocessing and **Power BI** for visualization. The goal is to explore crop yield trends, pesticide usage, and the impact of environmental factors like rainfall and temperature.

---

## Dataset
The dataset is sourced from [Kaggle: Crop Yield Prediction Dataset](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset/data?select=yield_df.csv).  
It contains the following key columns:  
- `Year`  
- `Country`  
- `Item` (Crop)  
- `Yield` (hg/ha)  
- `Area` (ha)  
- `Pesticides_tonnes`  
- `Temperature`  
- `Rainfall`  

**Note:** A cleaned/processed version of the dataset is included in `data/cleaned_crop_yield.csv`.

---

## Tools & Technologies
- Python (Pandas, NumPy) – Data cleaning and preprocessing  
- Power BI – Data visualization and interactive dashboard  
- GitHub – Version control and portfolio hosting  

---

## Features
- **Interactive Filters:** Year, Country, Crop  
- **Visualizations:**  
  - Pie Chart: Crop-wise yield comparison  
  - Map: Yield, Temperature, and Rainfall by country  
  - Line Chart: Yield trends over years  
- **KPIs:**  
  - Average Yield per Hectare  
  - Crop Contribution Percentage  

---

## How to Run
1. **Python preprocessing:**  
   - Open `python/data_cleaning.ipynb` to clean and process raw data.  
   - Output is saved in `data/cleaned_crop_yield.csv`.  

2. **Power BI Dashboard:**  
   - Open `powerbi/Crop_Yield_Dashboard.pbix`  
   - Use slicers for Year, Country, and Crop to explore trends interactively.  

---

## Insights
- Identify which crops are **high-yielding and pesticide-efficient**.  
- Analyze the effect of **rainfall and temperature** on crop yield.  
- Compare **crop contribution** to total yield across countries.  

---

## Folder Structure

Crop-Yield-Dashboard/
├── data/
├── python/
├── powerbi/
├── README.md


# Faisalabad Cloud Level Analysis (2019–2024)

## Overview
This project analyzes cloud properties over Faisalabad, Pakistan, using satellite-derived data. The analysis includes:

- Cloud base height
- Cloud top height
- Cloud fraction
- Cloud thickness
- Classification into Low, Mid, and High clouds

The goal is to explore trends and distributions of different cloud levels from 2019 to 2024.

---

## Dataset
The dataset `Faisalabad_CloudTop_Base_Height_Fraction_2019_2024.csv` contains:

- `cloud_base_height`: Base height of the cloud (meters)  
- `cloud_top_height`: Top height of the cloud (meters)  
- `cloud_fraction`: Fractional coverage of clouds  
- `month`: Month of observation  
- `year`: Year of observation  

> Non-numeric columns like `.geo` and `system:index` are ignored in the analysis.

---

## Analysis
1. **Cloud Level Classification:**
   - Low clouds: base < 2000 m (adjustable)  
   - Mid clouds: 2000–6000 m  
   - High clouds: base > 6000 m (adjustable)  

2. **Metrics Computed:**
   - Mean cloud fraction per year per cloud level  
   - Mean cloud thickness per year per cloud level  

3. **Visualizations:**
   - Stacked bar chart for mean cloud fraction  
   - Side-by-side bar chart for mean cloud thickness  
   - Optional histogram for cloud base height distribution

---

## Requirements
- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  



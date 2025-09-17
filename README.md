# hsrproject
# Honkai: Star Rail Pull Forecasting Project

**Tools:** Python, Excel, Power BI  
**Skills Demonstrated:** Simulation modeling, probability analysis, data cleaning, dashboard design  

---

## Project Overview
This project explores the gacha system in *Honkai: Star Rail*, focusing on 5★ pull forecasting during Version 3.3.  
It combines **simulated data** (via Python) with **manually tracked pull history** (Excel) and presents insights in an interactive **Power BI dashboard**.  

The goal is to apply real-world analytics skills—probability modeling, forecasting, and data visualization—to a fun, game-related dataset.

---

## Data & Methods
- **Actual Data:**  
  - Pull history and Stellar Jade income tracked in Excel  

- **Simulated Data:**  
  - Python script runs 10,000 gacha trials  
  - Models pity system and 50/50 mechanics  
  - Outputs pity distribution and probability curves  

- **Analysis Steps:**  
  1. Built rarity distribution and actual gacha pity tracking in Excel  
  2. Simulated probability outcomes with Python (`gachasim.ipynb`)  
  3. Imported results into Power BI for visualization  

---

## Key Insights
- Most pulls result in 3★ items (~85%).  
- Probability of obtaining a 5★ rises steeply after 75 pity.  
- Actual pull history shows streaks of both “early luck” and “high pity.”  
- Simulation confirms expected 50/50 win-loss outcomes over large sample sizes.  

---

## Dashboard
The Power BI dashboard includes:  
- **Rarity Distribution Pie Chart** – % of 3★, 4★, 5★ pulls  
- **Line Chart** – how often 5★ occurred at each pity count (cumulative probability)  
- **KPI Cards** – total pulls, 5★ count, % 5★, average pity  


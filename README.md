

# Solar Radiation in Dhahran (2025)

This project analyzes solar radiation data in Dhahran, Saudi Arabia (26.26°N, 50.07°E) using NASA POWER data for the year 2025. The focus is on comparing **All-Sky** vs **Clear-Sky** solar radiation and evaluating monthly trends, distributions, and differences. These insights help understand solar energy potential under real vs ideal atmospheric conditions.

---

## Key Insights

- **All-Sky** values reflect actual atmospheric conditions, including clouds and aerosols.
- **Clear-Sky** values represent theoretical maximums with no atmospheric interference.
- Radiation increases from ~3.5 kWh/m²/day in January to over 7.0 kWh/m²/day in June.
- Clear-sky values consistently exceed all-sky by ~0.2 to 1.1 kWh/m²/day.
- Some data cleaning was necessary: placeholder values (−999) and negative outliers were removed.

---

## Visualizations

- 📊 Daily trend comparison of All-Sky vs Clear-Sky radiation  
- 📈 Monthly averages and differences (Jan–Jul 2025)  
- 📉 Histograms showing distribution of radiation under both conditions  
- ⚠️ Edge cases like negative radiation or sudden drops were cleaned before analysis

---

## Dataset

- **Source:** NASA POWER (Prediction Of Worldwide Energy Resources)  
- **Timeframe:** January to July 2025  
- **Variables:**  
  - `ALLSKY_SFC_SW_DWN` – Actual surface radiation  
  - `CLRSKY_SFC_SW_DWN` – Ideal clear-sky radiation

---

## Tools Used

- Python (Pandas, Matplotlib, NumPy)
- Jupyter/Google Colab
- NASA POWER CSV Data

---

## How to Reproduce

1. Clone the repository
2. Place the CSV file in the `data/` folder
3. Open and run the notebook in `notebook/`
4. View saved plots in the `assets/` directory

---

## Author

Dana Alzahid – 2025  


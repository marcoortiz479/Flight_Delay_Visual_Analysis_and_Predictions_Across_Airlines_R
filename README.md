# ✈️ Flight Delay Visual Analysis and Predictions Across Airlines | R (April 2025 - May 2025)

Performed exploratory analysis on 336,000+ U.S. flights using R (dplyr, ggplot2) to uncover delay patterns by airline, time of day, and airport. Merged datasets and visualized trends to highlight performance gaps across carriers and seasonal delay patterns for operational insights.

---

## 📂 Files Included

- `flights.csv.gz`: – Compressed dataset containing 336,000+ U.S. domestic flights, including variables such as departure and arrival delays, flight number, airline carrier code, origin and destination airports, and scheduled vs. actual departure/arrival times. This dataset serves as the foundation for identifying operational inefficiencies and temporal delay trends.

`airlines_carrier_codes.csv`: – Reference table mapping airline carrier codes (e.g., “AA”, “DL”) to full airline names (e.g., American Airlines, Delta Air Lines), enabling clearer labeling and interpretation in visualizations.

`notebook.ipynb`: – R-based Jupyter Notebook containing all data cleaning, exploratory analysis, and visualizations performed using dplyr and ggplot2.

---

## 📊 Agenda/Objectives

- Perform exploratory data analysis (EDA) to identify trends in delays by airline, day of week, and time of day.
- Visualize delay patterns using `ggplot2` in R.
- Compare the performance of different airlines based on average arrival and departure delays.
- Provide a foundation for predictive modeling of delays (e.g., logistic regression or decision trees — in future work).

---

## 🛠️ Tools & Technologies

- **Language:** R
- **Environment:** R in Jupyter Notebook (via IRKernel)
- **Libraries:** `ggplot2`, `dplyr`, `readr`

---

## 📈 Key Visualizations

- Bar charts comparing average delays across airlines.
- Line plots showing delay trends over time (e.g., by hour of day or day of week).
- Boxplots to visualize delay variability.
- Heatmaps correlating delay severity with time-related variables.

---

## 🧼 Data Cleaning

- Removed canceled flights and filtered out extreme outliers in delay times.
- Converted time columns to readable `POSIXct` formats.
- Merged datasets using carrier codes for clarity in visualization labels.

---

## 🧠 Insights

- Certain airlines consistently experience lower average delays.
- Delays tend to spike during late afternoon and early evening hours.
- Weather and airport congestion may be contributing factors, though not included in the dataset.

---

## 🚀 Future Improvements

- Develop a predictive model for flight delays using logistic regression or classification trees.
- Incorporate weather data and airport congestion statistics.
- Deploy an interactive dashboard using Shiny or Streamlit for better visualization sharing.

---

## 📌 How to Run

1. Open `notebook.ipynb` using Jupyter with R kernel.
2. Install required R packages if not already installed:
   ```R
   install.packages(c("ggplot2", "dplyr", "readr"))

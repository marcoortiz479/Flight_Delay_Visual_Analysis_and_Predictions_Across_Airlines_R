# ✈️ Flight Delay Visual Analysis and Predictions Across Airlines | R (April 2025 - May 2025)

Performed exploratory analysis on 600K+ U.S. flights using R (dplyr, ggplot2) to uncover delay patterns by airline, time of day, and airport. Built and evaluated predictive models using caret, achieving up to 78% accuracy in classifying delayed flights.

---

## 📂 Files Included

- `flights.csv`: Raw dataset containing flight-level details such as airline, origin, destination, departure delay, arrival delay, and more.
- `airlines_carrier_codes.csv`: Mapping of airline codes to full carrier names.
- `notebook.ipynb`: R-based notebook containing data cleaning, visualizations, and exploratory analysis.

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
- **Libraries:** `tidyverse`, `ggplot2`, `dplyr`, `readr`

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

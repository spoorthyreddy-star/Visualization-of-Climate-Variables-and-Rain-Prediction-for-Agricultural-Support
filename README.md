# 🌦️ Visualization of Climate Variables and Rain Prediction for Agricultural Support

## 📘 Overview

This project focuses on **developing a web-based climate visualization and rain prediction system** to support **agricultural decision-making**. Since agriculture depends heavily on weather conditions, unpredictable climate patterns often challenge farmers in planning irrigation, crop schedules, and resource allocation.

To address these challenges, the system integrates **data visualization and predictive analytics** to analyze key weather variables — **temperature, rainfall, humidity, wind, pressure, and sunshine** — through an interactive dashboard. The ultimate goal is to provide **insightful visual analytics** and **rain prediction** that assist farmers in making smarter, sustainable farming decisions.

---

## 🌍 Key Features

The system incorporates multiple interactive visualizations and analytical components:

1. **Temperature Trends**

   * Line charts for daily and seasonal variations in **minimum and maximum temperature**.
   * Helps monitor heat stress and temperature fluctuations affecting crops.

2. **Rainfall vs. Evaporation**

   * Dual-axis chart comparing **rainfall** and **evaporation**.
   * Useful for evaluating water availability and loss, aiding irrigation planning.

3. **Sunshine Hours Distribution**

   * Bar chart showing **sunshine hours per day**.
   * Assists in assessing solar exposure and crop growth potential.

4. **Wind Gust Speed and Direction**

   * Wind rose diagram for analyzing **wind gust occurrences and prevailing directions**.
   * Helps identify periods of strong winds and plan crop protection.

5. **Wind Speed Comparison (9AM vs 3PM)**

   * Grouped bar chart comparing wind speeds at **morning and afternoon**.
   * Provides insight into diurnal wind behavior and its impact on farming operations.

6. **Humidity Comparison (9AM vs 3PM)**

   * Scatter plots showing **humidity variation throughout the day**.
   * Supports predictions of crop moisture and disease management.

7. **Pressure Variation**

   * Line chart comparing **morning and afternoon air pressure**.
   * Helps detect stable weather vs. potential storm activity.

8. **Cloud Cover (Morning vs Afternoon)**

   * Stacked bar visualization for **cloud coverage**.
   * Indicates potential rainfall or overcast conditions.

9. **Temperature by Time of Day**

   * Visualization comparing **temperature at 9AM and 3PM**.
   * Useful for understanding heat variation and crop stress factors.

10. **Rain Risk (RISK_MM) Trend**

    * Histogram depicting **rain likelihood and intensity**.
    * Predicts rainfall probability to support crop and irrigation planning.

11. **Rainfall vs RISK_MM**

    * Comparison chart validating **predicted vs. actual rainfall**.
    * Verifies prediction accuracy and model reliability.

12. **Rain Prediction Dashboard**

    * Integrates all modules into a **comprehensive Tableau dashboard**.
    * Displays interactive charts, predictive weather outcomes, and **crop recommendations** based on predicted rainfall.

---

## 🧠 System Objective

* Provide **data-driven insights** to assist farmers in daily and seasonal decision-making.
* Predict **rainfall likelihood and weather trends** using Tableau.
* Visualize climate variables interactively for **easy interpretation and planning**.
* Support **crop recommendations** and **sustainable agriculture** based on predictive weather data.

---

## 🧩 Technical Implementation

### 🖥️ Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript
* **Visualization:** Tableau Public / Tableau Embedded Dashboard
* **Data Processing:** Python (Pandas, NumPy, Scikit-learn)
* **Prediction Model:** RainTomorrow classification using logistic regression or random forest
* **Deployment:** Vercel

---

## 📊 Data Insights

The dataset includes daily meteorological readings such as:

* Minimum & Maximum Temperature
* Rainfall and Evaporation
* Wind Speed & Wind Gust Direction
* Humidity (9AM & 3PM)
* Air Pressure (9AM & 3PM)
* Sunshine Duration
* Cloud Coverage (9AM & 3PM)
* RainToday and RainTomorrow indicators

These variables are analyzed to derive **patterns and correlations** that influence rainfall prediction and agricultural productivity.

---

## 🔍 Outcome

The final deliverable is an **interactive and operational web dashboard** that:

* Displays multiple **climate indicators** and **site comparisons**.
* Predicts rainfall with a measurable **RISK_MM index**.
* Offers **actionable crop recommendations**.
* Demonstrates integration of **predictive analytics, data visualization, and natural language prediction** for decision support.

---

## 📂 File Structure

```
📁 Project Directory
│
├── index.html                # Main dashboard web page
├── /assets/                  # Icons, images, and styling assets
├── /css/style.css            # Custom CSS for layout and visuals
├── /js/script.js             # JavaScript functions for interaction
├── /data/weather_data.csv    # Source dataset (climate variables)
└── README.md                 # Project documentation (this file)
```

---


## 👩‍💻 Authors

**Team Members:**

* Spoorthy Reddy Alimineti
* Archana Chenigepally
* Shreshna Anugu

**Based on the research paper:**
*Ashutosh Shankhdhar (SMART–2022 IEEE Conference, ID: 55829)*

---

### 💡 Summary

This project demonstrates how **predictive analytics and visualization** can transform agricultural decision-making by linking weather data with crop management strategies. It provides an effective, user-friendly platform for farmers to interpret complex climate data intuitively and plan smarter for sustainable outcomes.

# Semiconductor Wafer Defect & Quality Control Pipeline

This repository contains an advanced data engineering and quality control data pipeline designed for semiconductor manufacturing laboratories (such as Intel, TSMC, or AMD infrastructures). It automatically processes, cleans, and classifies microchip wafer test datasets based on rigorous physical and electrical performance metrics.

## 🚀 Key Features & Pipeline Architecture
* **Sensor Noise Reduction & Data Imputation:** Automates the handling of sensor dropouts and logging faults using statistical median imputation.
* **Statistical Outlier Detection:** Filters out false equipment calibration spikes (such as impossible temperature readings and frequency anomalies).
* **Industrial Chip Binning:** Applies logical classification to categorize manufactured chips into **Class A (Premium Pro)**, **Class B (Standard)**, or **Defective (Scrap)** segments.
* **Yield Rate Evaluation:** Dynamically calculates and visualizes factory key performance indicators (KPIs) and total global production yield.

## 📊 Analytical Insights & Visualizations
* Production output distributions are automatically rendered into high-fidelity, presentation-ready bar charts using Python visualization matrices to monitor factory efficiency trends.

## 🛠️ Tech Stack & Dependencies
* **Core Environment:** Python 3.14+ / Jupyter Notebook (`.ipynb`)
* **Libraries:** Pandas, NumPy, Matplotlib (Data Transformation & Visualization Engine)

# Global Air Quality and Pollution Trends

## Problem Statement

Air quality is one of the biggest public health concerns worldwide. This project explores how air quality varies across regions, time, and socioeconomic conditions using global air pollution datasets. The goal is to identify trends, patterns, and correlations that help explain differences in air quality and understand the factors influencing pollution levels globally.

**Data Source:** Kaggle , Google Scholar 

---

## Project Overview

This is a data mining project focused on analyzing global air quality patterns and pollution trends. The analysis covers multiple dimensions including geographic variations, temporal trends, socioeconomic relationships, and correlations between different pollutants.

### Key Features
- Exploratory data analysis of global air pollution metrics
- Analysis across multiple countries and cities
- Examination of pollutants: PM2.5, PM10, NO2, CO, and O3
- Temporal and seasonal trend analysis
- Socioeconomic correlation studies

---

## Exploratory Questions

1. **Which countries/cities have the highest and lowest average pollution levels?**
   - Identify pollution hotspots and cleanest regions globally

2. **How has air quality changed over the last 20 years globally and regionally?**
   - Track temporal trends and long-term patterns

3. **What is the relationship between GDP per capita and air pollution levels?**
   - Explore socioeconomic factors affecting air quality

4. **Do urbanized regions always show higher pollution compared to rural areas?**
   - Analyze urban vs. rural pollution differences

5. **Are there seasonal variations in pollution (e.g., winter vs. summer spikes)?**
   - Identify seasonal patterns and climate influences

6. **How do different pollutants (PM2.5, PM10, NO2, CO, O3) correlate with each other?**
   - Study pollutant interactions and dependencies

---

## Project Structure

```
Global-Air-Quality/
├── README.md                              # Project documentation
├── requirements.txt                       # Python dependencies
├── data/
│   └── global_air_pollution_data.csv     # Air pollution dataset with AQI values
├── notebooks/
│   ├── DM_AQI_Project.ipynb              # Initial exploratory analysis
│   ├── DM_AQI_Pro.ipynb                  # Extended analysis
│   └── DataMiningFinal.ipynb             # Final comprehensive analysis
└── results/
    └── GlobalAQI_Report.pdf              # Final analysis report
```

---

## Dataset Description

### `global_air_pollution_data.csv`

Contains air quality measurements across multiple countries and cities with the following key columns:

| Column | Description |
|--------|-------------|
| `country_name` | Country where the measurement was taken |
| `city_name` | City location of the measurement |
| `aqi_value` | Overall Air Quality Index value |
| `aqi_category` | AQI category (Good, Moderate, etc.) |
| `co_aqi_value` | Carbon Monoxide AQI value |
| `co_aqi_category` | CO AQI category |
| `ozone_aqi_value` | Ozone AQI value |
| `ozone_aqi_category` | Ozone AQI category |
| `no2_aqi_value` | Nitrogen Dioxide AQI value |
| `no2_aqi_category` | NO2 AQI category |
| `pm2.5_aqi_value` | PM2.5 (Fine Particulate Matter) AQI value |
| `pm2.5_aqi_category` | PM2.5 AQI category |

---

## Notebooks

### 1. **DM_AQI_Pro.ipynb**
Initial exploratory data analysis covering:
- Data loading and preprocessing
- Initial visualization of pollution levels
- Pollutant correlation studies

### 2. **DM_AQI_Project.ipynb**
Extended analysis including:
- Comparative analysis across regions
- Basic statistical summaries
- Temporal trend analysis

### 3. **DataMiningFinal.ipynb**
Comprehensive final analysis featuring:
- Complete exploratory data analysis
- Advanced statistical insights
- Visualization of key findings
- Summary of discoveries

---

## Key Findings

See `results/GlobalAQI_Report.pdf` for the detailed analysis report and findings.

---

## Requirements

This project uses Python 3.x with data analysis and visualization libraries. To set up the environment:

```bash
pip install -r requirements.txt
```

Common dependencies for this type of analysis typically include:
- pandas - Data manipulation and analysis
- numpy - Numerical computing
- matplotlib - Data visualization
- seaborn - Statistical data visualization
- scikit-learn - Machine learning (if applicable)

---

## How to Use

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Explore the data:**
   - Start with `notebooks/DM_AQI_Pro.ipynb` for exploratory analysis
   - Progress through `DM_AQI_Project.ipynb` for extended insights
   - Review `DataMiningFinal.ipynb` for comprehensive findings

3. **View results:**
   - Check `results/GlobalAQI_Report.pdf` for the final analysis report

---

## Analysis Methodology

The project employs exploratory data analysis (EDA) techniques to:
- Identify patterns in global air quality
- Compare pollution levels across regions
- Analyze temporal trends and seasonal variations
- Investigate correlations between different pollutants
- Explore relationships with socioeconomic factors

---

## Future Work

Potential extensions of this analysis could include:
- Predictive modeling for air quality forecasting
- Machine learning classification for pollution severity
- Integration of additional datasets (meteorological data, traffic data)
- Development of early warning systems for pollution events
- Deep temporal analysis with time series forecasting

---

<!-- ## Author

Data Mining Course Project - Global Air Quality Analysis

--- -->

## References

- Data sources and analysis methods documented in project notebooks
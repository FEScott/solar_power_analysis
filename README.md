# Solar Power Plant Analysis

Analysis of real-world solar power generation data from two solar installations in India to identify production patterns, weather dependencies, and equipment 
performance.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPO-NAME/blob/main/YOUR-NOTEBOOK-NAME.ipynb)

## Project Overview

This project analyzes 34 days of solar power generation data from two plants in India (May-June 2020) to understand what drives production variability and assess equipment health.

**Key Metrics:**
- 68,774 observations recorded at 15-minute intervals
- 22 inverters monitored across 2 plants
- 8 different measurements per timestamp

##  Key Findings

- **Strong weather dependency**: Solar irradiation shows 0.989 correlation with power output - the primary driver of production
- **Significant daily variance**: 65% difference between best day (May 20: 193,770 kWh) and worst day (May 18: 117,738 kWh)
- **Equipment performing well**: All 22 inverters operating within normal range (798-922W during peak hours) - no maintenance issues detected
- **Seasonal patterns**: Late May consistently outperformed early June, with irradiation 60-80% higher on top production days

##  Analysis Components

1. **Data Integration** - Merged inverter-level generation data with plant-level weather sensor readings
2. **Production Analysis** - Identified highest/lowest production days and quantified variance
3. **Weather Correlation** - Analyzed impact of irradiation, ambient temperature, and module temperature on output
4. **Equipment Health Check** - Evaluated inverter performance during peak hours to detect anomalies
5. **Data Quality Assessment** - Validated merge accuracy (99.99% successful match rate)

##  Dataset

**Source**: [Solar Power Generation Data (Kaggle)](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data)

**Files analyzed:**
- Plant_1_Generation_Data.csv - Inverter-level power output measurements
- Plant_1_Weather_Sensor_Data.csv - Plant-level weather conditions

##  Author

**Freya Elizabeth Scott**  
Physics Graduate | Data Analyst  
[LinkedIn](#) | [Email](mailto:your.email@example.com)

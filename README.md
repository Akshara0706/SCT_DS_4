# Traffic Accident Data Analysis and Visualization

## Overview

This project analyzes the **US Accidents (March 2023)** dataset containing over **7.7 million records** to uncover patterns related to weather conditions, road features, and time of day. The analysis includes exploratory data analysis (EDA), visualization, and geospatial hotspot mapping to derive insights that can contribute to road safety improvements.

## Objectives

* Analyze accident occurrences by hour of the day.
* Study the impact of weather conditions on accidents.
* Examine road features such as junctions, crossings, traffic signals, stops, and bumps.
* Visualize accident hotspots using interactive maps.
* Extract meaningful insights from large-scale transportation data.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Folium
* Git & GitHub

## Dataset

**Dataset:** US Accidents (March 2023)

The dataset contains information about accident severity, location, weather conditions, timestamps, and various road characteristics across the United States.

## Project Workflow

1. Data loading and preprocessing.
2. Handling missing values and date-time conversion.
3. Feature engineering (hour and day extraction).
4. Exploratory Data Analysis (EDA).
5. Visualization of weather and road-related factors.
6. Interactive heatmap generation for accident hotspots.

## Visualizations

* Accidents by Hour of Day
* Top Weather Conditions in Accidents
* Accidents by Day of Week
* Road Feature Analysis
* Accident Severity Distribution
* Interactive Accident Hotspot Heatmap

## Key Insights

* Accident frequency peaks during rush hours.
* Adverse weather conditions contribute significantly to accident occurrences.
* Junctions, crossings, and traffic signals are common accident locations.
* Interactive hotspot mapping helps identify high-risk regions.

## How to Run

```bash
pip install pandas matplotlib seaborn folium
python SCT_DS_4.py
```

## Output Files

* `accidents_by_hour.png`
* `weather_conditions.png`
* `accidents_by_day.png`
* `severity_distribution.png`
* `accident_hotspots_map.html`

## Conclusion

This project demonstrates practical skills in data preprocessing, exploratory data analysis, data visualization, and geospatial analytics. The findings provide valuable insights into accident trends and highlight the importance of data-driven approaches for enhancing road safety and urban planning.

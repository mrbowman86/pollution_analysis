# Global Air Pollution Analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset and Sources](#dataset-and-sources)
   - [Data Collection](#data-collection)
   - [Key Pollutants Analyzed](#key-pollutants-analyzed)
   - [Data Cleaning and Processing](#data-cleaning-and-processing)
3. [Analysis and Findings](#analysis-and-findings)
   - [Pollution Levels vs. Population](#pollution-levels-vs-population)
   - [Top 10 Most Polluted Cities](#top-10-most-polluted-cities-by-pollutant)
   - [Top 1000 Most Polluted Cities - Global Heatmap](#top-1000-most-polluted-cities---global-heatmap)
   - [Pollutant Correlation Analysis](#pollutant-correlation-analysis)
4. [Visualizations](#visualizations)
5. [Conclusion](#conclusion)
6. [Repository and Presentation](#repository-and-presentation)
7. [Project Contributors](#project-contributors)
8. [Resources](#resources)

## Project Overview
This project investigates the relationship between air pollution and population density across the world's most populated cities. Using real-world air quality data, we analyzed key pollutants and assessed their correlation with urban population levels. Our research aims to determine whether higher population density directly translates to higher pollution levels or if other factors play a more significant role.

## Dataset and Sources
### Data Collection
- **City Population Data:** Top 1,000 most populated cities worldwide.
- **Air Quality Data:** Retrieved from the OpenWeather API, specifically using the One Call API 3.0, which provides real-time and historical pollution data.
- **Geographical Data:** Used latitude and longitude for precise pollution mapping.

### Key Pollutants Analyzed
- **Sulfur Dioxide (SO2):** Emissions from fossil fuel burning and industrial activities.
- **Nitrogen Dioxide (NO2):** Emissions from vehicles and power plants.
- **Particulate Matter (PM10, PM2.5):** Airborne particles from dust, industrial emissions, and combustion.
- **Ozone (O3):** A secondary pollutant formed from NO2 and volatile organic compounds.
- **Carbon Monoxide (CO):** Resulting from incomplete combustion of fuels.

### Data Cleaning and Processing
- Renamed columns for consistency.
- Handled missing values to ensure dataset integrity.
- Aggregated pollution metrics to compare across cities effectively.
- Used statistical analysis to identify anomalies in pollution data.

## Analysis and Findings

### 1. Pollution Levels vs. Population
- **Expectation:** A strong positive correlation between population and pollution levels.
- **Finding:** Surprisingly, our analysis showed a weak correlation between population size and pollution concentration.
- **Conclusion:** Pollution levels are influenced by regional factors such as industrial activity, fuel consumption, and environmental policies rather than just population size alone.

### 2. Top 10 Most Polluted Cities (by Pollutant)
- The cities with the highest levels of SO2, NO2, PM10, and PM2.5 were mainly in industrial regions of China and India.
- This aligns with expectations, as these regions have high manufacturing activity and loose pollution regulations.

### 3. Top 1000 Most Polluted Cities - Global Heatmap
- A heatmap visualization provided insight into regional pollution trends:
  - **South Asia (India, Pakistan, Bangladesh):** High PM2.5, CO, and NO2 levels.
  - **Southeast Asia (Indonesia, Vietnam):** Pollution rising due to industrialization.
  - **Africa (Nigeria):** Increasing pollution due to urban growth without strict regulations.
  - **Europe and North America:** Generally lower pollution levels but occasional high pollution spikes in urban centers.

### 4. Pollutant Correlation Analysis
- We generated a correlation matrix for the pollutants:
  - PM10 and PM2.5 had the strongest correlation (~0.9), as expected.
  - Other pollutants showed moderate correlations, likely due to shared sources.
  - CO showed weaker correlation patterns, indicating different emission sources.

## Visualizations
We developed several visualizations to support our findings, including:
1. **Scatter plots:** Displaying pollution levels against population density.
2. **Bar charts:** Comparing pollution levels across different cities.
3. **Heatmaps:** Showing global pollution distribution patterns.
4. **Correlation matrices:** Analyzing the relationships between pollutants.
5. **Top 10 polluted cities:** Highlighting the worst-affected regions.
6. **Top 100 pollution heatmaps:** Providing regional insights into pollution intensity.
7. **Time series graphs:** Examining pollution trends over time for selected cities.
8. **Comparative analysis charts:** Contrasting industrial vs. non-industrial cities.

## Conclusion
- While higher pollution levels often appear in heavily populated areas, direct correlation with population alone is weak.
- Industrialization, fuel usage, and government regulations play a major role in air quality.
- Future research could explore:
  - Income levels vs. air pollution
  - Population density vs. air quality
  - Weather factors (temperature, humidity) affecting pollution
  - Public transport availability vs. pollution levels
  - Impact of environmental policies on pollution trends

## Repository and Presentation
- **GitHub Repository:** [[Pollution Analysis](https://github.com/mrbowman86/pollution_analysis)]
- **Presentation:** A professionally designed PowerPoint explaining the analysis, methodology, and conclusions.

## Project Contributors
This project was completed as part of a data analytics bootcamp by **Project 1 Group 3**. Our team consisted of Anna Howell, Caleb Schmitt, Diana Gibson, Kanchan Kumari, and Michael Bowman.

## Resources
ChatGPT
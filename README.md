# Global Air Pollution Analysis: Population vs. Pollution

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Pollutants Analyzed](#pollutants-analyzed)
- [Data Cleaning & Processing](#data-cleaning--processing)
- [Visualizations](#visualizations)
- [Correlation Analysis](#correlation-analysis)
- [Conclusions](#conclusions)
- [Tools & Technologies Used](#tools--technologies-used)
- [Team Members](#team-members)

---

<a id="project-overview"></a>
## 📖 Project Overview
This project examines the relationship between population density and pollution levels across the world's 1,000 most populated cities. Using data from the OpenWeather API and population datasets from Kaggle, we analyzed six major air pollutants to determine if a direct correlation exists between city population and pollution levels. 

https://github.com/mrbowman86/pollution_analysis

---

<a id="data-sources"></a>
## 📊 Data Sources
- **OpenWeather API** - Used to obtain real-time air pollution data
- **Kaggle City Population Dataset** - Provided population figures for global cities
- **Scientific Literature & Reports** - Referenced to understand the effects of pollutants

---

<a id="pollutants-analyzed"></a>
## ☣️ Pollutants Analyzed
The study focused on the following six pollutants:

1. **Sulfur Dioxide (SO₂)** – From fossil fuel combustion, causes respiratory issues and acid rain.
2. **Nitrogen Dioxide (NO₂)** – Emitted by vehicles and industrial sources, contributes to smog.
3. **Particulate Matter (PM10)** – Large airborne particles from dust and construction.
4. **Particulate Matter (PM2.5)** – Smaller, more harmful particles that penetrate deep into lungs.
5. **Ozone (O₃)** – Formed through chemical reactions in the atmosphere, causes breathing difficulties.
6. **Carbon Monoxide (CO)** – Emitted from incomplete combustion, affects oxygen transport in blood.

---

<a id="data-cleaning--processing"></a>
## 🛠 Data Cleaning & Processing
### Steps Taken:
- Filtered dataset to include only the **top 1,000 most populated cities**.
- Queried OpenWeather API for **pollution levels** in each city.
- Handled missing values, ensuring data consistency.
- Standardized measurement units for pollutants.
- Merged city population data with pollution data.

---

<a id="visualizations"></a>
## 📈 Visualizations
Our project includes several key visualizations:

1. **Scatter plots** showing the population vs. each pollutant.
   [Scatter Plots](https://github.com/mrbowman86/pollution_analysis/blob/main/resources/Scatter_Plot_Visualizations.pdf)
2. **Heatmaps** showing regional pollution levels.
   [Heatmaps](https://github.com/mrbowman86/pollution_analysis/blob/main/resources/Heat_Map_Visualizations.pdf)
3. **Bar Charts** showing the top 10 most/least polluted cities per pollutant.
   [Bar Charts](https://github.com/mrbowman86/pollution_analysis/blob/main/resources/Bar_Chart_Visualizations.pdf)
4. **Open Street Map** showing the top 1,000 populated cities and their pollution levels.
   [Open Street Map](https://github.com/mrbowman86/pollution_analysis/blob/main/resources/City_Open_Street_Map.pdf)
5. **Correlation Matrix** showing how each pollutant is related (or not) against another.
   [Correlation Matrix](https://github.com/mrbowman86/pollution_analysis/blob/main/resources/Correlation_Matrix.pdf)
6. **Powerpoint Presentation**.
   [Powerpoint](GLOBAL_AIR_POLLUTION_ANALYSIS.pptx)   

---

<a id="correlation-analysis"></a>
## 📉 Correlation Analysis
We computed correlation coefficients (R² values) to assess relationships between population and pollutants:

| Pollutant | R-Squared Value | Interpretation |
|-----------|---------------|----------------|
| SO₂ | 0.18 | Weak correlation |
| NO₂ | 0.21 | Weak correlation |
| PM10 | 0.12 | Very weak correlation |
| PM2.5 | 0.14 | Very weak correlation |
| O₃ | 0.08 | No significant correlation |
| CO | 0.10 | Very weak correlation |

### Key Findings:
- We expected **higher population to result in higher pollution** but found **no strong correlation**.
- Pollution levels may be more **influenced by other factors** rather than population size.
- **PM2.5 and PM10** showed the strongest correlation, as expected, due to their similar sources.
- **O3 and CO** showed an inverse correlation, as expected, due to their similar sources.

---

<a id="conclusions"></a>
## 🔍 Conclusions
- **Population alone is not a strong indicator of pollution levels.**
- Industrialization and energy consumption could **play a more significant role** in pollution.
- Future research should explore:
  - **All cities and population sizes versus pollution levels**
  - **Population growth, analyzing how increased population in the same city impacts pollution levels**
  - **Economic factors influencing pollution**
  - **Climate variables affecting pollution levels**
  - **Environmental factors such as temerature, humidity, and altitude versus pollution levels**

---

<a id="tools--technologies-used"></a>
## 🛠 Tools & Technologies Used
- **Python** (Data Analysis & Visualization)
  - `pandas` (Data Processing)
  - `matplotlib`, `seaborn`, `plotly` (Visualizations)
  - `numpy`, `scipy.stats` (Statistical Analysis)
  - `ipywidgets` (Interactive UI Elements)
- **OpenWeather API** (Pollution Data)
- **Kaggle Datasets** (Population Data)
- **PowerPoint** (Report Compilation)
- **ChatGPT** (Research & Report Writing)

---

<a id="team-members"></a>
## 👥 Team Members
- Anna Howell
- Caleb Schmitt
- Diana Gibson
- Kanchan Ratan
- Michael Bowman

Thank you for exploring our findings! 🚀

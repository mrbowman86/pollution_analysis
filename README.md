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

![Project Overview](https://your-repo.com/images/project_overview.png)

---

<a id="data-sources"></a>
## 📊 Data Sources
- **OpenWeather API** - Used to obtain real-time air pollution data
- **Kaggle City Population Dataset** - Provided population figures for global cities
- **Scientific Literature & Reports** - Referenced to understand the effects of pollutants

![Data Sources](https://your-repo.com/images/data_sources.png)

---

<a id="pollutants-analyzed"></a>
## ☣️ Pollutants Analyzed
The study focused on the following six pollutants:

![Pollutants Analyzed](https://your-repo.com/images/pollutants.png)

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

![Data Processing](https://your-repo.com/images/data_processing.png)

---

<a id="visualizations"></a>
## 📈 Visualizations
Our project includes several key visualizations:

1. **Scatter plots** of population vs. each pollutant.
   ![Scatter Plot](https://your-repo.com/images/scatter_plot.png)
2. **Heatmap** showing regional pollution levels.
   ![Heatmap](https://your-repo.com/images/heatmap.png)
3. **Top 10 most polluted cities per pollutant**.
   ![Top Polluted Cities](https://your-repo.com/images/top_polluted.png)
4. **Global distribution of pollution levels**.
   ![Global Pollution](https://your-repo.com/images/global_pollution.png)

🔗 **[Download Visualizations (PDF)](GLOBAL_AIR_POLLUTION_ANALYSIS.pptx)**

---

<a id="correlation-analysis"></a>
## 📉 Correlation Analysis
We computed correlation coefficients (R² values) to assess relationships between population and pollutants:

![Correlation Analysis](https://your-repo.com/images/correlation_analysis.png)

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
- Pollution levels may be more **influenced by industrial activity** rather than population size.
- **PM2.5 and PM10** showed the strongest correlation, as expected, due to their similar sources.

---

<a id="conclusions"></a>
## 🔍 Conclusions
- **Population alone is not a strong indicator of pollution levels.**
- Industrialization and energy consumption **play a more significant role** in pollution.
- Future research should explore:
  - **Population density vs. air quality**
  - **Economic factors influencing pollution**
  - **Climate variables affecting pollution levels**

![Conclusions](https://your-repo.com/images/conclusions.png)

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
- Kanchan Kumari
- Michael Bowman

Thank you for exploring our findings! 🚀
# Wafra: Solar & Renewable Energy Analytics in Egypt

## Project Overview

**Wafra** explores the role of renewable energy, particularly solar and wind power, in reducing dependence on fossil fuels and natural gas for electricity generation.

The project studies **Spain as a benchmark country**, analyzing the growth of renewable energy, including solar and wind, and its impact on electricity generation and natural gas consumption. By examining Spain's experience, we aim to identify insights that could help Egypt increase its use of clean energy and reduce its dependence on natural gas.

The project also assesses Egypt's solar energy potential, identifies promising locations, and estimates their potential electricity generation, natural gas savings, and economic value.

Our goal is to connect historical energy trends, international comparisons, and Egypt's geographical solar potential to better understand the opportunities and impact of renewable energy.

## Team Members

**DEPI – Team 4**

| # | Name | Responsibilities |
|---|---|---|
| 1 | Abdelrahman Ahmed Mahmoud Shoman (Team Leader) | Data Collection, Data Cleaning & Manipulation, Visualization, Presentation |
| 2 | Omar Moharm Fouad Ali | KPIs, Analytical Questions, Insights, Visualization |
| 3 | Omar Mohamed Elmandoh Abdelmaged | Visualization, Reporting |
| 4 | Nada Afify Ahmed Helal | Data Collection, Data Cleaning & Manipulation, Visualization |
| 5 | Hisham Adel Saleh Mohamed | Exploratory Data Analysis (EDA), Visualization |

## Data Sources

### 1. Global Solar Atlas
- Provides solar resource and photovoltaic potential data for Egypt.
- Includes PVOUT, GHI, DNI, DIF, GTI, OPTA, and TEMP.
- Geographic coverage: Egypt.
- Approximate spatial resolution: 1 km.
- Used to assess solar energy potential and identify promising locations.

### 2. geoBoundaries
- Administrative boundary data for Egypt.
- Includes 27 governorates (ADM1) and 365 administrative areas (ADM2).
- Used to connect geographical solar data with administrative regions.

### 3. GeoNames
- Egypt's `cities15000` geographical dataset.
- Includes 242 settlements in the processed dataset.
- Provides settlement names and geographic coordinates.
- Used as a geographical reference for location-based analysis.

### 4. Our World in Data (OWID) – Energy Dataset
- Historical energy data for **Egypt and Spain**.
- Includes six data categories for each country:
  - Solar electricity generation.
  - Wind electricity generation.
  - Electricity consumption.
  - Fuel burned for energy.
  - Energy imports.
  - Natural gas data.
- Used to analyze historical energy trends, renewable energy development, and changes in natural gas consumption.
- Spain serves as a benchmark for understanding the impact of increasing renewable energy use and identifying potential lessons for Egypt.

### 5. World Bank – Commodity Markets (Pink Sheet)
- Monthly and annual historical commodity price datasets.
- Includes natural gas price benchmarks:
  - Natural gas, U.S.
  - Natural gas, Europe.
  - Liquefied natural gas, Japan.
- Prices are measured in USD/MMBtu.
- Used to study historical natural gas price trends and estimate the financial value of potentially avoided gas consumption.
- These are international price benchmarks, not actual Egyptian import prices.

### 6. IRENA – Renewable Power Generation Costs
- Source file: `IRENA_TEC_RPGC_in_2025_data_file_2026.xlsx`
- Includes renewable energy investment cost indicators.
- Solar PV weighted-average capital cost data for 2015–2025.
- Values are expressed in 2025 USD/kW.
- Used to understand the development of solar PV investment costs.

## Data Cleaning & Preprocessing

### Global Solar Atlas
- Selected the relevant solar resource layers.
- Prepared the geographical data for spatial analysis.
- Worked with the PVOUT layer to assess photovoltaic electricity potential.

### geoBoundaries
- Prepared administrative boundary files.
- Used the ADM1 and ADM2 boundaries for geographical matching and aggregation.

### GeoNames
- Filtered the geographical dataset for Egypt.
- Prepared settlement names and coordinates for location-based analysis.

### Our World in Data
- Prepared the Egypt and Spain datasets.
- Selected the relevant energy indicators.
- Focused the historical analysis on 2015 onward.
- Organized the data to support comparisons between the two countries.
- Prepared historical solar and wind generation data alongside other energy indicators.

### World Bank – Pink Sheet
- Selected the required natural gas price columns.
- Prepared separate monthly and annual datasets.
- Focused on the period from 2015 onward.
- Converted price values to numeric format and handled missing values.
- Checked for duplicates and arranged records chronologically.

### IRENA
- Identified the relevant Solar PV data.
- Focused on weighted-average capital costs for 2015–2025.
- Prepared the selected data for cost trend analysis.

## Methodology

1. **Historical Energy Analysis:** Study renewable energy development, including solar and wind generation, electricity consumption, natural gas use, and energy trends in Egypt and Spain.
2. **Benchmark Analysis:** Examine Spain's experience to understand how increasing renewable energy generation can reduce dependence on fossil fuels and natural gas.
3. **Solar Potential Assessment:** Analyze Egypt's geographical solar resources using Global Solar Atlas data.
4. **Spatial Analysis:** Connect solar potential with administrative regions and geographical locations to identify promising areas.
5. **Energy Estimation:** Estimate potential solar electricity generation and the natural gas consumption that could be avoided.
6. **Economic Analysis:** Use international natural gas price benchmarks to estimate the financial value of potentially avoided gas consumption, alongside solar investment cost trends.
7. **Renewable Energy Insights:** Explore the broader contribution of renewable energy, including solar and wind, to cleaner electricity generation and reduced reliance on conventional fuels.

## Key Performance Indicators (KPIs)

- Solar energy potential by location.
- Estimated potential solar electricity generation.
- Historical solar and wind electricity generation trends.
- Renewable energy contribution to electricity generation.
- Natural gas potentially avoided through renewable electricity generation.
- Estimated financial value of avoided natural gas.
- Historical renewable energy growth in Egypt and Spain.
- Changes in natural gas prices.
- Solar PV investment cost trends.

## Tools & Technologies

- Python – Data Cleaning, Manipulation, and Analysis.
- Pandas – Data Processing.
- GeoPandas – Geospatial Data Analysis.
- Power BI – Data Visualization and Reporting.
- Excel – Data Inspection and Preparation.

## Project Limitations

- Solar resource estimates represent long-term potential, not actual electricity generation from existing power plants.
- The geographical resource assessment in this project focuses on solar energy; wind is explored through historical energy generation data rather than a separate geographical wind potential assessment.
- Estimated natural gas savings depend on assumptions about replacing gas-based electricity generation with renewable electricity.
- The financial value of avoided gas is an estimate based on international price benchmarks, not actual Egyptian gas procurement costs.
- Solar potential does not automatically mean that a location is suitable for construction; land availability, infrastructure, and other practical factors must also be considered.
- Spain is used as a benchmark for historical energy trends, but differences between the two countries must be considered when interpreting comparisons.

## Instructor

**Amr Ayyad**

## Project Files

[Google Drive – Project Datasets and Files](https://drive.google.com/drive/folders/16xkDAIIwuCrwaL-6RwhsHMnejSPK9E6Z?usp=sharing)

## Project Status

Work in progress.

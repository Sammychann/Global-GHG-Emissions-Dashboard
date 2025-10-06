# Power BI Global GHG Emissions Dashboard

## 📊 Dataset Description

This dataset provides a historical view of global CO₂ and greenhouse gas (GHG) emissions across countries, regions, economic groups, and sectors. It includes detailed information on population, GDP, energy use, and emissions from cement, coal, oil, gas, flaring, and land-use change. The data is sourced from Our World in Data, a trusted platform for global statistics. 

Each row represents a country (or group/sector) in a given year, with values for per capita emissions, emissions per GDP, cumulative emissions, and contributions to global climate change. In addition to CO₂, the dataset contains methane, nitrous oxide, and total GHG emissions, along with energy consumption and trade-related CO₂ indicators. It also reports global shares and estimates of temperature change caused by different greenhouse gases.

## 🎯 Task

**Create advanced data visualizations by exploring relationships, trends, and patterns within the provided dataset. Your goal is to showcase meaningful insights for both technical and non-technical audiences.**

**Objective:** Participants are required to analyze the dataset and design interactive visualizations that interpret key variables, correlations, or anomalies. The aim is to reveal actionable information and present complex data in a clear, user-friendly manner.

**Guidelines:**
- Clearly state your chosen visualization objective or hypothesis
- Justify the choice of chart types and visualization techniques
- Ensure visualizations are interpretable and accessible
- Highlight insights, trends, or outliers revealed through your analysis
- Include a brief explanation for each visualization describing its purpose and findings

***

## 📈 Page 1: Time Series Analysis

<img width="1297" height="708" alt="image" src="https://github.com/user-attachments/assets/f96b1367-f9cb-4e66-a856-1075ca1cb741" />


### Description

This dashboard page focuses on **temporal trends and patterns** in global greenhouse gas emissions from 1980 to 2022. The visualization strategy emphasizes time-series analysis to reveal long-term trends, cyclical patterns, and inflection points in emissions data.

**Key Visualizations:**
- **Primary Time Series Chart:** Displays CO₂ emissions over time with interactive year slider, showing the steady upward trend from ~400 to ~590 units with notable fluctuations around 2008-2010
- **KPI Cards:** Highlight critical metrics - 39M Population, 2T GDP, providing context for emission intensity calculations
- **Gauge Charts:** CO₂ Consumption (546.67, range 0.00K-1.09K) and Energy Consumption (390M, range 0.0K-9.6K) showing current performance against historical ranges
- **Temperature Change Area Chart:** Demonstrates the cumulative temperature impact by measure over time, showing steady increase from ~0.016 to 0.028 degrees
- **Interactive Filters:** Country selector (Canada), ISO code filter, and measure toggles (CO₂, Methane, GHG, Nitrous Oxide) for dynamic analysis

**Insights Revealed:**
- Consistent upward trajectory in global CO₂ emissions with brief plateaus during economic downturns
- Temperature impact shows accelerating trend, particularly post-2000
- Energy consumption patterns closely correlate with emission trends
- Interactive filtering reveals country-specific and gas-specific patterns

***

## 🌍 Page 2: Comparative Analysis

<img width="1275" height="727" alt="image" src="https://github.com/user-attachments/assets/38104612-328f-4ec6-a86b-095d1ac0fd02" />


![Comparative Analysis Dashboard](imagescross-sectional comparisons** across different dimensions - geographic regions, economic development levels, and individual countries. The visualization approach uses multiple chart types to effectively communicate proportional relationships and rankings.

**Key Visualizations:**
- **Continental Pie Chart:** Shows greenhouse gas distribution by continent with Asia leading at 26.43%, followed by Europe (25.33%), and North America, with detailed percentage breakdowns
- **Income-Based Bar Chart:** Horizontal bar chart displaying emission shares by economic development level, clearly showing high-income countries' disproportionate contribution
- **Continental Bar Chart:** Quantifies CO₂ measures by continent (Asia: 589.69K, Europe: 434.81K, North America: 401.04K) with declining pattern
- **Country Treemap:** Interactive treemap showing individual country contributions with United States, China, Russia, Germany, and Japan as major emitters
- **Time Range Selector:** Covers 1950-2023 period for comprehensive historical analysis
- **Parameter Controls:** Share parameter and CO₂ measure selectors for dynamic comparison switching

**Insights Revealed:**
- Clear regional disparities with Asia and Europe dominating total emissions
- High-income countries show highest per-capita impact despite lower absolute numbers in some cases
- Treemap visualization effectively highlights the concentration of emissions among major economies
- Historical perspective (1950-2023) reveals shifting patterns of global emission responsibilities

***

## 🗺️ Page 3: Bird's Eye View

<img width="1291" height="706" alt="image" src="https://github.com/user-attachments/assets/c15ce028-b951-4ad6-be3f-6d475419cce0" />


![Bird's Eye Geographic View](images/page3_geographic page presents a **geospatial perspective** on global emissions, utilizing an interactive world map to show geographic distribution and hotspots. The visualization leverages spatial analysis to identify regional clusters and geographic patterns in emission data.

**Key Visualizations:**
- **Interactive World Map:** Plotted points representing emission monitoring stations/countries across all continents with higher concentration in industrialized regions
- **Geographic Distribution:** Clear visualization of emission monitoring density with notable clusters in Europe, North America, and parts of Asia
- **Continental Coverage:** Comprehensive global coverage showing data points across North America, South America, Europe, Asia, Africa, and Oceania
- **Spatial Patterns:** Higher density of monitoring points in developed regions, correlating with industrial activity and data collection infrastructure
- **Ocean Context:** Map includes major ocean labels (Atlantic, Pacific, Indian) providing geographic reference points

**Insights Revealed:**
- Emission monitoring and reporting infrastructure is most developed in industrialized nations
- Geographic clustering of high-emission sources primarily in temperate industrial zones
- Comprehensive global coverage enables worldwide climate impact assessment
- Spatial distribution patterns reveal correlation between economic development and emission monitoring density
- Interactive nature allows for detailed geographic exploration of specific regions and countries

***

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/powerbi-ghg-dashboard.git
   cd powerbi-ghg-dashboard
   ```

2. **Download Power BI Desktop** (if not already installed)

3. **Open the dashboard file**
   - Launch Power BI Desktop
   - Open `PowerBI_GHG_Dashboard.pbix`

4. **Refresh data** (if needed)
   - Click on "Refresh" to ensure latest data is loaded

## 🔧 Usage

- Use **slicers and filters** to explore specific countries, time periods, or emission types
- **Hover over visualizations** for detailed tooltips and additional information  
- **Click on chart elements** to cross-filter other visuals on the same page
- **Navigate between pages** using the tabs at the bottom of the report

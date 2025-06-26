# COVID-Impact-NYC-Mousing-Market
This project uses Tableau to visualize COVID-19’s impact on NYC housing through trend lines, filters, and interactive dashboards.

**The Impact of COVID-19 on New York City’s Housing Market: A Buyer and Seller Perspective**

**Project Overview**


This project leverages data visualization techniques in Tableau to analyze the impact of COVID-19 on New York City’s housing market. The goal is to explore how housing inventory, prices, and buyer activity evolved in relation to macroeconomic disruptions — especially shifts in mortgage rates — across four major pandemic phases. This Tableau project provides a detailed, interactive view of New York City’s housing market from 2019 to 2025. By integrating local housing data with national mortgage rate trends, it offers insights into how COVID-19 influenced housing behaviors across different phases of the pandemic. 
________________________________________
**1. Data Preparation and Cleaning**
Datasets used:
•	Housing Market Data

Source: Realtor.com - https://www.realtor.com/research/data/?msockid=39ba18bc204568662c390b6b21cf696e
Metrics: Median Listing Price, Days on Market, Number of Active Listings
Granularity: Monthly frequency, ZIP-code-level for NYC

•	Mortgage Rate Data 

Source: Freddie Mac Primary Mortgage Market Survey (PMMS) – https://www.freddiemac.com/pmms

•	Frequency: Weekly (converted to monthly average)

Cleaning and Transformation Steps:

•	Merged housing data and mortgage rates by date (aligned by month)

•	Filtered ZIP codes to include only the five NYC boroughs

•	Cleaned and standardized date fields

•	Calculated rolling averages where appropriate for visual smoothing
________________________________________

**2. Exploratory Analysis and Visualization in Tableau**

Key metrics tracked:

•	Active Listings: Monthly count of active listings

•	Median Listing Price: Price trends for housing

•	Median Days on Market: Time homes stayed on the market

•	30-Year Fixed Mortgage Rate: Trends in mortgage rates

Key Insights:

•	Active listings showed a significant drop during lockdowns and a surge during the recovery period.

•	Median listing prices followed a sharp rise during the pandemic recovery, fueled by low mortgage rates and demand.

•	Mortgage rates and inventory fluctuations strongly correlated with market behaviors.
________________________________________
**3. Interactive Dashboard in Tableau**

The Tableau dashboard offers dynamic visualizations that allow users to interact with key metrics and analyze trends over time:

Visualizations in the dashboard:

•	NYC Housing Heatmap: An interactive map by ZIP code showing listing density and price variations.

•	Time Series Charts: Line charts of each key metric with COVID phase annotations for easy trend identification.

•	Borough Filter: Filter options to explore trends for Bronx, Brooklyn, Manhattan, Queens, and Staten Island.

•	Period Highlights: Summary boxes and narratives explain market behavior during each phase of the pandemic.
________________________________________

**4. Timeline Breakdown: COVID-19 Market Phases**

The dashboard segments the NYC housing timeline into four distinct phases:

•	Pre-COVID Market (Jan 2019 – Jan 2020)

Mortgage rates declined slowly from ~4.5% to 3.8%.

Listing inventory remained stable with typical seasonal fluctuations.

Prices were mostly flat.

•	Pandemic Shock & Lockdowns (Jan 2020 – Sept 2020)


A sharp drop in listings in spring 2020 due to lockdowns.

Days on market spiked, then dropped with renewed demand.

Mortgage rates fell to record lows (~2.7%).

•	Recovery & Boom (Sept 2020 – Jan 2022)

Demand surged due to low mortgage rates and remote work flexibility.

Inventory could not keep up with demand, forming a sellers' market.

Prices rose steadily and days on market shortened.

•	Inflation & Rate Spike (Jan 2022 – June 2025)

Mortgage rates jumped from ~3% to over 7%.

Listings dropped as sellers hesitated.

Prices plateaued or climbed slowly; demand weakened.

Days on market rose again.
________________________________________
**5. Key Insights and Interpretations**

•	The pandemic shock resulted in an immediate drop in listings, which rebounded as demand picked up during the recovery phase.

•	Price surges and the sellers' market formed when demand was high, but inventory could not meet the surge in buyers, particularly during the recovery.

•	The rate spike phase in 2022-2025 showed how rising mortgage rates and inflation dampened buyer activity, leading to longer days on market.

The Tableau dashboard allows users to interactively explore how housing trends evolved in response to the pandemic, offering insights into the dynamic relationship between inventory, prices, and mortgage rates.
________________________________________
**6. Project Files**

• **historicalweeklydata (1).CSV** - Dataset from Realtor.com containing weekly historical real estate metrics

• **RDC_Inventory_Core_Metrics_Zip_History.csv** - Dataset containing U.S. mortgage rate 

• **Real_Estate.twb** - Tableau workbook (non-packaged); requires downloading the datasets separately and reconnecting them locallyts

• **Real_Estate_Packaged.twbx** - ableau packaged workbook with embedded datasets; full dashboard accessible via this Google Drive Link: https://drive.google.com/file/d/1Xi1fqgt-HbyobnhPhEesJFwaLDN5W1St/view?usp=drive_link

• **Real_Estate.pdf** - PDF export of the Tableau dashboard for quick offline viewing

• **README.PDF** - PDF version of the project README with description and usage instructions



_______________________________________

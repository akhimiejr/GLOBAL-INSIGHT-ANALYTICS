# Introduction
# GLOBAL-INSIGHT-ANALYTICS
Global Insights Analytics is a consultancy specializing in  demographic research and data- driven insights to help governments,  NGOs, and businesses understand global population trends.
# 1.1 Overview
This report presents a comprehensive global demographic analysis, illustrating how the world population has evolved over time, how it is geographically distributed today, and how it is segmented by major religious affiliations. The structure of the report allows the reader to develop an understanding of long-term trends, present-day population concentration, and underlying cultural composition. Power BI has been used to extract data directly from online sources, enabling automation, periodic refresh, and continuous accuracy as global data updates. The design and analytical flow position the report as both a reference tool and a dashboard for ongoing monitoring.
# 1.2 Aim of the Project
The primary goal of this project is to
extract historical and forecasted
population data to identify significant
trends, growth patterns, and
demographic changes across different
regions to help address challenges such as
urban planning, healthcare needs,
resource management, and
environmental impact.
# 1.3 Data Description
1. The dataset contains global demographic information sourced from reputable online databases.

2. It includes historical population figures from the mid-1900s through to projected values for 2025.

3. Country-level population records are geocoded to support spatial mapping and comparative analysis.

4. Regional population data is aggregated into broader continental groupings for high-level interpretation.

5. Religious demographic data represents major global belief systems and shows their proportional share of the world population

https://www.worldometers.info/world-population/

<img width="1113" height="911" alt="Screenshot 2025-12-07 180038" src="https://github.com/user-attachments/assets/695fe45b-c6fc-4b59-97d4-726a89cafe3e" />

# 2. Analysis
## 2.1 Problem Statement
With the global population continuously growing,
environmentalists, and corporations are increasingly
concerned about population distribution, growth
rates, and demographic changes.
Global Insights Analytics has been tasked with
gathering data for these organizations to aid
government decision
## 2.2 Population by Year (Line Chart)
The line chart serves to illustrate global population growth from approximately 1955 to 2025. The trend line rises steadily and sharply, reflecting the exponential increase in population across the mid- to late-twentieth century and into the early twenty-first century. The visual demonstrates key milestones, such as reaching roughly 4 billion in the 1970s, 6 billion around the turn of the millennium, and surpassing 8 billion in the early 2020s. Toward the most recent years, the slope begins to moderate, signalling a slowing growth rate consistent with contemporary demographic projections. The chart leverages Power BI’s automatic scaling, interactive tooltips, and structured temporal axis to maximise clarity and user insight.

<img width="1402" height="435" alt="Screenshot 2025-12-07 183228" src="https://github.com/user-attachments/assets/6a01cc0b-3a74-4406-b30e-7915d8b12901" />

## 2.3 Population 2025 by Country (Bubble Map)
The bubble map visualises the estimated 2025 population at the country level and highlights disparities in population density across the globe. Larger markers cluster significantly in South Asia, East Asia, and Africa, with additional notable concentrations in parts of North and South America. Smaller markers allow representation of every nation, ensuring completeness of analysis. The visual confirms that a relatively small number of countries account for the majority of the global population. This component likely uses Power BI’s geo-encoding capabilities, which automatically interpret country names and assign them to geographic coordinates.

<img width="488" height="281" alt="Screenshot 2025-12-07 183703" src="https://github.com/user-attachments/assets/4814d8e2-d307-4af3-b269-7d7df3ea9546" />

## 2.4 Population (2025) by Region (Choropleth Map)
The choropleth map aggregates countries into global regions and applies colour intensity to represent population magnitude. Asia appears the most densely populated region, followed by Africa, Europe, and the Americas. The map also highlights Africa’s increasing demographic weight, which aligns with projections of rapid population growth in Sub-Saharan regions. Power BI’s shape map visual and graduated colour scale work together to simplify comparison across broad geopolitical groupings, offering a macro-level view complementary to the country-based bubble map.

<img width="467" height="280" alt="Screenshot 2025-12-07 184052" src="https://github.com/user-attachments/assets/559c1ee8-18de-4ecd-9ef7-b6c84bb454da" />

## 2.5 Percentage of Global Population by Major Religious Groups (Bar Chart)
The horizontal bar chart displays population distribution by religious affiliation, presenting Christianity as the largest group, followed closely by Islam. Other categories such as those with no religious affiliation and Hinduism represent substantial proportions as well. The results reinforce religion as a significant demographic characteristic globally, while also indicating the growing secular trend in certain regions. The horizontal layout improves readability, particularly with categorical and non-numerical labels, making it suitable for comparison-based interpretation.

<img width="444" height="281" alt="image" src="https://github.com/user-attachments/assets/20b04fbd-4d96-4e9b-8101-a2c9402509a2" />

## 3. REPORTS
The report demonstrates effective use of Power BI’s online data connectivity features. Online data sources could have been accessed through the Web connector in Power Query, enabling extraction from APIs, publicly available data portals, or structured web tables such as the World Bank datasets, United Nations population tables, or Pew Research data. Transformations would have included filtering, normalising values, and establishing data types suitable for calculations and modelling. Data relationships would then be maintained in a structured model, potentially using a star schema for clarity and efficiency. Measures and aggregations were likely written using DAX to compute totals, percentages, and growth indicators. Once published to Power BI Service, scheduled refresh functionality ensures that the report updates automatically in alignment with new data releases. The report is visually clear and logically structured. It progresses from historical context through present-day geographic distribution and finally into cultural demographic segmentation. The colour consistency, geographic mapping, clean labelling, and strong visual hierarchy contribute to professionalism and readability. The report format is scalable and capable of supporting additional views such as forecast projections, age structure analysis, or socio-economic overlays.

<img width="1417" height="829" alt="Screenshot 2025-12-07 173211" src="https://github.com/user-attachments/assets/ccde021f-66f0-411d-8788-06142aad6b5e" />








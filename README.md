# :airplane: Clearing the Skies: Tracking Aviation CO₂ Emissions
A data analytics capstone project exploring the environmental impact of aviation emissions using Climate TRACE data.
---
## :pushpin: Problem Statement
Aviation CO₂ emissions are rising every year. However, we don’t fully understand which countries or flight types are responsible for the majority of emissions. There is also a lack of clarity on how airport count or population size affect emission levels. This project aims to explore these patterns more clearly.
---
## :dart: Objectives
Explore aviation emissions using simplified data and visualizations.
Identify top emitting countries and flight types (domestic vs. international).
Analyze emissions trends over time.
Compare emissions in small tourist vs. non-tourist islands.
Investigate how emissions relate to population and airport count.
---
## :bust_in_silhouette: Target Audience
Environmental analysts 
Policymakers 
Sustainability researchers 
---
## :bar_chart: Datasets Used
**Main Source:** [Climate TRACE Aviation Emissions Data](https://climatetrace.org/data) 
This included two datasets for domestic and international aviation, which were merged.
**Additional Data Added:**
Country names (from ISO3 codes)
Population per country
Airport count per country
---
## :wrench: Data Handling
**Column renaming** and cleaning for clarity.
**Categorical to numeric conversion**: 
  Values such as `Very Low`, `Low`, ..., `Very High` were converted to numeric scale (1 to 5) for the following columns:
`source_type`
`capacity`
`capacity_factor`
`activity`
`emissions_factor`
`emissions_quantity`
---
## :chart_with_upwards_trend: Key Findings
**Top 5 emitters**: USA, China, Canada, Brazil, and Russia.
**Tourist islands** (e.g., Seychelles, Maldives) had surprisingly high emissions compared to small non-tourist islands.
**Domestic and international flights** contribute almost equally to global emissions.
**2023** showed the highest recorded emission levels.
Countries with large populations or more airports tend to have more emissions — but not always.
---
## :white_check_mark: Recommendations
Focus reduction efforts on high-traffic international routes.
Invest in cleaner aviation infrastructure.
Re-evaluate responsibility for smaller but high-impact countries.
Improve data accuracy and collection, especially in underrepresented regions.
---
## :warning: Limitations
The dataset was **qualitative**, not quantitative.
Column names were sometimes **misleading or unclear**.
The structure of the dataset required extra effort to understand.
Some data was **inaccurate**, e.g., the number of airports listed for Bahrain.
---
## :link: References
Climate TRACE: [https://climatetrace.org/data](https://climatetrace.org/data)
OAG (Official Airline Guide) Methodology 
World Bank Open Data (for population statistics)

climatetrace.orgclimatetrace.org
Data Downloads - Climate TRACE
Climate TRACE makes climate action faster and easier by mobilizing the global tech community to track greenhouse gas (GHG) emissions.

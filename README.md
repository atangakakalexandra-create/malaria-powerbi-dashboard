# Malaria Incidence Dashboard (Power BI)
An interactive Power BI dashboard of malaria incidence (new cases per 1,000 people at risk) across 107 countries, 2000-2024.
## Data source
Our World in Data, from WHO via the World Bank (CC BY): https://ourworldindata.org/grapher/incidence-of-malaria
## What I did
- Loaded and cleaned the data in Power Query (renamed columns, removed non-country groups such as World and income-level groups)
- Built a data model with a Regions table linked to the main table
- Created a card, line chart, bar charts, a table and slicers (Country and Region)
## Key findings
1. Nigeria's malaria incidence fell from 401.79 per 1,000 in 2000 to 294.25 per 1,000 in 2024.
2. Burkina Faso, Central African Republic and Benin had the highest average incidence across 2000-2024.
## Tools
Power BI Desktop, Power Query, data modelling
## Files
- malaria-dashboard-v2.pdf: the finished dashboard
- incidence-of-malaria (2).csv: the dataset used
Related project: [SQL analysis of the same data](https://github.com/atangakakalexandra-create/sql-practice)

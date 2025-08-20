# Nigeria Foreign Trade Analysis 
### Project Overview
This project explores Nigeria's Foreign Trade Goods Statistics (Q3 2024) dataset published by the National Bureau of Statistics (NBS). The goal is to clean messy government data, transform it into usable form, and generate insights using Python (pandas, matplotlib).

### Data Source
- Dataset: Foreign Trade in Goods Statistics Q3 2024 [Download here](https://microdata.nigerianstat.gov.ng/index.php/catalog/84/download/1063/Q3_2024_Foreign_Trade_Statistics_Table.xlsx)
- Format: Excel (15 tables in a single file, semi-structured)

### Tools Used
- Python (pandas, matplotlib, seaborn) &rarr; Data cleaning & visualisation
- Jupyter Notebook &rarr; Workflow documentation
- GitHub &rarr; Project sharing and version control

### Data Cleaning Steps
- Removed metadata rows (e.g. table titles, repeated headers).
- Forward-filled missing Year values in the first column.
- Standardised column names (Imports, Exports, Balance, etc.)
- Extracted yearly, quarterly, and monthly breakdowns into tidy format.
- Converted values from text to numeric.
- Created a clean Excel sheet for reuse.

### Key Metrics & Insights
1. Trade Balance Trends
   - Some years show negative balance, driven by high imports.
   - Oil exports remain the largest share, but non-oil exports are rising slowly.
2. Quarterly Volatility
   - Q3 2024 shows a 13.26% increase compared to Q2.
3. Exports Composition
   - Crude Oil still accounts for >70%of exports.
   - Non-oil exports remain below 10%, showing limited diversification.
4. Growth Patterns
   - Import growth outspaces export growth in some periods, widening trade deficit.

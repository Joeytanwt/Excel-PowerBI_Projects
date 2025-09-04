# Data Analysis in Excel with Pivot Tables and Charts
## Project Overview
This project cleans raw customer and sales data in Excel and builds interactive pivot tables and charts to analyse bike purchases by age group, income, and commute distance.

## Data Cleaning
### 1. Remove duplicates
Created a copy of data into a new sheet to preserve original dataset.

Used Excel’s Data > Remove Duplicates to de-duplicate the source table.

### 2. Find and replace

Standardised inconsistent text fields using Find & Replace.

### 3. Currency formatting

Applied appropriate currency formatting to income field.

### 4. Binning Age with IF function

Created age bins using ```=IF('Age'>54,"Age (55+)",IF('Age'>=31,"Age (31-54)",IF('Age'<31,"Age (<30)","Invalid")))``` function, reducing noise from too many unique ages and improving interpretability in charts.

## Analysis & Reporting
### 1. PivotTables for summaries

Built PivotTables to summarise purchase decisions by average income, gender, age brackets and commute distance.

### 2. Charts for visualization

Created PivotCharts to visualise distribution of purchase decisions.

### 3. Interactive dashboard with slicers

Added synchronised slicers to enable one-click filtering and faster exploration.

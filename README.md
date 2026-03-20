# Canadian Federal Workforce Analytics Dashboard

## Project Overview
This project analyzes publicly available Canadian federal public service workforce data to support HR reporting and workforce planning. It focuses on workforce size, department distribution, tenure structure, age profile, and geographic distribution across the federal public service.

The project was built as a portfolio case study aligned with junior HR Data Analyst, HR Reporting Analyst, and People Analytics-type roles. The goal was to demonstrate practical reporting and analysis skills using real public data, while staying realistic about the limits of aggregate workforce datasets.

## Business Problem
HR and business leaders need reliable workforce reporting to understand how the public service has changed over time, where workforce concentrations exist, and what structural patterns may affect planning and decision-making. Public workforce data exists across multiple files, but it must be cleaned, structured, and documented before it can support consistent reporting.

## Project Objectives
- Consolidate public workforce datasets into a clean reporting model
- Analyze workforce trends from 2010 to 2025
- Compare departments across workforce size and composition measures
- Build an interactive dashboard in Power BI for workforce reporting
- Document assumptions, KPI definitions, and data limitations

## Scope of Version 1
### Included
- Total workforce trend
- Department trend analysis
- Tenure analysis
- Age analysis
- Province/territory map

### Excluded
- Turnover
- Hires
- Terminations
- Employee-level HRIS logic
- Predictive modeling
- Advanced statistical modeling
- Employee experience survey analysis (deferred after profiling due to complexity)

## Data Sources
Public Canadian federal workforce datasets were used, including:
- Population of the federal public service
- Population of the federal public service by department or agency
- Population of the federal public service by department and tenure
- Population of the federal public service by department and age band
- Population of the federal public service by department and province or territory of work

## Data Preparation
The source files were cleaned and standardized before modeling in Power BI. Key preparation steps included:
- Renaming fields into a consistent naming convention
- Standardizing employee count fields across tables
- Removing pre-aggregated total rows from granular analysis tables
- Creating a simplified map field for province/territory reporting
- Handling suppressed values and documenting limitations
- Creating shared dimensions for year and department to support reporting relationships

## Dashboard Pages
### 1. Executive Overview
Provides a high-level summary of workforce size and structure, including:
- Total employees
- Number of departments/agencies
- Top departments by headcount
- Workforce composition by organization type
- Long-term workforce trend

### 2. Workforce Composition
Shows what the workforce looks like across:
- Tenure type
- Age band
- Geographic distribution
- NCR and outside-Canada workforce counts

### 3. Department Analysis
Provides deeper department-level comparison, including:
- Headcount change over the selected period
- Department comparison summary
- Top department headcount trends over time

## Key KPIs
- Total federal public service population
- Number of reporting departments/agencies
- Top department by headcount
- Headcount change over selected period
- Workforce composition by organization type
- Workforce composition by tenure type
- Largest age band
- NCR employees
- Outside Canada employees

## Key Insights
- Federal workforce size increased materially over the later part of the reporting period.
- Workforce composition is heavily concentrated in indeterminate employees.
- Mid-career age bands represent the largest portion of the workforce.
- Workforce distribution is concentrated in specific provinces/territories and the National Capital Region.
- Department growth is uneven, with some organizations expanding much more than others over the selected period.

## Assumptions and Limitations
- The datasets are aggregate, not employee-level.
- The project supports workforce reporting, not operational HRIS analytics.
- Turnover, hires, and terminations cannot be calculated directly from these public aggregate datasets.
- Suppressed values in some source files were handled according to source notes and documented as limitations.
- Geography data includes special categories such as NCR and Outside of Canada, which required separate handling for mapping.

## Tools Used
- Excel
- Power Query / data cleaning logic
- Power BI
- DAX

## Files
- `canadian_federal_workforce_analytics_dashboard.pbix`
- PDF export of dashboard
- Source data files
- Project documentation

## Why This Project Matters
This project was designed to reflect practical HR reporting work: cleaning public data, defining KPIs, building dashboards, documenting assumptions, and translating workforce data into usable business insight.

# salesforce-analysis
Analysis of Salesforce export data using Python and Jupyter Notebook.



# Salesforce Data Analysis with Python

## Project Overview
This project analyzes Salesforce export data (Opportunities, Leads, Accounts, Contacts) using Python and Jupyter Notebook.  
The dataset was exported via Salesforce Data Export Wizard and processed with pandas for insights.

## Files
- `Salesforce_Analysis.ipynb` → Jupyter Notebook with code, analysis, and visualizations
- `Account.csv`, `Contact.csv`, `Lead.csv`, `Opportunity.csv` → Salesforce export files

## Key Insights
- **Opportunities**: Closed Won stage dominates with 3.5M revenue.
- **Leads**: Majority are still “New” (13), with 7 qualified.
- **Accounts**: Education industry is most represented.
- **Contacts**: Titles need cleanup (“new” vs “New”).

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebook
- GitHub for version control

##  Next Steps
- Add visualizations (bar charts, pie charts).
- Explore real-time Salesforce API integration.
- Extend analysis to Snowflake or Power BI dashboards.


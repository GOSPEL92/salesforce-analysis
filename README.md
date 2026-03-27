# salesforce-analysis
Analysis of Salesforce export data using Python and Jupyter Notebook.

Salesforce → Python Analysis → Insights → Slack (updates) + Jira (tasks) → Team Action



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

- ##  Collaboration Demo: Slack & Jira Integration

Data analysis is most impactful when insights are shared and acted upon.  
This project demonstrates how Salesforce analytics can be integrated with collaboration tools:

###  Slack Integration
- Pipeline insights can be posted directly into team channels (e.g., *sales-insights-dashboard*).  
- Example: After running the notebook, a message is sent to Slack with revenue updates and lead status distribution.  
- This keeps sales and marketing teams aligned in real time.

###  Jira Integration
- Data quality issues and follow‑up actions can be tracked as Jira tasks.  
- Example: Inconsistent contact titles (“new” vs “New”) are flagged and automatically logged as a Jira issue on the *Sales Insights Dashboard* board.  
- This ensures accountability and continuous improvement.

### Why It Matters
- **Slack** → Instant communication of insights.  
- **Jira** → Structured task management for improvements.  
- Together, they show how analysis → communication → execution can flow seamlessly across teams.



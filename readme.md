#  Indian Startup Funding Analysis (Tableau Project)

This project analyzes the **Top 10 Indian Cities by Startup Funding in 2024** using Tableau.  
It demonstrates data cleaning, visualization, and insight extraction from a real-world dataset.

##  Dataset
- **Source:** [Kaggle - Indian Startup Funding](https://www.kaggle.com/datasets/sudalairajkumar/indian-startup-funding)
- **Columns Used:**  
    - `City_Clean`: Cleaned city names  
    - `Amount_Clean`: Funding amounts (numeric, cleaned)

*Only the cleaned columns needed for analysis are included here for clarity.*

##  Data Cleaning Workflow
- Downloaded original dataset from Kaggle.
- Cleaned "Amount" column in Excel by removing commas and converting text to numbers.
- Standardized city names using a VLOOKUP mapping table (Excel).
- Extracted only `City_Clean` and `Amount_Clean` for Tableau import.

##  Visualization Steps (Tableau)
- Imported cleaned Excel file into Tableau.
- Created a bar chart: `City_Clean` (Rows) vs. SUM(`Amount_Clean`) (Columns).
- Filtered to show only **Top 10 Indian cities** by total funding.
- Removed/excluded international and non-city entries.
- Customized color, labels, and chart title for professional presentation.

##  Key Insights
- **Bangalore** leads with a massive funding total, far ahead of other cities.
- **Mumbai**, **Gurugram**, and **Delhi** are major funding hubs.
- Other cities like **Noida**, **Chennai**, **Pune**, and **Hyderabad** also show strong activity.

##  Recommendations
- **Startups:** Consider Bangalore, Mumbai, and Gurugram for best funding opportunities.
- **Policymakers:** Invest in startup ecosystems outside the top 3 cities for a more balanced growth.
- **Data teams:** Always clean and standardize data before visualization for reliable insights.

##  Outputs
- [Download chart image here](viz/top_10_cities_funding.png)
- Tableau worksheet: [Download .twbx file](tableau/sheet1.twbx)

##  How to Use
1. Download the cleaned dataset (`data/startup_funding_cleaned.xlsx`).
2. Open in Tableau Desktop or Tableau Public.
3. Explore interactive visualizations or use the PNG for reports.

##  Tools Used
- Excel (data cleaning)
- Tableau Desktop Public Edition (visualization)

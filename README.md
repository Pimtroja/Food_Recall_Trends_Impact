# **US Food Recall Trends and Impact (2012 - 2025)**
Food recalls in the United States have had a significant impact on public health status and imposed financial burdens on businesses over the years. This project analyze food recall trends from 2012 to 2025 to indentify the most common causes and evaluate their effects on consumer health and business operations.

The goal:
*Isolate food recall data (excluding cosmetics and other non-food products)
*Group the data by recall type
*Count how many unique US states are impacted for each recall type
*Support data analysis and storytelling related to common causes and their impact on consumer health and business operations

Tools used:
*Language - Python, SQL
*Environment - Jupyter Notebook
*Libraries - pandas for data handling, re for regular expressions, collections (defaultdict) for clean counting logic, us for accessing US sate abbreviations and names.

Workflow:
1. Data Cleaning
   * Removed rows with missing, irrelevant entries, duplicate cases (subsetting "FEI Number") and white spaces
   * Filtered out cosmetic and unrelated product categories
   * Standardized recall type groupings 
2. State Counting Logic
   * Scan each row of the Distribution Pattern column
   * Searches for both state abbreviations and full state names
   * Ensure a row with both CA and California counts only once for California
   * Track counts of states per recall type
3. Output
   * Returns a summary showing the number of US states affected by each recall type
   * Can be visualized or exported for further geographic or demographic analysis
  
##### Data source from US Food & Drugs Administration (Recalls Details): https://datadashboard.fda.gov/ora/cd/recalls.htm?utm_source

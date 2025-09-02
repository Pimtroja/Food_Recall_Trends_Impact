# **US Food Recall Trends and Impact (2012 - 2025)**
Food recalls in the United States have had a significant impact on public health status and imposed financial burdens on businesses over the years. This project analyze food recall trends from 2012 to 2025 to uncover the most common causes, identify geographic hotspots, and evaluate correlations with state population.

The goal:
*Isolate and analyze food recall data (excluding non-food products)
*Identify top recall categories and affected regions
*Track recall trends over time and by geography
*Assess correlation between population and number of recalls
*Communicate findings through interactive visual storytelling

Tools & Methods:
*Python (Pandas, Regex, US Module)
*SQL for structured queries
*Jupyter Notebook for analysis
*Tableau for dynamic and geographic visualization
*Power BI for monitoring the trend based on the key insights

Workflow Highlights:
1. Cleaned and filtered raw FDA recall data
2. Standardized recall categories and removed non-food items
3. Parsed state names from distribution patterns using robust string matching logic
4. Summarized and aggregated recall events by state, category, and time
5. Merged with US Census data for demographic comparisons

Key Visuals:
[Tableau]
1. US Map with animated hotspots by recall type and year
2. Top 5 states by recall events (stacked bar)
3. Timeline trends by month and category
4. Recall events vs population (scatterplot with trendline)
[Power BI]
1. Yearly trend of the number of recall (line chart) - Interactive filters by recall reason category
2. Monthly Average Recall Trend (Line Chart) with Current Year Comparison – Interactive filters by reason category
3. Recall events vs population (combo chart) - Interactive filters by year, reason category, region and state

##### Data source from US Food & Drugs Administration (Recalls Details): https://datadashboard.fda.gov/ora/cd/recalls.htm?utm_source
##### Population source from US Census: www.census.gov

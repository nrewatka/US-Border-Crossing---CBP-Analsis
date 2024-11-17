# US Border Crossing:Control Border Protection-Dashboard

### Dashboard Link : https://app.powerbi.com/links/d67DCFXJLU?ctid=8e01b948-7f90-4068-a737-735638e01794&pbi_source=linkShare

### Dataset Link : https://data.bts.gov/Research-and-Statistics/Border-Crossing-Entry-Data/keg4-3bc2/about_data

## Problem Statement

This Power BI dashboard for U.S. border crossings provides a comprehensive analysis of cross-border traffic trends and enables stakeholders to understand the volume and nature of these movements better. By examining data on various transportation modes (such as trucks, personal vehicles, and trains), the dashboard reveals areas that may benefit from enhanced infrastructure and optimized resource allocation.

Through detailed visualizations, users can identify peak traffic times and assess the impact of crossings on national security, trade, and immigration policies. The forecasted increase in border traffic, especially commercial crossings, suggests the need for policy adjustments and infrastructure planning. Additionally, the insights into mode-specific trends support targeted improvements, such as enhancing truck lanes at high-volume ports or optimizing staffing based on traffic peaks.

By highlighting key metrics—such as the 11 billion total crossings, the projected 209 million crossings in 2024, and a 73.56% traffic share at the U.S.-Mexico border—this dashboard empowers decision-makers to address potential bottlenecks, streamline border processes, and make data-driven policy adjustments.


### Steps followed 

- Step 1: Imported the U.S. Border Crossing data from CSV files into Power BI Desktop.
- Step 2: In the Power Query Editor, enabled "Column Distribution," "Column Quality," and "Column Profile" to analyze data cleanliness and quality.
- Step 3: Adjusted the profiling option to analyze the full dataset instead of the default 1,000-row limit.
- Step 4: Addressed missing or erroneous data fields as needed, such as handling nulls in columns like "Border Crossing Volume."
- Step 5: Developed new calculated columns and measures using DAX for customized insights, such as average crossing volumes, seasonal trends, and specific crossing point usage.

For creating new column following DAX expression was written:
![Country](https://github.com/user-attachments/assets/bc56d127-0805-4182-98c0-bb11144ac0d8)

New measure was created to find People cross via Bus:
![Total Buses](https://github.com/user-attachments/assets/79928d48-9dc2-41e3-bd50-08b9a31ffd7b)

New measure was created to find People cross via Pedestrians:
![Total Pedestrians](https://github.com/user-attachments/assets/ba81f144-0b7b-4337-a937-e2256b09a51b)

New measure was created to find People cross via Personal Vehicle:
![Total Pedestrians](https://github.com/user-attachments/assets/ba81f144-0b7b-4337-a937-e2256b09a51b)

New measure was created to find People cross via Train:
![Total Personal Vechicle](https://github.com/user-attachments/assets/8de5f80d-7287-48ec-bed6-31d671e41b17)

New measure was created to find People cross via Truck:
![Total Truck](https://github.com/user-attachments/assets/8aacbc5c-bb83-441b-a31a-c0c3f06b4eb3)

- Step 6: Selected a dashboard theme to maintain consistent design aesthetics across visuals.
- Step 7: Created slicers to filter by fields such as "Border Location," "Transportation Mode," and "Month/Year."
- Step 8: Added visuals, including bar charts, line graphs, Pie chart, Donut Chart to display patterns in crossing volumes over time.
- Step 9: Used card visuals to highlight KPIs, such as total border crossings and average monthly crossings.

A KPI card visual was used to represent count Total Traffic Crossed till now.

![Total Traffic](https://github.com/user-attachments/assets/79c318eb-7a09-4dd4-ab64-f2e1e221e3bd)

A KPI card visual was used to represent count Total Traffic Crossed for current year.

![Total current Year](https://github.com/user-attachments/assets/26db0b2c-6650-497f-bff5-df2863a0f4d5)

- Step 10: Added a new page to provide a detailed view of individuals crossing the border, featuring two map visuals to illustrate border traffic patterns.

- Step 11: Utilized card visuals to emphasize key metrics, including total crossings along both the Mexico and Canada borders.

![Crossing Over Canada](https://github.com/user-attachments/assets/4892bfc6-ca61-40b0-9ad0-4a6451c1160f)

![Crossing Over Mexico](https://github.com/user-attachments/assets/68822c5d-42fc-475c-9907-c4b282b1adce)

# Snapshot of volumne crossing over Border:

![Border Comparison](https://github.com/user-attachments/assets/5746afec-93c6-45dc-9921-1bdfd48a1297)

- Step 12: Created a new page to display border crossing trends over the past three years, using a line chart to illustrate these patterns and apply forecasting features for the current year.

- Step 13: Published the report to Power BI Service, making it accessible for stakeholders.
 
![Public Message](https://github.com/user-attachments/assets/627af1a8-2560-4bb5-ba68-84050facf986)

# Snapshot of Dashboard (Power BI Service)

![Dashboard](https://github.com/user-attachments/assets/98f263af-57e9-4baa-8ac7-5334c61cdda7)

 
 # Border Analysis Snapshot (Power BI DESKTOP)

 
![Border Analysis](https://github.com/user-attachments/assets/df43e73f-a036-4abe-9cf7-06a0e6b06388)


# Over Time Analysis Snapshot (Power BI DESKTOP)

 
![Over Years](https://github.com/user-attachments/assets/4bc694a5-ca4e-45fa-b90b-e3008b346457)

# Insights

This dashboard allows for a comprehensive analysis of border crossing patterns and provides actionable insights:

- Total Border Crossings: Provides the overall number of crossings by year and highlights key locations with high traffic.
- Mode of Transportation: Analyzes which transport modes (e.g., vehicle, train, pedestrian) are most commonly used at different border points.
- Seasonal Trends: Identifies patterns in crossing volumes by month to highlight peak seasons and any off-peak trends.
- Economic and Policy Impact: Provides insights into how economic conditions or policy changes (like tariffs or visa rules) influence crossing patterns.
- Clustering Analysis: Groups border crossing points based on volume and other metrics to help categorize high-traffic and low-traffic areas.
- Anomaly Detection: Flags any irregular patterns in crossing volumes, helping stakeholders identify potential concerns or changes in activity.

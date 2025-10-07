Global Climate Events Analysis Dashboard
This repository contains the Power BI project for an interactive dashboard that analyzes the impact of global climate events. The dashboard provides a comprehensive overview of key metrics such as fatalities, injuries, affected populations, and economic impact across different countries and event types.
Dashboard Preview
🎯 Project Overview
The goal of this project is to visualize data related to various climate events and their consequences. By consolidating the information into an easy-to-understand dashboard, users can identify trends, compare the severity of different events, and analyze the impact on specific regions over time.
✨ Features
The dashboard is composed of several key visualizations:
 * Key Metrics Cards: At-a-glance view of the total deaths, injuries, and the currently filtered event type and country.
 * Impact per Capita: A gauge visual showing the relative impact on a per-capita basis for the selected region.
 * Temporal Analysis:
   * Injuries by Year: A bar chart comparing the percentage of total injuries across different years.
   * Events Over Time: A line chart tracking the frequency or impact of events on a monthly and yearly basis.
   * Affected Population Trend: A waterfall chart illustrating the cumulative or yearly increase in the affected population.
 * Categorical Analysis:
   * Deaths by Year: A donut chart showing the distribution of fatalities across the years in the dataset.
   * Economic Impact by Event Type: A bar chart comparing the economic consequences of different climate events (Cold Wave, Drought, Earthquake, Flood, etc.).
   * Affected Population by Country: A pie chart displaying the proportion of the total affected population by country.
Interactive Controls
Users can dynamically filter the entire report by:
 * Event Type (e.g., Cold Wave, Flood, Drought)
 * Country
🛠️ Tech Stack
 * BI Tool: Microsoft Power BI
 * Data Source: [Specify your data source here, e.g., CSV file from Kaggle, WHO database, etc.]
🚀 How to Use
 * Clone this repository to your local machine.
   git clone []

 * Open the .pbix file in Power BI Desktop.
 * If the data source is not embedded, you may need to update the data source path in the "Transform Data" -> "Data source settings" menu.
 * Interact with the slicers and visuals to explore the data.
📊 Data Source
The dataset used for this project is [Your Dataset Name], sourced from [Link to Data Source or Name of Organization].
(Note: Please replace the placeholder text above with the actual details of your data source.)
💡 Potential Improvements
 * Data Cleaning: The 'country' field appears to contain some placeholder or unknown values (e.g., 'DK') that could be cleaned or mapped correctly.
 * Clarity of Visuals: Improve the titles and labels on some charts for better readability (e.g., the 'year and month' line chart).
 * Add Tooltips: Implement custom tooltips to provide more detailed information when a user hovers over a data point.
 * Advanced Analytics: Incorporate forecasting models to predict future trends in affected populations or economic impact.
   
👤 Author
[Arawind]
 * LinkedIn: [Your LinkedIn Profile URL]
 * GitHub: [Your GitHub Profile URL]

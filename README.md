
---

# Flight Delays and Cancellations Analysis

This project analyzes and visualizes flight delays and cancellations using the 2015 dataset from the U.S. Department of Transportation's Bureau of Transportation Statistics. By creating various data visualizations, it highlights trends in delays, seasonal patterns, and correlations, offering insights that can aid airlines, travelers, and policymakers in understanding the dynamics behind flight delays.

## Project Overview

The analysis focuses on several aspects of flight delays, including:
- **Monthly and Daily Flight Trends**: Showing the busiest travel periods throughout the year.
- **Delay Causes**: Breaking down different types of delays (e.g., carrier, weather) and their impact.
- **Relationship Between Departure and Arrival Delays**: Analyzing correlations between delays at departure and their influence on arrival times.
- **Airline Performance**: Comparing delays across different airlines.
  
Using tools like Jupyter Notebook, BigQuery, and Tableau, this project provides an interactive and visual approach to understanding the flight delay data.

## Features

- **Data Cleaning**: Data preparation in Jupyter Notebook to handle missing values and ensure consistency.
- **Data Storage and Querying**: Cleaned data stored in BigQuery for fast, efficient querying.
- **Interactive Visualizations**: Created in Tableau, visualizations include:
  - A **scatter plot** showing the relationship between departure and arrival delays.
  - A **pie chart** illustrating the distribution of flights by month.
  - **Line and bar charts** displaying delay trends by airline and date.
  - **Dual-axis and area charts** for deeper insights into delay patterns.
  
## Dataset

The dataset contains information about flights in 2015 and includes fields such as:
- Flight dates, airline codes, origin and destination airports
- Delay times (departure and arrival)
- Cancellations and diversions

This dataset is publicly available from the Bureau of Transportation Statistics.

## Technologies Used

- **Python (Jupyter Notebook)**: For data cleaning and preparation.
- **BigQuery**: For storing and querying cleaned data.
- **Tableau**: For creating interactive and visually engaging data visualizations.

## Insights and Findings

- **Peak Travel Seasons**: The data reveals peaks in travel during certain months, with delays correlating with higher travel volumes.
- **Delay Correlation**: Departure delays have a noticeable impact on arrival times, stressing the importance of punctual departure handling.
Airline Comparisons: Differences in delay patterns between airlines provide insights into potential areas for service improvement.

## Getting Started

To get started with this project:
1. Clone the repository:
   ```bash
   [git clone https://github.com/yourusername/flight-delay-analysis.git](https://github.com/kavishkadinajara/SkyMetrics)
   ```
2. Set up a BigQuery project and load the cleaned dataset.
3. Open the Jupyter Notebook to review and modify the data cleaning process.
4. Explore the Tableau dashboard for interactive visualizations.
5. Download the original dataset from https://www.kaggle.com/datasets/usdot/flight-delays?resource=download

## Acknowledgments

Special thanks to the Bureau of Transportation Statistics for the dataset and to the open-source community for providing the tools that made this project possible.

---

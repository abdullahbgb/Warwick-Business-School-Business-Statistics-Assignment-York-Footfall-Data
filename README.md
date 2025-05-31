
## York Footfall Data Analysis - Project Overview

This project focuses on analysing footfall data in York to determine the optimal location for placing a promotional stall. As a promoter, your goal is to select a site that maximises passerby exposure. By leveraging daily footfall data collected from cameras at various locations, you will identify which spot attracts the most foot traffic.

## Data Integrity and Quality Check

1. Data Loading:
- Load the provided footfall dataset.
- Conduct thorough checks to ensure the data's integrity and quality before proceeding with further analysis.

## Analysis Tasks

2. Summary Table Generation:

For each measured location, provide a summary table with the following details:
- Date Range: The first and last recorded dates of footfall measurement at each location.
- Mean Daily Footfall: The average number of people passing by each day.
- Standard Deviation: The variability in daily footfall.
- Maximum Daily Footfall: The highest recorded daily footfall.
- Minimum Daily Footfall: The lowest recorded daily footfall.

3. Data Focus:
- Only use data from the year 2019, the last full year prior to the COVID-19 pandemic.

4. Footfall Distribution Plotting:
- Plot the distribution of footfall for all recorded days.
- Separate the distributions by location, clearly illustrating footfall patterns for each "LocationName."

5. Statistical Analysis:
- Perform a t-test to compare footfall between Coney Street and Stonegate.
- Conduct an additional t-test to compare footfall exclusively on weekends (Saturdays/Sundays) between Coney Street and Stonegate.

## Recommendations for Promoters

6. Location Advice:
Based on the analysis, advise whether to place the promotional stall on Coney Street or Stonegate:
- For All Days: Consider the overall footfall throughout the week.
- For Weekends Only: Focus on foot traffic specifically on Saturdays and Sundays.

# Bike Buyers Dataset Analysis Project

## Overview
This project involves analyzing a dataset of bike buyers to uncover insights into purchasing behavior based on demographic and socio-economic factors. The dataset, stored in an Excel file (`Excel Project Dataset.xlsx`), contains detailed information about individuals and whether they purchased a bike, along with attributes such as marital status, gender, income, education, occupation, and more. The project includes data processing, pivot table analysis, and a dashboard for visualizing key trends.

## Dataset Description
The dataset is organized into multiple sheets within the Excel file:
- **bike_buyers**: The primary dataset containing raw data with columns like ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike.
- **working_sheet**: A processed version of the dataset with an additional "Age Brackets" column categorizing ages into Adolescent, Middle Age, and Old.
- **pivot_table**: Contains summarized data, including:
  - Average income by gender and bike purchase status.
  - Count of bike purchases by commute distance.
  - Count of bike purchases by age brackets.
  - Count of bike purchases by individual age.
- **dashboard**: A placeholder sheet titled "Bike Sales Dashboard" for visualizing insights (not fully implemented in the provided data).

  <img width="1188" height="717" alt="Screenshot 2025-08-02 131624" src="https://github.com/user-attachments/assets/97243552-ed22-4a79-866a-45d165d561fd" />


## Objectives
- Analyze the relationship between demographic/socio-economic factors and bike purchasing decisions.
- Summarize key metrics such as average income and purchase counts by various categories.
- Provide a foundation for creating a dashboard to visualize trends and insights.

## Key Insights
- **Income Analysis**: The average income of males who purchased a bike ($60,123.97) is higher than those who did not ($56,208.18). For females, the average income is slightly higher for those who purchased a bike ($55,774.06) compared to those who did not ($53,440).
- **Commute Distance**: The majority of bike purchases occur among individuals with a commute distance of 0-1 miles (200 purchases), suggesting proximity to work may influence bike buying.
- **Age Brackets**: Middle-aged individuals (701 total) are the most likely to purchase bikes (383 purchases), compared to adolescents (110 total, 39 purchases) and older individuals (189 total, 59 purchases).
- **Age Distribution**: Bike purchases peak among individuals aged 35-38, with notable purchase counts at ages 36 (30 purchases), 38 (29 purchases), and 37 (28 purchases).

## Project Structure
- **Data Source**: `Excel Project Dataset.xlsx`
  - **bike_buyers**: Raw data with 1,000 rows.
  - **working_sheet**: Processed data with age brackets.
  - **pivot_table**: Aggregated statistics for analysis.
  - **dashboard**: Placeholder for visualization.
- **Analysis Approach**:
  - Data cleaning and preprocessing in the `working_sheet` to categorize ages.
  - Pivot tables in the `pivot_table` sheet to summarize income and purchase counts.
  - Potential for further visualization in the `dashboard` sheet.

## Potential Visualizations
To enhance the dashboard, the following visualizations could be created:
- **Bar Chart**: Compare bike purchase counts by commute distance to highlight the preference for shorter commutes.
- **Pie Chart**: Show the distribution of bike purchases across age brackets (Adolescent, Middle Age, Old).
- **Line Chart**: Illustrate bike purchase trends across individual ages to identify peak purchasing ages.
- **Bar Chart**: Compare average income by gender and bike purchase status to explore economic factors.

## How to Use
1. **Access the Data**: Open `Excel Project Dataset.xlsx` in Microsoft Excel or a compatible program.
2. **Review Raw Data**: Explore the `bike_buyers` sheet for raw data and the `working_sheet` for processed data with age brackets.
3. **Analyze Summaries**: Refer to the `pivot_table` sheet for key metrics on income and purchase counts.
4. **Build Visualizations**: Use the `dashboard` sheet to create visualizations based on the pivot table summaries (e.g., using Excel’s charting tools or a programming library like Recharts for web-based dashboards).
5. **Extend Analysis**: Add new pivot tables or visualizations to explore additional relationships, such as bike purchases by occupation or region.

## Tools and Technologies
- **Microsoft Excel**: For viewing and editing the dataset.
- **Data Analysis Tools**: Excel’s pivot table functionality or programming libraries (e.g., Python with Pandas, JavaScript with Recharts) for advanced analysis and visualization.
- **Visualization Platforms**: Excel, Power BI, or web-based frameworks for dashboard creation.

## Future Improvements
- **Enhanced Dashboard**: Develop interactive visualizations using tools like Power BI or a web-based solution with Recharts and React.
- **Additional Analysis**: Explore correlations between bike purchases and other factors like occupation, education, or number of cars.
- **Data Cleaning**: Address any missing or inconsistent data (e.g., handling truncated rows in the dataset).
- **Predictive Modeling**: Use machine learning to predict bike purchase likelihood based on demographic features.

## Notes
- The dataset contains some duplicated rows (e.g., rows 1002–1027 in `bike_buyers` match earlier rows), which may require deduplication for accurate analysis.
- The `dashboard` sheet is currently a placeholder and could be expanded with charts and interactive elements.
- The `pivot_table` sheet provides a solid foundation for insights but could be extended with more granular analyses.

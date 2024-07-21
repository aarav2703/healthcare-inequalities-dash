

# Health Inequities Dashboard

## Project Overview

This project involves the development of an interactive dashboard to monitor and analyze health inequities using public health data. The dashboard leverages data from the CDC and WHO to visualize trends, correlations, and combined analyses of mortality rates and life expectancy. The primary goal is to provide insights into health disparities across different states and countries.

## Objectives

1. **Trend Analysis**: Visualize the trend of mortality rates over the years to identify any significant changes or patterns.
2. **Correlation Analysis**: Explore the correlation between age-adjusted mortality rates and the number of deaths.
3. **Heatmap Analysis**: Provide a heatmap to show age-adjusted mortality rates by state and year.
4. **Life Expectancy Analysis**: Visualize the average life expectancy by country.
5. **Combined Data Analysis**: Integrate CDC and WHO data to analyze the relationship between deaths and life expectancy.

## Data Sources

- **CDC Data**: Mortality data sourced from the CDC's public databases, including crude death rates, age-adjusted rates, and related metrics.
- **WHO Data**: Life expectancy data sourced from the WHO's Global Health Observatory (GHO) database.

## Tools and Technologies

- **Python**: The primary programming language used for data processing and analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **Plotly**: Utilized for creating interactive visualizations.
- **Dash**: Framework used to build the interactive dashboard.
- **Google Colab**: Environment for developing and testing the code.

## Key Steps and Methodologies

1. **Data Acquisition**: Data was fetched from CDC and WHO APIs, ensuring real-time access and updates.
2. **Data Cleaning and Preprocessing**: Both datasets were cleaned and preprocessed to ensure consistency and compatibility for merging and analysis.
3. **Trend Analysis**: Trends in mortality rates were analyzed and visualized using line charts.
4. **Correlation Analysis**: The relationship between age-adjusted mortality rates and deaths was explored through scatter plots and correlation coefficients.
5. **Heatmap Visualization**: A heatmap was created to display age-adjusted mortality rates by state and year.
6. **Life Expectancy Analysis**: Average life expectancy by country was visualized using bar charts.
7. **Combined Data Analysis**: CDC and WHO data were merged to analyze the combined effects on mortality and life expectancy.

## Dashboard Features

- **Trend Analysis Tab**: Displays the trend of mortality rates over the years using line charts.
- **Correlation Analysis Tab**: Shows the correlation between age-adjusted mortality rates and deaths using scatter plots with trendlines.
- **Heatmap Analysis Tab**: Provides a heatmap visualization of age-adjusted mortality rates by state and year.
- **Life Expectancy Tab**: Visualizes the average life expectancy by country using bar charts.
- **Combined Data Analysis Tab**: Combines CDC and WHO data to analyze deaths and life expectancy through scatter plots.

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Ensure you have the necessary Python libraries installed. Refer to the `requirements.txt` file for the list of dependencies.
3. **Run the Dashboard**: Execute the Jupyter notebook in Google Colab or any local Jupyter environment to generate the visualizations and run the Dash app.

## Acknowledgements


- **CDC**: For providing access to comprehensive mortality data.
- **WHO**: For offering detailed life expectancy data through their Global Health Observatory.
- **Google Colab**: For providing an accessible environment to develop and test this project.
- **Plotly and Dash**: For visualization and dashboarding tools 

## Citation

- Centers for Disease Control and Prevention. [CDC Wonder API](https://wonder.cdc.gov).
- World Health Organization. [GHO OData API](https://ghoapi.azureedge.net/api).

## Contact

For any questions or feedback regarding this project, please contact:

Aarav Kalkar
Email: aaravkalkar@gmail.com

Thank you for exploring the Health Inequities Dashboard project. Your feedback and contributions are highly valued.

---

This README provides a comprehensive overview of the project, ensuring that anyone accessing the GitHub repository can understand the objectives, methodologies, and usage of the dashboard. It also acknowledges the sources and tools used in the project development.

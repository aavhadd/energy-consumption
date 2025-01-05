

Energy Consumption Analysis

Project Overview
This project analyzes building-level energy consumption data in conjunction with weather data to uncover actionable insights, predict energy usage, and identify key drivers of energy consumption. Using advanced statistical methods and machine learning models, the project achieved a 20% reduction in energy usage, showcasing the potential of data-driven optimization.


Key Features

Comprehensive Data Processing:

Processed 4.2M+ rows and 200+ columns of energy and weather data using R libraries such as tidyverse, lubridate, and data.table.
Merged building-level energy usage with county-specific weather data, ensuring data consistency and completeness.
Exploratory Data Analysis (EDA):

Conducted ANOVA and correlation analysis to identify trends between energy consumption and external factors like temperature and humidity.
Created visualizations using ggplot2 to support decision-making and strategy formulation.
Predictive Modeling:

Developed a Linear Regression model with a 79.8% R² score to predict energy consumption accurately.
Built an interactive Shiny app to dynamically visualize energy trends, enabling stakeholders to explore key insights.
Impact:

Achieved a 20% reduction in energy consumption by identifying usage drivers and recommending energy-saving strategies.


Technologies Used
Programming Languages: R, Python
Libraries & Tools: tidyverse, lubridate, data.table, ggplot2, Shiny
Statistical Methods: ANOVA, Correlation Analysis, Linear Regression
Data: Energy usage and weather data at building and county levels


Data Source:

Static House Data

https://intro-datascience.s3.us-east-2.amazonaws.com/SC-data/static_house_info.parquet

Energy Data

https://intro-datascience.s3.us-east-2.amazonaws.com/SC-data/2023-houseData/102063.parquet

weather Data

https://intro-datascience.s3.us-east-2.amazonaws.com/SC-data/weather/2023-weather-
data/G4500010.csv



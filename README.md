CitiBike Demand Analysis

Overview
This repository contains a detailed analysis of the CitiBike dataset, focusing on identifying the key drivers of bike demand and predicting future demands for specific stations. By understanding the underlying patterns, CitiBike can optimize bike allocations across stations, enhancing user satisfaction and ensuring efficient utilization.
## Introduction

CitiBike is a private bicycle-sharing service in New York City. The dataset provides a snapshot of the demand between different stations and contains data from June 1, 2017, to May 31, 2018. The study aims to forecast demand using a linear regression model for five chosen stations.

## Objectives

- Explore the dataset to understand its structure and the patterns it contains.
- Analyze descriptive statistics to gain insights into the variables.
- Create visualizations to depict trends and relationships in the data.
- Predict demand for daytime and evening for selected stations using a linear regression model.

## Technologies Used

- **Language**: R
- **Libraries**: ggplot2, class, ROSE, car, dplyr

## Steps to Reproduce

1. **Set up your environment**:
   - Ensure R and RStudio are installed.
   - Install the necessary R packages (`ggplot2`, `class`, `ROSE`, `car`, `dplyr`).
   
2. **Load the dataset** (`demand.csv`).
   
3. **Run the R Markdown script**:
   - Set your working directory to the location containing the dataset.
   - Load the required libraries.
   - Execute the embedded R code chunks within the R Markdown document.

## Results

1. The dataset was explored using functions like `dim()`, `str()`, `colnames()`, `head()`, and `tail()`.
2. Descriptive statistics were computed for various variables, revealing insights like:
   - Average demand for bike trips.
   - Correlation between demand and temperature, daily snowfall, and daily precipitation.
   - Insights into customer proportion, per capita income, and households without vehicles.
3. Visualizations were created to depict:
   - The impact of the month on demand.
   - Distribution of demand across different days of the week, times of the day, and months.
   - Histograms for demand, start percentage of households with no vehicles, end percentage of households with no vehicles, start per capita income, and end per capita income.
   - Scatter plots showing the relationship between demand and various predictors.
4. A linear regression model was built to forecast the daytime and evening demand for five selected stations based on predictors like `DemandTime`, `StartStationId`, `EndStationId`, and `StartPerCapitaIncome`.

## Conclusion

The CitiBike dataset provides valuable insights into the demand patterns for bike-sharing in New York City. The analysis successfully predicts the demand for bicycles at selected stations based on certain predictors. The findings can be beneficial for policymakers and CitiBike administrators to make informed decisions about resource allocation and service improvements.

---

To reproduce the analysis:

1. Ensure that R and RStudio are installed.
2. Clone/download the repository.
3. Open the R Markdown file in RStudio.
4. Install the required packages.
5. Set the working directory to the location of the `demand.csv` file.
6. Execute the R Markdown file to generate the report.

---


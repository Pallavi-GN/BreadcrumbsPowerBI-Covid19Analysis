# PowerBI-Covid19Analysis

## Objective
The primary goal of this project is to conduct a comprehensive analysis of COVID-19 data sourced from Covidometer. The dataset has undergone a rigorous cleaning process, and various analytical measures have been applied to derive meaningful insights. The focus is on visualizing key metrics and patterns, aiding a deeper understanding of the pandemic's impact across different continents.

## Data Overview
The dataset contains the following columns:

1.TotalCases

2.NewCases

3.TotalDeaths

3.NewDeaths

4.TotalRecovered

5.NewRecovered

6.ActiveCases

7.Serious, Critical

8.Tot Cases/1M pop

9.Deaths/1M pop

10.TotalTests

11.Tests/1M pop

12.Population

13.Continent

## Data Cleaning/Preparation

The raw data extracted from Covidometer(website) has been cleaned to ensure accurate and reliable analysis. Any missing or inconsistent values have been addressed to maintain data integrity.

##  Zone Classification
A new column 'Zone' has been created using the 'Serious, Critical' column to categorize the severity of cases.

## Visualizations
a. Slicer
A slicer has been implemented to provide an interactive filter for the dataset, allowing users to focus on specific regions or continents.

b. Cards
Cards have been used to display key metrics such as Active Cases, New Cases, and Total Cases for quick reference.

c. Stacked Bar Chart
A stacked bar chart has been employed to visualize the distribution of TotalCases, TotalDeaths, and TotalRecovered for each continent.

d. Stacked Column Chart
A stacked column chart has been used to illustrate the breakdown of ActiveCases, Serious, Critical cases, and TotalRecovered for different continents.

## Conclusion
This analysis provides valuable insights into the COVID-19 data, offering a clear understanding of the current situation across continents. The visualizations and key metrics help stakeholders and decision-makers in making informed decisions and understanding the impact of the pandemic.

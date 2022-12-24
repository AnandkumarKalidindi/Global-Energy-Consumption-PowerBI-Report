# Global-Energy-Consumption-PowerBI-Report
Visualization of Global energy consumption using power BI

## OVERVIEW

The main objective of this project is to analyze and visualize energy trends of different countries in different years using Power BI.Here, I have taken dataset from the kaggle and pull the dataset into the jupyter notebook using pandas and read the dataset which is available in the csv file into the pandas dataframe.The analysis and visualization will give us an idea of which energy is consumed more in different countries in different years.The Power BI report is divided into 4 parts. In the first part, i have given an overview of electricity generation from different energy sources,energy consumption from different energy sources,per capita of each energy source, electricity share of each energy source from different countries in different years.In the second part i have visualized the trends of fossil fuels from different countries in different years. In the third part i have visualized the trends of renewables and in the last part i have showed the visualization comparison between fossil fuels and renewables.By this comparison one can understand whether the particular country is shifting from the consumption of fossil fuesl to renewables on the each passing year as the fossil fuels consumption is the main cause for the global warming which can cause the natural calamities.

## DATA CLEANING

Performed data cleaning like droping unwanted columns, replacing null values with the aggregate functions and used BFILL and FFILL methods.As the dataset consists of 17432 rows and 122 columns, i have trimmed the dataset by taking only popular countries and taken years from 2000 to 2020. By trimming the dataset, the size size of the dataset is reduced to 415 rows and 44 columns. Here I have divided the dataset into five parts.The first part consists of basic details like country, year, population, gdp and the next part consists of electricity generation,energy consumption,electricity per capitta and electricity share of each energy source.In the Power Bi i have performed data transformation like unpivoting columns in table, creating new measures for the visualization purpose etc.

![OVERVIEW]("C:\Users\Anand\OneDrive\Desktop\Overview page.png")

## FOSSIL FUELS



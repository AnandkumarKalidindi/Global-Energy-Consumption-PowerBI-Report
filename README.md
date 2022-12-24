# Global-Energy-Consumption-PowerBI-Report
Visualization of Global energy consumption using power BI

## OVERVIEW

The main objective of this project is to analyze and visualize energy trends of different countries in different years using Power BI.Here, I have taken dataset from the kaggle and pull the dataset into the jupyter notebook using pandas and read the dataset which is available in the csv file into the pandas dataframe.The analysis and visualization will give us an idea of which energy is consumed more in different countries in different years.The Power BI report is divided into 4 parts. In the first part, i have given an overview of electricity generation from different energy sources,energy consumption from different energy sources,per capita of each energy source, electricity share of each energy source from different countries in different years.In the second part i have visualized the trends of fossil fuels from different countries in different years. In the third part i have visualized the trends of renewables and in the last part i have showed the visualization comparison between fossil fuels and renewables.By this comparison one can understand whether the particular country is shifting from the consumption of fossil fuesl to renewables on the each passing year as the fossil fuels consumption is the main cause for the global warming which can cause the natural calamities.

## DATA CLEANING

Performed data cleaning like droping unwanted columns, replacing null values with the aggregate functions and used BFILL and FFILL methods.As the dataset consists of 17432 rows and 122 columns, i have trimmed the dataset by taking only popular countries and taken years from 2000 to 2020. By trimming the dataset, the size size of the dataset is reduced to 415 rows and 44 columns. Here I have divided the dataset into five parts.The first part consists of basic details like country, year, population, gdp and the next part consists of electricity generation,energy consumption,electricity per capitta and electricity share of each energy source.In the Power Bi i have performed data transformation like unpivoting columns in table, creating new measures for the visualization purpose etc.

![Overview page](https://user-images.githubusercontent.com/121304061/209445507-538c1964-bb29-4d5c-bbce-61038a84e8eb.png)

## FOSSIL FUELS

Here, in this visualization page i have taken only the fossil fuesl data from the dataset by taking the energy sources that comes from the fossil fuesl like coal,oil,natural gas and nuclear energy. I have taken nuclear energy as the fossil fuel energy although the nuclear energy is a recycle energy becauce the nuclear energy is produced with the help of uranium atoms and perform nuclear fission between the urannium atoms for the generation of the nuclear energy.As the process for mining and refining the uranium ore requires lot of fossil fuel energy hence i have taken nuclear energy is fossil fuel energy.

![Fossil Fuel page](https://user-images.githubusercontent.com/121304061/209446167-56dbb4d2-a936-4ea2-9ca8-f9e39c368013.png)
 
## RENEWABLES

In the renewables page, i have taken the renewables data from the dataset.The renewable energy includes energy from the solar,wind,biofuel and hydro.This renewable page will show the electricty generation ,electricity per capita of ,energy consumption of and electricity share from the renewable sources.The visualization of these data is shown with the help of diiferent charts like bar charts,pie charts,stacked column charts and map.This visualization will give us an idea of how the renewables energy is generated and consumed and whether the share of renewablle energy is increasing in the each passinng years and the electricty per capita of renewable energy which means for each person how much reneable energy is consumed.

![Renewables page](https://user-images.githubusercontent.com/121304061/209446574-5f3822a1-6c3f-48e2-92a1-e8cac4164868.png)

## FOSSIL FUELS VS RENEWABLES

In this part, i have taken both the renewables and fossil fuels data separately and visualized both the data on the same page by taking electricity generation,energy consumption,electricty per capita,electricity share of fossil and renewable energy sources in different visuals. This page will give us a perfect overview of the energy trends between fossil fuels and renewables.By taking this data and visualizations into consideration, one can get a clear idea of energy trends of both fossil fuels and renewables from different countries in different years.

![Fossil fuel vs renewables page](https://user-images.githubusercontent.com/121304061/209446630-dd2ec722-7eca-4bfd-989e-e3d1b89788d9.png)



## Overview 
The purpose of the project was to analyze data for a ridesharing company called PyBer to provide recommendation addressing any disparities among the city types.

<img width="942" alt="RIDE SHARING" src="https://user-images.githubusercontent.com/98617082/185946033-5602e335-3c9d-4b0d-b625-c3baa34739bf.png">


## Data
Three CSV files including information on: 1. Ride data with location, date and fare for every ride, and 2. City data which describes type of city and number of drivers and month wise fare. The goal was to compare quantity and fares of rides in every city type: urban, suburban and rural; 
Size: 125 KB

![image](https://user-images.githubusercontent.com/98617082/185997480-cb67f6aa-d941-4efa-ace8-85d3da45a852.png)

## Results
Creating a Dataframe to include Total rides, drivers, Fares ,average fare per ride and per driver for each city tpe has resulted in following insights:
* The volume of rides in urban cities is much highest followed by suburban and then rural. Volume in Urban cities is 13x of rural and 2.6x of suburban.
* Despite low volume, rural centres generate highest Average fare per ride and Average fare per driver. Average fare per ride in rural centres is 1.4x of Urban cities and Average fare per driver is whooping 3.4x times of urban cities.
* Total drivers in urban centres are 30x of their rural counterparts resulting in high fare per driver.

![image](https://user-images.githubusercontent.com/98617082/161192309-c4e476b7-185c-4248-ae98-3c879b38e037.png)


Multiple line plot is used to demonstrate total weekly of the fares for each type of city between 01-Jan-2019 to 29-April-2020. 

![image](https://user-images.githubusercontent.com/98617082/161192457-eb54c403-14e5-4987-b149-9c5323f4bf68.png)


The line chart clearly demonstrates that Urban cities generate the highest fares followed by suburban cities and then rural centres. Winter months are slightly lower as followed by as small jump in total fares for all centres end of May. Sururban centres see a sharp decline after peaking in the end of February.

# Summary
Basis the charts and data analysed from the above data points, I recommend the following to CEO for addressing disparities among the city types
* Doing a market survey in suburban and rural markets to analyse if there is more scope for growth since the total drivers are disproportionately high and each driver in suburban and rural centre is taking far more rides compared to their urban counterparts. 
* Reviewing the pricing policy for Urban centres to determine if just distances resulting in lower average high fares for each ride or there are other factors including promotions or offers. 
* Adding promotions in the winter month of January especially in rural areas to boost demand.

## Resources
Software: Jupyter Notebook, Pandas, Matplotlib

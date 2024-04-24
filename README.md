# Data Visualization Project

## Project Overview
This project presents an interactive dashboard that visualizes COVID-19 data across different countries. The goal was to elucidate relationships between countries in terms of COVID-19 impact using an integrative approach combining various types of visualizations like maps, bar charts, and line charts.


## Data Source
The dataset used for this visualization project is sourced from a publicly available GitHub gist, which includes COVID-19 cases and deaths data across multiple countries://gist.github.com/KangjianWu/db06675bba6753a66a7dcb861d37dbf7


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How to show the relationship between different countries on COVID-19 data through data visualization?
 * How to represent relationships between data in a visualization?
 * Which data need extra attention and which can be appropriately ignored?
 * How to integrate these different forms of visualization (bar charts, histograms and maps) into an interactive dashboard?

## Answer to These Questions

 * Use a world map to show data between different countries.
 * Different data relationships are shown through different colors for each country on the map as well as a legend
 * There are some countries for which data are not available, and others whose names in the dataset do not match the names on the map and require additional attention.
 * A bar chart has been added to the map, so that when the mouse moves over a country, the corresponding bar chart will appear, showing some specific data.

## Sketches
1.to show the relationship between different countries on COVID-19 data, the most efficient and intuitive way is to use a world map to show data between different countries.
![COVID-19 map](https://github.com/KangjianWu/dataviz-project-template-proposal/assets/124107340/5d8fbab6-2cec-4bbe-a4ee-1282f2ec0816)
2.to represent relationships between data, since the dataset does not have a point in time, I need to design a bar graph to show the number of cases or deaths per million people with COVID-19
![COVID-19 deaths](https://github.com/KangjianWu/dataviz-project-template-proposal/assets/124107340/6ce32293-f59f-4b73-83f9-a1f8524a65df)
![COVID-19 cases](https://github.com/KangjianWu/dataviz-project-template-proposal/assets/124107340/89e77c78-308e-464c-acb3-ee20b7d9ae21)


## Prototypes

I’ve created a proof of concept visualization of this data. 
1. It's a bar chart and it shows Top 10 countries by COVID-19 cases                   
   https://vizhub.com/KangjianWu/3e6b82a776c84ee8a95003d5b943dbf7
2. It's a simple scatter plot and it shows Covid cases and deaths worldWide
    https://vizhub.com/KangjianWu/ea8b5ebe25f34b969bde75ed3e7d8ab7
3. It's a line chart and it shows COVID-19 total cases in the world's most populated countries
    https://vizhub.com/KangjianWu/3bfa2074b5b2425696aca9637b9def54



## Milestones
Week1: Set up GitHub repository adn clean the dataset.                                                                                                              
Week2: Finish a world map with some covid-19 data, make a simple draft.                                                         
Week3: Design a bar gragh to show the number of cases or deaths per million people with COVID-19.                             
Week4: Gather two visualization in one, and adjust the layout.                            
Week5: Design a viz responsive and improve user interface.     

## Left Work
1: Add more interactivity, such as panning and zooming                                                                                                             
2: Changed some text and map colors to improve contrast                                                         
3: There is some data that doesn't show up well, find out what's wrong and fix it!                          


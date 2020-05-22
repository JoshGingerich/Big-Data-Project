# Big-Data-Project
This project uses Oracle SQL Developer and a dataset of over seven million crimes in Chicago to find valuable insights and 
develop a monitoring system to see the real-time levels of crime occurring throughout the city.

Here is a link to the data that the project utilized: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

The first part of the project was to place each crime into a geographic grid cell based on the longitude and latitude of where
a crime occurred. The heat map below was then created to display all of the grid cells in Chicago with their varying levels of
total crime.

The primary purpose of the project was to develop a crime monitoring system that would receive crimes as they occurr in real
time over the course of a month and would update the critical level of the grid cell where the crime occurred. The critical
level represents the relative intensity of crime in a grid cell over the past 24 hours. The system then outputs the top ten 
grid cells with the highest critical levels of crime for every hour of every day in the given month. The system allows the 
user to specify the month and year of choice to examine.

If the user specified April, 2013, here would be a sample portion of the output the system would give:



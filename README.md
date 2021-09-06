# Traffic-analyzer

Building AI course project


## Summary

Traffic Analyzer is an application that aims to predict the values of carbon emissions, traffic trends by subcategories of vehicles.

## Background

This application aims to solve two major problems: pollution and traffic congestion.
Pollution (https://www.co2.earth/) must have a downward trend in the coming years and to make the right decisions both locally and globally, but for this we need to have some concrete data.
This data can be provided by an application that analyzes car traffic. Application that can predict with a certain accuracy the categories of vehicles that pollute the most, but also other information and trends about traffic.

The data provided by the application could help to:
  * types of vehicles
  * car age
  * pollution
  * traffic congestion
  * the area of origin of the vehicles

![Traffic Analyzer](/Prezentare1.jpg)


## Data and AI techniques:

The problem can have several ways to solve it, each with a certain precision:
  * The first way to solve the problem is a standalone application, in which data is collected using a surveillance camera. These data are images with cars, which must be recognized and classified based on training data. After classification, certain calculations can be performed in order to predict trends.
  * The second way also uses a surveillance camera to collect data, but also involves querying a database. The data are images with vehicle registration numbers, which require recognition algorithms. After identifying the registration numbers in the database, detailed information about the vehicle is also obtained. With the latter data, regressions can be used to predict certain trends.


## How is it used

Although the first approach provides less accurate data, it will be presented as a mode of operation, because the application is independent and does not use databases of other organizations.
Broadly speaking, the application detects vehicles and divides them into categories and subcategories, providing data such as the pollution norm, the age of the vehicles, the place where they were registered, as well as their daily inventory.
Knowing the pollution norms and the number of vehicles, we can calculate the CO2 emissions produced by vehicles in a certain locality (if we have a small number of surveillance cameras) or in a region (if we have a larger number of rooms (input data)).
Using different regression algorithms, a prediction of CO2 emissions can be made.
The higher the traffic congestion, the higher the carbon emissions. Therefore, the application aims to predict a trend of increasing or decreasing traffic in certain areas.
If the region of origin of the cars is also known, traffic could be redirected to avoid possible traffic congestion, or it could help local authorities in making decisions to build new detours, or to increase the number of lanes.
If it is known which types of vehicles pollute the most, decisions could be made to replace them with less polluting ones.
The basic idea is that it could support local authorities in implementing solutions to reduce pollution.


## Challenges

If we work with the variant in which we have an independent application (it does not query a database), the accuracy with which the CO2 emission is calculated may contain some errors.
These errors can come from the inaccurate calculation of the pollution norm (we have an image of a vehicle, after which only the time interval in which that vehicle was made can be determined, so we cannot determine exactly the pollution norm).
The real challenge is in the most accurate classification of vehicles and in the use of techniques to reduce errors in determining pollution rules.


## What next

The accuracy of estimating the pollution norm can be greatly increased by reading the registration number and consulting a database that contains data about vehicles (car register).
In such an approach, prediction errors tend to zero.

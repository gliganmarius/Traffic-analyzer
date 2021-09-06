# Traffic-analyzer

Building AI course project


## Summary

Traffic Analyzer is an application that aims to predict the values of carbon emissions, traffic trends by subcategories of vehicles.

## Background

This application aims to solve two major problems: pollution and traffic congestion.
Pollution must have a downward trend in the coming years and to make the right decisions both locally and globally, but for this we need to have some concrete data.
This data can be provided by an application that analyzes car traffic. Application that can predict with a certain accuracy the categories of vehicles that pollute the most, but also other information and trends about traffic.

The data provided by the application could help to:
  * types of vehicles
  * car age
  * pollution
  * traffic congestion
  * the area of origin of the vehicles

![Traffic Analyzer](/Prezentare1.jpg)


## Data and AI techniques:

The problem can have several ways to solve it, each with a certain precision.
  * The first way to solve the problem is a standalone application, in which data is collected using a surveillance camera. These data are images with machines, which must be recognized and classified based on training data. After classification, certain calculations can be performed in order to predict trends.
  * The second way also uses a surveillance camera to collect data, but also involves querying a database. The data are images with vehicle registration numbers, which require recognition algorithms. After identifying the registration numbers in the database, detailed information about the vehicle is also obtained. With the latter data, regressions can be used to predict certain trends.

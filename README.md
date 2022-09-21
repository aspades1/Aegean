## Airline Interview

#Contents:
  Data cleaning and transformation
    Contains the jupiter notebook where data cleaning and transformation. The #1 first objective is answered in this file.

  Requirements
    Contains a .txt file with the required libraries and their most efficient versions.

  Airport delay analysis
    Contains the jupiter notebook where analysis is conducted. Objectives #2 & #3 are answered in this file.

  Presentation
    Contains the final presentation of the project.

#Instructions given:

Please submit the description of the execution plan, the code, the output, and any comments.

You can use any tool/programming language/ library you wish. Please include any dependencies/ instructions required to recreate the output. Data

The datasets that you will work with are located at https://www.kaggle.com/usdot/flight-delays Flights.csv contains flight data regarding 2015 US flights. Each row can be identified by (YEAR, MONTH, DAY, AIRLINE, FLIGHT_NUMBER, TAIL_NUMBER, SCHEDULED_DEPARTURE)

For the purposes of this exercise, we will assume that all times are in the same time zone. Tasks

Task 1: We would like you to left join flights with airlines and airports using their respective IATA code. Please describe the resulting dataset ‘flights_extended’: Number of rows, null values if any. Also, please describe any cleaning processes you may find useful or necessary.

Task 2: We would like to perform an analysis in the top 10 airports in terms of departure delay. Please create a metric to rank each airport according to the average number of aircraft that departed from that airport having a DEPARTURE_DELAY > 15 mins. Please describe if such a metric would be efficient to compare airports and include any suggestion to improve such a comparison.

Task 3: We would like to find the association, if any, between these top 10 airports and the aircraft that had no previous arrival delay (ARRIVAL_DELAY < 15) on a given day but they had arrival delay > 15 mins as soon as they departed from these airports. Please create any metrics and plots and use any technique you deem necessary to indicate the potential existence of such a phenomenon.


#Project Description:
The main concept is to: 
-identify delays in airports. 
-find the lowest performing airports. 
-examine relationship between previous arrival and concequent arrival.

We use graphs and perform OLS/logistic regretion to examine the causal relationship.

A presentation with the results is provided.

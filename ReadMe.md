# Indian Airlines Ticket Price Analysis

## About the dataset
Dataset Link: 

Dataset contains information about flight booking options from the website 'Easemytrip' for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

The various features of the cleaned dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.
3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.
4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.
8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
11) Price: Target variable stores information of the ticket price.

## Research Questions

The aim of this project is to answer the following questions:

1) What are number of flights operated by each airline?
2) What is price range according to class of travel?
3) What is availability of Tickets according to class of travel?
4) What is price of ticket for different airlines based on duration of flight? 
5) How do ticket prices vary across different airlines and class of travel?
6) How do airline ticket prices vary depending on when you buy them?
7) How does price of ticket vary depending on duration of flight?
8) How does ticket price vary according to departure time and arrival time?
9) How does ticket price vary depending on source and destination?
10)How does price of tickets vary based on no. of stops and airline?
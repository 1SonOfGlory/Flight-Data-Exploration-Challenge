# Flight-Data-Exploration-Challenge

## Exploring Flight Data from the US Department of Transportation

In this challenge, we delve into a real-world dataset containing flight data from the US Department of Transportation to analyze possible factors that affect delays in the departure or arrival of flights.

## Dataset Overview

The dataset contains observations of US domestic flights in 2013 and consists of the following fields:

- **Year**: The year of the flight (all records are from 2013)
- **Month**: The month of the flight
- **DayofMonth**: The day of the month on which the flight departed
- **DayOfWeek**: The day of the week on which the flight departed (from 1 (Monday) to 7 (Sunday))
- **Carrier**: The two-letter abbreviation for the airline
- **OriginAirportID**: A unique numeric identifier for the departure airport
- **OriginAirportName**: The full name of the departure airport
- **OriginCity**: The departure airport city
- **OriginState**: The departure airport state
- **DestAirportID**: A unique numeric identifier for the destination airport
- **DestAirportName**: The full name of the destination airport
- **DestCity**: The destination airport city
- **DestState**: The destination airport state
- **CRSDepTime**: The scheduled departure time
- **DepDelay**: The number of minutes departure was delayed (flights that left ahead of schedule have a negative value)
- **DelDelay15**: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")
- **CRSArrTime**: The scheduled arrival time
- **ArrDelay**: The number of minutes arrival was delayed (flights that arrived ahead of schedule have a negative value)
- **ArrDelay15**: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")
- **Cancelled**: A binary indicator that the flight was cancelled

## Project Aim

The aim of this project is to explore the flight data to analyze possible factors that affect delays in the departure or arrival of a flight.

# Excel : Aero Analytics : Navigating the Complexities of Airline and Airport Operations
![image](https://github.com/keerthan-pu/-Aero-Analytics-Navigating-the-Complexities-of-Airline-and-Airport-Operations/assets/114256472/35f66da6-a5cc-4735-94d6-01f41b50b8eb)

# Objective

The primary objective of this case study, titled "Sky Analytics: Navigating the Complexities of Airline and Airport Operations," is to deeply analyze and interpret the extensive datasets encompassing flights, airlines, and airports - namely "flights.csv", "airlines.csv", and "airports.csv". The analysis aims to uncover critical insights into flight operations, delay patterns, airline efficiency, and airport traffic dynamics. By exploring these datasets, the study seeks to identify key factors influencing operational efficiency, understand the intricacies of flight scheduling and delays, and evaluate the performance metrics of airlines and airports. The ultimate goal is to provide strategic recommendations to enhance operational effectiveness, improve customer experiences in air travel, and contribute to the overall advancement of the aviation industry's standards and practices.

# **Data Source**

1. **Flights Dataset**
[flights.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/ae2ac182-d6b6-4411-ad7e-3be1d7bc2a33/flights.csv)
This dataset contains detailed flight information, including timings, delays, and other flight-specific data.
- **YEAR, MONTH, DAY, DAY_OF_WEEK**: Date and day information for the flight.
- **AIRLINE**: Airline identifier.
- **FLIGHT_NUMBER**: Flight number.
- **TAIL_NUMBER**: Aircraft tail number.
- **ORIGIN_AIRPORT, DESTINATION_AIRPORT**: Airport codes for origin and destination.
- **SCHEDULED_DEPARTURE, DEPARTURE_TIME**: Scheduled and actual departure times.
- **DEPARTURE_DELAY**: Delay in departure (minutes).
- **TAXI_OUT**: The time duration between departure from the gate and wheels off.
- **WHEELS_OFF, WHEELS_ON**: Time when wheels were off/on the ground.
- **SCHEDULED_TIME**: Scheduled duration of the flight.
- **ELAPSED_TIME**: Actual time taken for the flight.
- **AIR_TIME**: Time in the air.
- **DISTANCE**: Distance covered by the flight.
- **TAXI_IN**: The time duration from wheels on to arrival at the gate.
- **SCHEDULED_ARRIVAL, ARRIVAL_TIME**: Scheduled and actual arrival times.
- **ARRIVAL_DELAY**: Delay in arrival (minutes).
- **DIVERTED, CANCELLED**: Indicators for diverted or cancelled flights.
- **CANCELLATION_REASON**: Reason for cancellation (if any).
- **AIR_SYSTEM_DELAY, SECURITY_DELAY, AIRLINE_DELAY, LATE_AIRCRAFT_DELAY, WEATHER_DELAY**: Different types of delays (minutes).


2. **Airlines Dataset**
[airlines.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/3632c550-cdbb-440f-a32b-90dbe4767865/airlines.csv)
This dataset provides information about various airlines.
- **IATA_CODE**: Unique airline code.
- **AIRLINE**: Full name of the airline.

3. **Airports Dataset**
[airports.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/1c354ebb-8057-4cf1-8d36-8a94c529bcd1/airports.csv)
This dataset contains information about various airports.
- **IATA_CODE**: Unique airport code.
- **AIRPORT**: Full name of the airport.
- **CITY**: City where the airport is located.
- **STATE**: State where the airport is located.
- **COUNTRY**: Country where the airport is located.
- **LATITUDE, LONGITUDE**: Geographic coordinates of the airport.

#Dashboards outcome
1.Airlines delay, cancellation and other metrics.
<img width="715" alt="Screenshot 2024-05-28 204552" src="https://github.com/keerthan-pu/-Aero-Analytics-Navigating-the-Complexities-of-Airline-and-Airport-Operations/assets/114256472/b3d67fb9-67ab-4916-ab27-999e25bf39e6">
2.Airport traffic and analysis.
<img width="747" alt="Screenshot 2024-05-28 204529" src="https://github.com/keerthan-pu/-Aero-Analytics-Navigating-the-Complexities-of-Airline-and-Airport-Operations/assets/114256472/51f76a0b-13f6-4640-b227-42484b10cec1">
3.Time series analysis.
<img width="722" alt="Screenshot 2024-05-28 204412" src="https://github.com/keerthan-pu/-Aero-Analytics-Navigating-the-Complexities-of-Airline-and-Airport-Operations/assets/114256472/a9aafa16-d120-48d8-b968-1b5e0446afc3">

#Tasks performed
1. **Flight Operations Overview**:
    - Incorporate a summary view showing total number of flights, average delays, and flight cancellations. Include filters to view data by specific airlines or airports.
2. **Airline Performance Analysis**:
    - Visualize performance metrics for each airline, such as average delay time, cancellation rates, and frequency of flights. Use charts like bar graphs or line charts for comparison.
3. **Airport Traffic Visualization**:
    - Display data on the busiest airports in terms of incoming and outgoing flights. Include interactive elements like a map for geographical representation and pie charts for traffic distribution.
4. **Delay Cause Breakdown**:
    - Provide a detailed analysis of the reasons for flight delays (weather, security, airline delays, etc.). Use a combination of pivot tables and stacked bar charts for this analysis.
5. **Time-based Flight Trends**:
    - Show how flight patterns and delay trends vary over different times of the day and across months. Implement a timeline or slider feature to allow users to explore temporal changes.
6. **User Interaction Features**:
    - Add slicers, dropdown menus, and timeline controls for users to interactively filter and explore the data across various dimensions like time periods, airlines, and airport codes.
7. **Dashboard Aesthetics and Usability**:
    - Ensure the dashboard is not only informative but also visually appealing and easy to navigate. Maintain a consistent color scheme and clear labels.

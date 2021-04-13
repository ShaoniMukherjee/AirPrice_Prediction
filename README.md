
# Flight-Price-Prediction

- Created a Machine Learning model to predict the prices of Flight in India to help user book the tickets in advance and have an estimate over the price.
- Engineered feature such as "Route", "Date of booking," "Time Duration" of flight. The features where quantified to fed to the ML Model.
- Till now the best model is Random Forest which helped to attain a score of 95% in training set and 83% in the testing set. 
- The model was fed 26 features which included ['Airline', 'Source', 'Destination', 'Arrival_Time', 'day',
       'month', 'Dep_hour', 'Dep_min', 'Stop', 'hours', 'minutes',
       'Airline_Air India', 'Airline_GoAir', 'Airline_IndiGo',
       'Airline_Jet Airways', 'Airline_Jet Airways Business',
       'Airline_Multiple carriers',
       'Airline_Multiple carriers Premium economy', 'Airline_SpiceJet',
        'Source_Chennai', 'Source_Delhi', 'Source_Kolkata', 'Source_Mumbai',
       'Destination_Cochin', 'Destination_Delhi', 'Destination_Hyderabad',
       'Destination_Kolkata', 'Destination_New Delhi']
       

- In the process to biuld a client facing app using flask frame work and Heroku.

# Codes and Resources used

- Python Version: 3.8.5
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, flask, json, pickle
- For Web Framework Requirements: pip install -r requirements.txt
- Dataset: https://www.machinehack.com/hackathons/predict_the_flight_ticket_price_hackathon/data

# Problem Statement

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. Huh! Here we take on the challenge! As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities.     Size of training set: 10683 records Size of test set: 2671 records FEATURES: Airline: The name of the airline. Date_of_Journey: The date of the journey Source: The source from which the service begins. Destination: The destination where the service ends. Route: The route taken by the flight to reach the destination. Dep_Time: The time when the journey starts from the source. Arrival_Time: Time of arrival at the destination. Duration: Total duration of the flight. Total_Stops: Total stops between the source and destination. Additional_Info: Additional information about the flight Price: The price of the ticket

Size of test set: 2671 records
FEATURES: Airline: The name of the airline.
Date_of_Journey: The date of the journey
Source: The source from which the service begins.
Destination: The destination where the service ends.
Route: The route taken by the flight to reach the destination.
Dep_Time: The time when the journey starts from the source.
Arrival_Time: Time of arrival at the destination.
Duration: Total duration of the flight.
Total_Stops: Total stops between the source and destination.
Additional_Info: Additional information about the flight
Price: The price of the ticket

#EDA


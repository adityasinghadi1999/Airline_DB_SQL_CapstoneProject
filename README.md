# Airline_DB_SQL_CapstoneProject
Write your answers(query) in the answer and submit it. To write the answer in the assignment, please follow the below example in yellow

Example:

Questions: Extract all the columns of the flights table

Answer: SELECT * FROM flights

 

Attempt the following Questions-

 

 

Represent the “book_date” column in “yyyy-mmm-dd” format using Bookings table
Expected output: book_ref, book_date (in “yyyy-mmm-dd” format) , total amount

Answer:

Get the following columns in the exact same sequence.
Expected columns in the output: ticket_no, boarding_no, seat_number, passenger_id, passenger_name.

Answer:

Write a query to find the seat number which is least allocated among all the seats?
 Answer:

In the database, identify the month wise highest paying passenger name and passenger id.
Expected output: Month_name(“mmm-yy” format), passenger_id, passenger_name and total amount

 Answer:

In the database, identify the month wise least paying passenger name and passenger id?
Expected output: Month_name(“mmm-yy” format), passenger_id, passenger_name and total amount

 Answer:

Identify the travel details of the flights having return journey (more than 1 flight).
Expected Output: Passenger_id, passenger_name, ticket_number and flight count.

 Answer:

How many tickets are there without boarding passes?
Expected Output: just one number is required.

 Answer:

Identify details of the longest flight (using flights table)?
Expected Output: Flight number, departure airport, arrival airport, aircraft code and durations.

Answer:

Identify details of all the morning flights (morning means between 6AM to 11 AM, using flights table)?
Expected output: flight_id, flight_number, scheduled_departure, scheduled_arrival and timings.

 Answer:

Identify the earliest morning flight available from every airport.Early morning: 2:00 am to 6:00 am.
Expected output: flight_id, flight_number, scheduled_departure, scheduled_arrival, departure airport and timings.

Answer:

Questions: Find list of airport codes in Europe/Moscow timezone
 Expected Output:  Airport_code.

Answer:

Write a query to get the count of seats in various fare condition for every aircraft code?
 Expected Outputs: Aircraft_code, fare_conditions ,seat count

Answer:

How many aircrafts codes have at least one Business class seats?
 Expected Output : Count of aircraft codes

Answer:

Find out the name of the airport having maximum number of departure flight
 Expected Output : Airport_name

Answer:

Find out the name of the airport having least number of scheduled departure flights
 Expected Output : Airport_name

 

Answer:

How many flights from ‘DME’ airport don’t have actual departure?
 Expected Output : Flight Count

Answer:

Identify flight ids having range between 3000 to 6000
 Expected Output : Flight_Number , aircraft_code, ranges

Answer:

Write a query to get the count of flights flying between URS and KUF?
 Expected Output : Flight_count

Answer:

Write a query to get the count of flights flying from either from NOZ or KRR?
 Expected Output : Flight count

Answer:

Write a query to get the count of flights flying from KZN,DME,NBC,NJC,GDX,SGC,VKO,ROV
Expected Output : Departure airport ,count of flights flying from these   airports.

Answer:

Write a query to extract flight details having range between 3000 and 6000 and flying from DME
Expected Output :Flight_no,aircraft_code,range,departure_airport

Answer:

Find the list of flight ids which are using aircrafts from “Airbus” company and got cancelled or delayed
 Expected Output : Flight_id,aircraft_model

Answer:

Find the list of flight ids which are using aircrafts from “Boeing” company and got cancelled or delayed
Expected Output : Flight_id,aircraft_model

Answer:

Which airport(name) has most cancelled flights (arriving)?
Expected Output : Airport_name.

Answer:

Identify flight ids which are using “Airbus aircrafts”
Expected Output : Flight_id,aircraft_model

Answer:

Identify date-wise last flight id flying from every airport?
Expected Output: Flight_id,flight_number,schedule_departure,departure_airport

Answer:

Identify list of customers who will get the refund due to cancellation of the flights and how much amount they will get?
Expected Output : Passenger_name,total_refund.

Answer:

Identify date wise first cancelled flight id flying for every airport?
Expected Output : Flight_id,flight_number,schedule_departure,departure_airport

Answer:

Identify list of Airbus flight ids which got cancelled.
Expected Output : Flight_id

Answer:

Identify list of flight ids having highest range.
 Expected Output : Flight_id, range

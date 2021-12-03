# Airline-Crew-Scheduling
Our goal of this project is to optimize the airline scheduling and crew scheduling. Also, we are focusing on merging them together to see if we are able to get to our final solution.

Flight Scheduling:
The Flight Scheduling helps to get a feasible plan on where to fly/ which city to fly and on what time. So, it is important to generate a plan that covers all our scheduled flights and also helps in reducing the overall cost.

We have done the airline scheduling part by:
•	Defining our objective of minimizing the round-trip cost.
•	Defining our constraints:
1.	At least one aircraft available for the flight
2.	The total time should not be more.

Crew Scheduling:
Crew scheduling is a process of assigning crew members to the scheduled flights. Flight crew planning is an import process as we have to focus on many things like seniority, and interpersonal relationship. 
And for the crew scheduling part:
•	Defining our objective of assigning the minimum crew time.
•	Not allowing the overlapping schedules for pilot and first officer.

Here are the libraries and tools we have used to find our optimal solution:
•	Programming Language – Python – Google Colab
•	Libraries- Pandas, NumPy, CVXPY

# Problem Definition
Problem Statement
There are various problems delt with in the airline scheduling, starting from ground crew scheduling to aircraft scheduling. The main aim still remains same to minimize expenses involved.
Among all the different optimization problems solved. We have mainly focused on scheduling cabin crew and choosing aircraft schedule while optimizing cost.

We have divided the approach into 2 main parts:
-	Flight Scheduling
-	Cabin Crew Scheduling

Objective
To determine –
•	Minimizing the overall Cost, covering all destinations in a given time span.

•	Assigning the paired crew to the scheduled flights.

Our main goal is to determine the initial allocation of flights to destinations and crew pairs to flights, while minimising the number of planes used and travel time. 


# Model-based_development



# Content
- ### [Task 1: Model using a Place/Transition Petri net for online purchasing train tickets system]()

# Task 1: Model using a Place/Transition Petri net for online purchasing train tickets system 

This model presents a Place/Transition Petri net model representing the online train ticket purchase process. The model captures key steps of a typical user journey when purchasing a train ticket through an online platform.

### It includes:

Synchronization: at the point of searching for a trip, requiring destination, date/time, and travel class to be selected.

Parallelism: during the final booking step, where the system both books the trip and generates the ticket simultaneously.

### Model Overview

Places (P):

P1 – Start (decision to buy a ticket)

P2 – Destination is selected

P3 – Date and Time are selected

P4 – Travel class is selected

P5 – Trip is found

P6 – Passenger’s Data is completed

P7 – Payment is accepted

P8 – Trip is booked

P9 – Ticket is generated

Transitions (T):

T1 – Select trip details

T2 – Find a trip (synchronization: requires P2, P3, and P4)

T3 – Fill in Passenger’s Data

T4 – Upload ID

T5 – Select payment method

T6 – Make Payment

T7 – Finish a booking (parallelism: leads to both P8 and P9)

### Features

Synchronization (T2): Ensures the user has entered all required search parameters (destination, date/time, travel class) before proceeding.

Parallelism (T7): Once payment is completed, both ticket generation and trip booking occur simultaneously.




# Task 2: Model using a Place/Transition Petri net for online purchasing train tickets system 

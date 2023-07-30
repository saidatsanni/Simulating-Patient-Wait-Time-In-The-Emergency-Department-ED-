# Real Time Simulation Modeling of Waiting Times in the Emergency Department
This project focuses on the real-time simulation of the emergency department on a typical day using statistical models and distributions. This project provides insights into the process, waiting times, bottlenecks, proposed modifications, and recommendations.

**Goal:** 

Assess the process flow at the emergency department to determine waiting times and the process with the highest influence (bottleneck).

This study addresses the following questions:

* How long are the waiting times for a typical day at Emergency Department?
* Do waiting times vary based on arrival type (means of patient’s arrival)?
* Check-in time vs Room assignment: which process step contributes more to the waiting times?
* Are the resources utilized effectively and what are the possible areas of improvement?


**Data**

Emergency department data for 24-hours with 130 patient arrivals using four different arrival means - Car, Public Transportation, County Services, and Other unspecified means.
Variables include: Patient No, Arrival Time, Means of Arrival, Check-in and Triage Time, Emergency Room Number, Time Spent in the Emergency Room, and Departure Time.

**Software**

ARENA Simulation software was used in the simulation, visulaization, and animation of the process flow.

**Modeling**

The process flow is simulated and modeled using statistical distributions such as:
* Arrival rates are simulated using Non-stationary Poisson process with a specific rate function.
* Arrival Distribution and Emergency Room Availability are simulated based on schedule in the dataset.
* Service time of the Receptionist/Triage Nurse is simulated using Beta distribution.

Model verification is conducted, proposed modifications are made and assessed. See the final project presentation here: [Waiting in the ed department on A Typical Day(Simulation Modeling of Waiting Times in the ED.pdf)

**Conclusion**

* The overall patients avg. waiting time is 28.31 minutes and a max. of 334.90 minutes (an extreme case).
* The most wait is at the check-in and triage process.
* Waiting times vary based on patients means of arrival.
** Unspecified forms of arrivals are the highest, and then car arrivals
** Public transport or taxi are the least.


* 

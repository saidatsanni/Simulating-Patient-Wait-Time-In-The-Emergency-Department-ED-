# Real Time Simulation Modeling of Waiting Times in the Emergency Department
This project focuses on the real-time simulation of the emergency department on a typical day using statistical models and distributions. This project provides insights into the process, waiting times, bottlenecks, and proposed modifications.

**Goal:** 

Assess the process flow at the emergency department to determine waiting times and the process with the highest influence (bottleneck).

This study addresses the following questions:

* How long are the waiting times for a typical day at Emergency Department?
* Do waiting times vary based on arrival type (means of patient’s arrival)?
* Check-in time vs Room assignment: which process step contributes more to the waiting times?
* Are the resources utilized effectively and what are the possible areas of improvement?



Investigate and fit nonlinear relationships using the Generalized Additive Model and Basis spline with different smoothing parameters, number of knots, degrees of polynomials, and degrees of freedom. 

**Data**

Emergency department data for 24-hours with 130 patient arrivals using four different arrival means - Car, Public Transportation, County Services, and Other unspecified means.
Variables include: Patient No, Arrival Time, Means of Arrival, Check-in and Triage Time, Emergency Room Number, Time Spent in the Emergency Room, and Departure Time.


**Statistical Techniques**

We consider statistical techniques and models such as:
* Generalized Additive Model for Univariate Data
*  Generalized Additive Model for Multivariate Data
*  B-spline with different numbers of knots, degrees of polynomials, degrees of freedom, and truncated power basis function.


**Project**

R and R Markdown were used for the coding and the creation of the project which can be found here: [Data Modeling with Splines and GAM](https://rpubs.com/Saidat/B-Splines-and-GAM)

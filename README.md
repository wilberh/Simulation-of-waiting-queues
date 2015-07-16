#Simulation of waiting queues at an airline check-in counter

-February 21st, 2015

-NEW JERSEY INSTITUTE OF TECHNOLOGY (NJIT) GRADUATE COMPUTER SCIENCE COURSE:  
CIS-610-Data Structures and Algorithms


-NJIT GRADUATE COMPUTER SCIENCE COURSE DESCRIPTION: 
Intensive study of the fundamentals of data structures and algorithms. Presents the definitions, representations, processing algorithms for data structures, general design and analysis techniques for algorithms. Covers a broad variety of data structures, algorithms and their applications including linked lists, various tree organizations, hash tables, strings, storage allocation, algorithms for searching and sorting, and a selected collection of other algorithms. Programs are assigned to give students experience in algorithms, data structure design and implementation.

-BOOK:  
Algorithm Design, by Machel T. Goodrich and Roberto Tamassia


-PROJECT:  
CIS-610-SPRING 2015-PROGRAMMING ASSIGNMENT 1


This is a simulation of waiting queues at an airline check-in counter, organized as follows, 
-There are two types of passengers: first clas, and coach.  
-There are two service stations for first class, and three for coach.  
-There is a single queue for each type of passenger (first class, coach).  
-Passenger arrival times are random and are generatored by a random number generator.  
-Average arrival rates for passengers are R1 for first class and R2 for coach.  
These are decided at run-time by prompting the user.  
-Service time is random and varies uniformly between 1 and S1 for first class, 
and between 1 and S2 for coach.  
Parameters S1 and S2 are also determined at run-time, by prompting the user.  
-Whenever a service station is available and the corresponding queue is not empty, 
we pick the passenger at the front of the queue and place her/him on the service station.  
-Whenever a first class service station is available and the first class queue is empty, 
the service station may service a passenger from coach.  
-The duration of the experiment, in minutes, is decided by the user at run time.  
-Statistics generated by the simulation include: average service time, maximum service time, 
number served in each class, maximum queue length for each type of passenger.  

## WHAT'S INCLUDED
within the download you'll find the following files:
- Program.cs

## BUGS AND FEATURE REQUESTS
Have a bug or a feature request? Please open an [issue](https://github.com/wilberh/Simulation-of-waiting-queues/issues/new).

## DOCUMENTATION
This Simulation-of-waiting-queues documentation included in this repo in the root directory was build with C# in Microsoft Visual Studio 2010.  

## RUNNING DOCUMENTATION LOCALLY
- 1. If necessary, install Microsoft Visual Studio
- 2. From the root /Simulation-of-waiting-queues directory, compile and run the Program.cs file 
- 3. The program will prompt the user for the average arrival rates of the passengers, and service time for first class and coach service desk.  After that the program will generate the average service time, maximum service time, number served in each class, maximum queue length for each type of passenger.

## CREATOR
**Wilber Hernandez**
- github.com/wilberh
- twitter.com/wilberh

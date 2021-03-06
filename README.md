CarPoolingSystem
================

A dynamic car pooling system to help college students (currently from DTU) share vehicles to save cost and time.




Before Using the system or trying to run the source codes : 
->Change the IP address in the android code->Vehicle Pooling System->src->com->Visdrotech->VehiclePoolingSystem->Utils->Common_Utilities->BaseUrl 
->Add the address of the php folder to this address
->U'll require a server to run the application 
->Add the vps.sql database to the phpmyadmin.
->After all the above steps compile the project to get the new apk file and run the application.







Introduction


Purpose
The purpose of this document is to present a detailed description of the Vehicle Pooling System. It will explain the purpose and features of the system, the interfaces of the system, what the system will do, the constraints under which it must operate and how the system will react to the external stimuli. This document is intended for both the stakeholders and the developers of the system. The document is also crucial for the maintainability of the software.


Scope of Project
This software system will be a Vehicle Pooling System for a college student who travels to University by road. This system will be designed to minimize the cost of travelling to University for classes on a daily basis by providing tools to assist in automating the car pooling process, which would otherwise have to be performed manually. By maximizing the traveler’s comfort and minimizing the cost, the system will meet the traveler’s needs while remaining easy to understand and use.
More specifically, this system is designed to allow a vehicle owner to manage and communicate with a group of interested travelers to share the vehicle on daily basis. The software will facilitate communication between vehicle owners and travelers, via Android Based Smart Phone Application. The back-end services will be performed via private server (or a localhost) .
Do’s:
1. Issue of login ids to the students. User Id will be the University Registration number and the password will be set by the students which may be changed by the student as and when (s)he requires to.
2. Create a profile for users after they have registered.
3. Maintain details of daily travelers, i.e. the vehicle owners and the travelers.
4. Maintain the routing details of the commuters on the daily basis.
5. Flash an error message on any invalid use of the system, making the system user friendly.
6. Make a combination such that every student travels to the university with minimum cost and maximum comfort.
7. Take entries at a predefined time every day (preferably), so as to make travelling arrangements one day before the travel.
8. Calculate fare share of each commuter.
9. Show the details of commuter along with the details of their companion, if any.
10. Allow the user to update their profile whenever needed.
Dont’s:
1. Travelling arrangements cannot be made dynamically.
3
2. Routes cannot be defined by the user. Fare calculations will be done on the basis of commonly used routes. It is the vehicle owner’s responsibility to follow the shortest path.
3. Traveler cannot choose the vehicle owner nor can (s)he deny being picked up through the system.
Benefits:
1. Easy and convenient travel.
2. Reduction in the cost of travel.
3. Reduction in the number of vehicles on road as well as in the campus premises thus reducing the pollution level.
4. Increased interaction amongst students.




Definitions, Acronyms, and Abbreviations:
 VPS: Vehicle Pooling System
 SRS: Software Requirement Specification
 DEO: Data Entry Operator
 Php (): It is used to create dynamic web content and interact with SQL.
 SQL (Structured Query Language): It is used to interact with the databases on the web server.
 HTTP (Hyper Text Transfer Protocol): It is a transaction oriented client/ server protocol between a web browser and a web server.




Glossary
Term							Definition								
System User		The person who is using the system in any way.				
Administrator  		The user who is having all the authorities and rights of the system.
Vehicle Owner		The traveler who owns a vehicle, prefers to travel by his own vehicle and is willing to share with other travelers.
Traveler		Person who does not prefer bringing his own vehicle or does not have his own vehicle and is willing to share with other travelers.
Database		Collection of all the information monitored by this system.
Commuter		Person who is either a Vehicle Owner or Traveler.
Member			A user registered with the Vehicle Pooling System.
Stakeholder		A person that is directly associated with the system, i.e. either uses it or develops it. Stakeholder involves the developers, the travelers and the University for which the system is developed.
SRS			A document that completely describes all the functions of a proposed system and the constraints under which it must operate.
User			Any person using the system who is not a developer.
Developer		The person who is into the technical development of the system.





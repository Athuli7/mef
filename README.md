# mef

##Deploy

> git clone https://github.com/Athuli7/mef

> npm install

> node release.js

##Mobile Entity Framework
A framework for mobile entities such as persons, assets and employees.

###Purpose
Track, Ping and recieve inputs from Mobile Entities

###Format
Trackers form the base of the system. Each tracker is connected to a network, of which the Server is part. Each tracker uses a Last Mile Delivery system to interact with a Mobile Entity. The Tracker is essentially a distributed proxy for the Server and is responsible for delivering the pings, identifying inputs and reporting presence to the server.
The design is meant to accomodate all configurations. But whereever such accomodations haven't been taken into consideration, the design is aligned towards deployment in a Hospital.

###Hospital (Test Case)
Last Mile Delivery Tech : BLE
Tracker Network         : LAN

Entities :-
- Nurses
- Doctors
- Assets
- Patients

Trackers :-
- Rooms
- Lifts
- Stairs

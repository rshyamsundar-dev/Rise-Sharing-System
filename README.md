📘 Overview

The Ride Sharing System simulates a basic platform that connects drivers and riders, manages available rides, and tracks ride details such as distance, cost, and driver/rider information.
The project demonstrates object-oriented programming (OOP) principles such as inheritance, polymorphism, encapsulation, and abstraction, implemented in C++ and Smalltalk.

⚙️ How the Program Works

Drivers can create and offer rides, specifying details like pickup point, destination, and fare.

Riders can request rides based on their location and preferences.

The system matches riders with available drivers and records completed rides.

Classes include Driver, Rider, Ride, and RideManager.

Driver and Rider inherit from a base User class.

RideManager handles creation, assignment, and completion of rides.

The program demonstrates data encapsulation through private attributes and public accessors, while polymorphism allows handling different ride types (e.g., StandardRide, LuxuryRide) using base-class pointers.

🧠 Implementation Details
C++ Version

Compile the program using any standard C++ compiler (e.g., g++):

g++ -o rideshare main.cpp driver.cpp rider.cpp ride.cpp manager.cpp
./rideshare


Key files:

main.cpp – Entry point

driver.cpp / rider.cpp – Class implementations

ride.cpp – Ride details and logic

manager.cpp – Manages ride allocation and records

Smalltalk Version

Load the .st files into a Smalltalk IDE (e.g., Pharo, Squeak).

Execute the main class (e.g., RideManager startDemo) from the workspace to run sample interactions.

The Smalltalk version uses pure object messaging, where every operation is performed through object communication.

🧩 Features

Object-oriented design across two languages

Dynamic ride assignment and record tracking

Clear class hierarchy with polymorphic behavior

Simple, modular structure for easy extension

🚀 Future Improvements

Add user authentication

Integrate a real-time location simulation

Store ride data in a database

Develop a simple graphical or web interface

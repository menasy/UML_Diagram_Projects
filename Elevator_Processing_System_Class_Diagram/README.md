# Elevator Processing System Class Diagram

## Problem Statement

Design a class diagram based on the following problem statement.

Try to use the principles of Object-Oriented Programming (Encapsulation, Inheritance, Polymorphism, Abstraction) and relationships between classes.

Kodluyoruz Insurance Company wants to construct a 12-story office building and equip it with the latest elevator technology. The company wants you to create a software simulator that models the operations of the building's elevators to see if they will meet the traffic flow needs within the building.

The building will have five elevators, each capable of serving all 12 floors of the building. Each elevator will have a capacity of approximately six adult passengers. The elevators are designed to be energy efficient, so they only move when necessary. Each elevator has its own door, floor indicator light, and control panel. The control panel includes target buttons, door open and close buttons, and an emergency signal button.

Each floor in the building has a door for each of the five elevator shafts, and each door has an arrival bell. The arrival bell indicates when an elevator has arrived at a floor. A signal light located above each door indicates the arrival of the elevator and the direction the elevator is moving. Each floor also has three sets of elevator call buttons.

A person calls an elevator by pressing the appropriate call button (up or down). A programmer assigns one of the five elevators to respond to the call and go to the floor where the call was made. After entering the elevator, a passenger typically presses one or more target buttons. As the elevator moves from floor to floor, an indicator light inside the elevator informs passengers of the elevator's position. An elevator's arrival at a floor is indicated by the illumination of the signal light above the exterior elevator door and the ringing of the floor bell. When an elevator stops at a floor, both sets of doors automatically open for a predetermined period, allowing passengers to enter and exit the elevator.

The simulator uses a "clock" to simulate real-time passage and timestamp and log the events occurring in the simulation. A random number generator is used by the simulator to create passengers and determine the departure and arrival floors for each passenger.

## Class Diagram

![Elevator Processing System Class Diagram](https://github.com/MeNasy/UML_Diagram_Projects/blob/main/Elevator_Processing_System_Class_Diagram/Elevator_Processing_System_Class_Diagram.png)

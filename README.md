# vehicle-rental-multilevel-inheritance-java

This project demonstrates **Multilevel Inheritance in Java** using a vehicle rental company example.

## Problem Statement
A rental company rents vehicles.

1. Create a base class **Vehicle**
   * Variables: `brand`, `modelYear`
   * Method: `start()`

2. Create class **Car**
   * Variable: `numberOfDoors`
   * Method: `drive()`

3. Create class **ElectricCar**
   * Variable: `batteryCapacity`
   * Method: `charge()`

## Concepts Used
* Multilevel Inheritance
* Constructors
* Java OOP Principles
* Object creation

## Program Structure
Vehicle
↓
Car
↓
ElectricCar

## Example Output
Brand: Tesla
Model Year: 2024
Number of Doors: 4
Battery Capacity: 75 kWh
Vehicle is starting...
Car is driving...
Battery charged to 80%

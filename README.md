Mini Hotel Recetion System-Java

Objective of the Project
This Java project is a console-based Hotel Management System that handles:

Booking rooms (Single / Double rooms, Luxury / Deluxe)

Checking room availability

Showing room features

Calculating bills (including room charges + food charges)

Deallocating (checkout) rooms

This simulates basic hotel operations a receptionist would handle.

Class Name	   Responsibility
Food	        Stores food item details ordered by a customer (item number, quantity, price).
Singleroom	  Represents a single room with customer's name, contact, gender, and food orders.
Doubleroom	  Inherits from Singleroom, adds details for a second customer (double room has 2 people).
NotAvailable	Custom Exception thrown when a user tries to book an already-occupied room.
Holder	      Holds all room arrays (Luxury Double Rooms, Deluxe Double Rooms, etc.)
Hotel        	Main driver class containing methods to book, check availability, show features, bill, and deallocate rooms.

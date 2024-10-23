# Indigo Airlines - Flight Booking System

Console Project

Welcome to the Indigo Airlines Flight Booking System! This console-based Java application allows users to browse available flights, book flights, and generate printable tickets. The system ensures a seamless booking experience and provides a user-friendly menu for managing bookings.

## Features:

- **Flight Availability**: Browse a list of available flights with details such as origin, destination, date, and ticket price.
  
- **Flight Booking**: Users can select a flight to book by entering the flight ID. The booking is recorded with details of the number of seats and the total fare.
  
- **Booking Details**: View the booking summary after making a reservation.
  
- **Ticket Printing**: Generate and save a ticket to a text file (`Ticket.txt`), which contains details of the flight, number of seats, and the total fare.
  
- **Simple Menu Navigation**: A guided, text-based interface makes the system easy to use.

## Project Structure:

The project is organized into several packages:

- **com.user**: Contains the main class `Test`, which handles user interaction and menu navigation.
- **com.model**: Contains data models, including `Booking` and `Flight`, that represent the core entities of the system.
- **com.service**: Contains the `BookingCounter` class, which manages flight bookings and ticket generation.

## How to Run:

1. Clone this repository to your local machine.
2. Open the project in your preferred Java IDE (e.g., Eclipse or IntelliJ IDEA).
3. Run the `Test` class located in the `com.user` package.
4. Follow the on-screen prompts to explore flight options, book flights, and generate tickets.

## Example Flights Available:

- **Flight 101**: Mumbai to Delhi on 2024-09-30 at 12:00 (₹5000)
- **Flight 102**: Pune to Bangalore on 2024-10-05 at 15:30 (₹4000)
- **Flight 103**: Hyderabad to Chennai on 2024-10-12 at 09:45 (₹3500)

## Ticket Generation:

Once a flight is booked, the ticket details will be saved in a text file (`Ticket.txt`). The ticket will include the following information:

- Booking ID
- Booking Time
- From and To locations
- Number of Seats
- Total Amount


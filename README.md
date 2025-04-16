# 🚆 Train Booking Application (Java, OOP)

A console-based train reservation system developed in Java using core Object-Oriented Programming (OOP) principles such as **Encapsulation**, **Abstraction**, **Inheritance**, and **Polymorphism**. This project simulates real-world train booking operations like viewing train details, booking tickets, canceling reservations, and checking seat availability.

---

## 🧩 Features

- 🔍 **View Available Trains**: Displays all available trains with train number, name, source, destination, and seat availability.
- 🎟️ **Book Tickets**: Allows users to book tickets by entering passenger details and selecting the desired train.
- ❌ **Cancel Tickets**: Enables users to cancel their existing reservations.
- 📄 **Print Ticket Details**: View booking status and passenger information.
- 🪑 **Seat Management**: Updates seat availability dynamically after bookings or cancellations.

---

## 🧠 Concepts Used

- **Encapsulation**: Each class manages its own data securely (e.g., `Train`, `Passenger`, `TicketManager`).
- **Abstraction**: Implementation details are hidden behind well-defined interfaces and methods.
- **Inheritance** *(if applied)*: Shared functionality reused across related classes (e.g., `User` → `Passenger`).
- **Polymorphism** *(optional use)*: Method overloading or overriding for flexible behavior.

---

## 🛠️ Tech Stack

- 👨‍💻 **Language**: Java  
- 🧱 **Architecture**: Object-Oriented Programming  
- 🖥️ **Interface**: Console-Based (Text UI)

---

## 📂 Project Structure

TrainBookingApp/ │ ├── Main.java # Entry point ├── Train.java # Train details and operations ├── Passenger.java # Passenger data class ├── TicketManager.java # Booking, canceling, and seat management logic └── Utils.java 



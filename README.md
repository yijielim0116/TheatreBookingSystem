# Theatre Booking System

A JavaFX app for running a single theatre's shows, performances, customers and seat bookings, built on a custom linked list instead of Java's collections.

Data Structures and Algorithms 1 · CA Exercise 1 · South East Technological University (SETU)

## Features

- **Shows:** title, running time, start and end dates, and ticket prices for the stalls, circle and balcony.
- **Performances:** a show on a given date, as a matinee or an evening performance (at most two a day).
- **Customers:** name, email address and phone number.
- **Bookings:** one or more seats for a performance, together or scattered. A seat can't be booked twice for the same performance.
- **Lists:** view the shows, performances, customers and bookings.
- **Save and load:** the whole system is saved to and loaded from an XML file.

## Project structure

| Path | Contents |
|---|---|
| `src/main/java/.../Node.java` | Node for the custom linked list |
| `src/main/java/.../Theatre*.java` | Models (show, performance, customer, booking) and their controllers |
| `src/main/java/.../Display*List.java` | List views |
| `src/main/resources/.../*.fxml` | The screens |
| `src/test/java/models/` | JUnit tests |
| `CA Exercise 1 2024.pdf` | The assignment brief |

## Running it

```bash
./mvnw javafx:run
```

## Tools

Java · JavaFX · FXML · JUnit 5 · Maven

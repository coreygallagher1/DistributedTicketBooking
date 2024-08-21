# Go Conference Ticket Booking Application

## Overview

This Go application simulates a ticket booking system for a conference. Users can enter their details, select the number of tickets they wish to purchase, and receive a confirmation via email (simulated with a print statement). The application demonstrates basic Go concepts, including struct usage, slices, input validation, concurrency with goroutines, and synchronization with `sync.WaitGroup`.

## Features

- **User Input:** Collects user information, including first name, last name, email, and the number of tickets.
- **Input Validation:** Ensures that the user's name, email, and ticket quantity are valid before processing the booking.
- **Concurrent Ticket Sending:** Simulates sending tickets to users via email using a goroutine.
- **Booking Management:** Keeps track of available tickets and displays the first names of all booked users.

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. **Run the Application:**
    ```bash
    go run main.go

## Dependencies
 
- **Go:**: This application requires Go to be installed on your machine.

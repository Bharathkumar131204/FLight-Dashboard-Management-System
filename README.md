# FLight-Dashboard-Management-System


This project implements a flight scheduling system using AVL trees to manage flight schedules efficiently. The system organizes flights into "buckets" based on their estimated time of arrival (ETA) and provides several functionalities:

## Features

- **Add a new flight**
- **Delete a flight**
- **Show Status**
- **Show Flight in Range**
  
## Data Structures

- **AVLBucket**: AVL tree node representing a bucket containing flights with ETAs within a specific hour.
- **AVLFlightSchedule**: AVL tree node representing an individual flight within a bucket.

## Usage

1. Compile the program using a C compiler.
2. Run the executable.
3. Follow the on-screen menu to interact with the flight scheduling system.

## File Structure

- `data.txt`: Contains initial flight data to load into the system at startup.
- `main.c`: Source code of the flight scheduling system.

The project demonstrates the efficient management of flight schedules using AVL trees to ensure balanced and quick operations.

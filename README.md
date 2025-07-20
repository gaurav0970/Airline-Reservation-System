# Airline Reservation System (ARS)

## Project Description
This C++ program implements an Airline Reservation System that allows users to:
- View flight schedules and details
- Make flight reservations
- View passenger lists
- Check seat status
- Generate bills for reservations

The system supports multiple airlines (Indigo, Air India, Go First, SpiceJet, Vistara) and routes (Pune to Mumbai, Delhi, Chennai).

## Features
- **Flight Management**:
  - View complete flight schedules with departure/arrival times and costs
  - Select from multiple airlines and destinations
- **Reservation System**:
  - Book multiple passengers in one transaction
  - Select seat numbers and meal preferences
  - Store passenger details (name, age, gender, contact)
- **Reporting**:
  - Generate passenger lists with reservation details
  - View seat availability status
  - Calculate total billing based on flight and destination
- **User-Friendly Interface**:
  - Menu-driven console interface
  - Error handling for invalid inputs

## Technical Details
- **Programming Language**: C++
- **Concepts Used**:
  - Object-Oriented Programming (Classes and Inheritance)
  - File Handling (Reading flight data from text file)
  - Exception Handling
  - Arrays for data storage
- **Data Storage**:
  - Flight data stored in `Flight_data.txt`
  - Passenger data stored in memory during runtime

## How to Use
1. Compile the program: `g++ ARS.cpp -o ars`
2. Run the executable: `./ars`
3. Follow the menu prompts to:
   - View flight schedules (Option 1)
   - Make reservations (Option 2)
   - View passenger lists (Option 3)
   - Check seat status (Option 4)
   - Exit the system (Option 5)

## File Structure
- `ARS.cpp`: Main program source code
- `Flight_data.txt`: Contains flight schedule data

## Requirements
- C++ compiler (g++ recommended)
- Standard C++ libraries

## Limitations
- Data is not persisted between program runs
- Limited to 100 seats per flight
- Supports only predefined routes and airlines

## Future Enhancements
- Add database support for persistent storage
- Implement flight cancellation functionality
- Add admin interface for flight management
- Support for more cities and airlines

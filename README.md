# Parking Management System

## Overview
The Parking Management System is designed to provide a streamlined and efficient approach to managing parking lots. It integrates advanced technologies such as license plate recognition, real-time parking availability tracking, and mobile application support to enhance the experience for both drivers and parking administrators.

## Features
- **License Plate Recognition (LPR) System**:
  - Captures and processes license plate data using OCR.
  - Differentiates between visitors and registered monthly clients.

- **Parking Management Software**:
  - Manages parking records and controls entry/exit barriers.
  - Tracks real-time availability of parking spaces.
  - Supports scalability and operates offline when needed.

- **User Interfaces**:
  - **Driver Interface**:
    - View available parking spaces.
    - Pay parking fees through various options (minutes, hours, days, or weeks).
    - Book parking spaces in advance.
  - **Administrator Interface**:
    - Monitor and manage parking lot status.
    - Override system controls during failures.

- **Mobile Application**:
  - Provides real-time notifications for expiring parking times.
  - Enables additional payments and bookings.

## Architecture
The system is composed of several interconnected modules:
1. **License Plate Recognition (LPR) System**:
   - Installed at entrances and exits to capture vehicle information.
2. **Parking Management Software**:
   - Handles database operations, payment processing, and LPR data.
3. **Barrier System**:
   - Ensures controlled access to parking lots.
4. **Mobile Application**:
   - Interfaces with drivers for payments, notifications, and bookings.
5. **Offline Functionality**:
   - Maintains operations using a local database, syncing with the online database upon reconnection.

## Use Cases
1. **For Drivers**:
   - Smooth entry and exit process.
   - Real-time updates on parking availability.
   - Notifications for expiring parking times.
2. **For Administrators**:
   - Real-time control over parking lot operations.
   - Manual override for system failures.
## Contributors
- **Yashrith Chittoor Hari Krishna**
- **Felipe Andrés Cordero Osorio**

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
- **Professor Salar Nasr Azadani** for guidance and support during development.

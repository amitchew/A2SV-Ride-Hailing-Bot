# A2SV Ride Hailing Telegram Bot

## Overview
This is the A2SV Ride Hailing Telegram Bot, developed using the aiogram library in Python. The bot provides ride booking services with features such as user authentication, profile management, ride booking, driver matching, rating and reviews, and history/receipts.

## Features

### 1. User Authentication
- Allow users to sign up and log in using their Telegram accounts.
- Users should provide a full name, phone number, and role (driver/passenger).
- Utilize the share phone number feature for receiving phone numbers.

### 2. Profile Management
- Enable users to edit their profiles with details such as name and contact information.

### 3. Ride Booking
- Implement a feature for users to request rides by providing their current location and destination (using a string).
- Provide estimated arrival times and fare estimates (generated randomly).

### 4. Driver Matching
- Send a ride alert to all drivers on the system.
- Notify users when a driver accepts their ride request.
- Notify the driver when a ride is canceled.

### 5. Rating and Reviews
- Allow users to rate and provide feedback on their ride experience.
- Provide a system for drivers to rate passengers.

### 6. History and Receipts
- Enable users to view their ride history.
- Provide digital receipts for completed rides.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/amitchew/A2SV-Ride-Hailing-Bot.git
cd A2SV-Ride-Hailing-Bot

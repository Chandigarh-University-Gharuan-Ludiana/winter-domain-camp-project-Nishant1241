[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/uELM4yXj)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17721110&assignment_repo_type=AssignmentRepo)
# Ride Sharing App

Welcome to the **Ride Sharing App**! This application connects riders and drivers seamlessly, enabling quick, safe, and affordable rides for everyone. Designed for convenience and reliability, our app ensures a smooth experience for both riders and drivers.

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### For Riders:
- **Quick Ride Booking**: Book a ride in seconds with a user-friendly interface.
- **Real-Time Tracking**: Track your driver on the map in real-time.
- **Flexible Payments**: Pay using credit cards, wallets, or cash.
- **Ride Rating**: Rate and review your ride experience.

### For Drivers:
- **Easy Ride Management**: Accept or decline ride requests instantly.
- **Earnings Dashboard**: Track daily, weekly, and monthly earnings.
- **Navigation Integration**: Use in-app navigation for optimized routes.
- **Safety Features**: Access emergency contacts and report issues.

---

## Tech Stack

- **Frontend**: React Native (for cross-platform compatibility)
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.IO for live updates
- **APIs**: Google Maps API for location and route management
- **Authentication**: JWT and OAuth2.0

---

## Installation

1. Clone the repository:
   ```bash
   git clone (https://github.com/Chandigarh-University-Gharuan-Ludiana/winter-domain-camp-project-Nishant1241)
   cd ride-sharing-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     DATABASE_URL=your_database_url
     JWT_SECRET=your_jwt_secret
     GOOGLE_MAPS_API_KEY=your_google_maps_api_key
     ```

4. Start the development server:
   ```bash
   npm start
   ```

---

## Usage

1. **For Riders**:
   - Sign up and verify your account.
   - Set your pickup and drop-off locations.
   - Select a ride type and confirm your booking.

2. **For Drivers**:
   - Sign up and verify your driver profile.
   - Go online to start receiving ride requests.
   - Accept rides and navigate to the rider's location.

---

## Screenshots

### Rider Interface:
- Booking a ride
- Real-time driver tracking

### Driver Interface:
- Ride requests
- Earnings dashboard

![Screenshot 2025-01-15 205020](https://github.com/user-attachments/assets/5eda824f-d348-4d81-9bbc-5fb9f9178e18)
![Screenshot 2025-01-15 205037](https://github.com/user-attachments/assets/163cf401-d084-4d79-bb83-e9c6c4728d2d)



---

## API Documentation

Detailed API documentation is available [here](link-to-your-api-docs). It includes:
- Authentication endpoints
- Ride management endpoints
- Payment processing
- Driver and rider management

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Just a readme update"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## License

This project is licensed under the [MIT License].

---

Happy Riding! 🚗


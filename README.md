# PBL25-3-FarmBot
# FarmBot Control Panel
# A React-based web application for controlling a FarmBot, an automated farming robot. This project provides a user-friendly interface to authenticate, connect to the FarmBot via MQTT, and send precise movement commands to manage agricultural tasks.
# Features

# User Authentication: Secure login with email and password to obtain a JWT token, stored in localStorage for session persistence.
# MQTT Connection: Real-time communication with the FarmBot using MQTT over WebSocket to send commands and receive status updates.
# Movement Control: Input X, Y, Z coordinates to move the FarmBot to specific locations with configurable speed.
# Real-Time Status: Displays connection status and the robot’s current position.
# Responsive UI: Built with React, Tailwind CSS, and React Router for a seamless experience across login and control panel pages.

# Tech Stack

# Frontend: React, Tailwind CSS, React Router
# State Management: React Context API
# API Communication: Axios for HTTP requests to the FarmBot API
# Real-Time Messaging: MQTT.js for WebSocket communication
# Dependencies: See package.json for full list


# Usage

# Login: Enter your FarmBot account email and password on the login page to authenticate and connect to the MQTT broker.
# Control Panel: After successful login, navigate to the control panel to input coordinates and send movement commands.
# Monitor Status: View real-time updates on the FarmBot’s position and connection status.
# Logout: Clear session data to log out.

# Project Structure

# src/components/: React components (ControlPanelHeader.jsx, MoveCommandForm.jsx, StatusMessage.jsx)
# src/context/: Context providers for authentication (AuthContext.jsx) and bot instance (BotContext.jsx)
# src/api/: API utilities (farmbotApi.js for HTTP requests, farmbotMqqt.js for MQTT communication)
# src/pages/: Page components (LoginPage.jsx, ControlPanelPage.jsx)

# Key Files

# LoginForm.jsx: Handles user authentication and MQTT connection setup.
# MoveCommandForm.jsx: Form for sending movement commands to the FarmBot.
# farmbotMqqt.js: Manages MQTT connection, subscriptions, and command execution.
# AuthContext.jsx: Provides authentication state and methods across the app.

# API
# The app interacts with the FarmBot API at https://my.farmbot.io/api. Ensure you have a valid FarmBot account for authentication.
# Contributing

# Fork the repository.
# Create a feature branch (git checkout -b feature/your-feature).
# Commit changes (git commit -m "Add your feature").
# Push to the branch (git push origin feature/your-feature).
# Open a pull request.

# Future Enhancements

# Support for advanced FarmBot commands (e.g., planting, watering).
# Real-time video feed integration.
# Improved error handling and command retries.


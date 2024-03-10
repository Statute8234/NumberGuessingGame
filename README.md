# NumberGuessingGame

The Java code is a simple number guessing game where players guess a random number between 1 and 10, with feedback on their guess, losing points if they fail, and ending with zero points.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 7/10](#Rating)

# About

The Java code is a simple number guessing game where the player has three chances to guess a random number between 1 and 10, with feedback provided after each guess. If the player fails within three attempts, they lose a point, and if they reach zero points, the game ends.
# Features

The Kivy application for managing user authentication and registration in the "GUUF IT Department App" is a robust project that features a multiplatform open-source Python framework for creating graphical user interfaces (GUIs). The app features multiple screens, each serving a specific purpose, such as the login screen, sign-up screen, password reset screen, and successful login screen. Users can log in using their credentials, sign up by providing their name, email, and password, and reset their password if needed.

The app likely uses email addresses for user identification and communication, and may send verification emails during registration or password reset processes. Password hashing is crucial for security, and the app likely hashes passwords before storing them in a database to prevent attackers from easily retrieving original passwords.

Device information can enhance the user experience by tailoring the app's behavior based on the user's device. For more advanced features, consider adding two-factor authentication (2FA), account recovery options, and user profile management.

# Imports

kivy.lang, kivymd.app, kivy.core.window, kivy.uix.screenmanager, kivy.properties, kivymd.uix.relativelayout, kivy.uix.boxlayout, kivymd.toast, platform, geopy.geocoders, datetime, email.message, pymongo, bcrypt, secrets, ssl, smtplib, string, re, random, sys

# Rating

The user authentication system uses the Kivy framework for cross-platform applications, providing a user-friendly interface and clear separation of concerns. It includes error handling and input validation for data integrity and security. However, some parts of the code could be optimized for readability and maintainability, and the app's functionality could be enhanced with two-factor authentication (2FA). Some commented-out sections of code may clutter the file and should be removed or properly documented for future use. More detailed comments and documentation could aid understanding and future development.
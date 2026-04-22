# Pawssenger

## Project Overview
Pawssenger is a comprehensive Android application designed to enhance the pet ownership experience. The app connects pet owners with various pet transportation services, providing them a seamless way to manage their pets travel from one area to another. This project is built per the requirements of our undergrad course CSE-250.

## Features
- Pet Transportation Service Finder: Discover local pet transport services.
- Profiles: Create and manage detailed profiles for yourself.
- Two types of roles: User (Pet-owner) and Transporter.
- Appointment Scheduling: Book appointments with service providers directly through the app.
- Notifications: Get updates and reminders for appointments and transportation.
- Supports Light and Dark theme

## Tech Stack
- **Language**: Kotlin
- **Framework**: Android SDK
- **Backend**: Firebase (Authentication, Database, Cloud Messaging)
- **Architecture**: MVVM

## User Interface

Pawssenger focuses on a clean, user-friendly interface with support for both light and dark themes.

### Authentication & Onboarding
Users can sign up and begin using the app through a simple onboarding flow.

<table>
<tr>
<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897351/login-page-dark_ppou3t.png" width="250"/><br>
Login Screen (Dark view)
</td>

<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897350/sign-up-page-light_yfebya.png" width="250"/><br>
Signup Screen (Light View)
</td>
</tr>
</table>

---

### Service Request
Make transportation request. (Unavailable for transportation role)

<table>
<tr>
<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897349/request-light_foqxcz.jpg" width="250"/><br>
Pet Request Form (Light)
</td>

<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897350/request-dark_uyfojx.jpg" width="250"/><br>
Pet Request Form (Dark)
</td>
</tr>
</table>

---

### Home Page
Schedule and manage transport appointments.

<table>
<tr>
<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897351/home-page-user-light_djcdkb.png" width="250"/><br>
Home Page (User View - Light)
</td>

<td align="center">
<img src="https://res.cloudinary.com/dr6pjobzl/image/upload/v1776897350/home-transport-dark_lyiee5.jpg" width="250"/><br>
Home Page (Transporter View - Dark)
</td>
</tr>
</table>

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/CharlieBrown110/Pawssenger.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Ensure you have the necessary Firebase configurations set up in your `google-services.json` file.
5. Run the app on an Android device or emulator.

## Contribution Guidelines
We welcome contributions to this project! To contribute:  
1. Fork the repository.  
2. Create a new branch for your feature or bugfix.  
3. Make your changes and commit them.  
4. Push your branch and submit a pull request.  
5. Ensure to provide a clear description of your changes.

For any issues or feature requests, please create an issue on GitHub.

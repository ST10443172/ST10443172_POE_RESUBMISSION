# ST10443172_POE_RESUBMISSION
 Hydration Haven
<img width="1280" alt="Screenshot 2024-07-22 at 16 04 07" src="https://github.com/user-attachments/assets/699f6e36-d866-4d1c-bab1-5b641bba2b6a">

 Overview

Hydration Haven** is an Android app designed to help users track their daily water intake and maintain proper hydration levels. The app allows users to record their morning and afternoon water intake, add hydration notes, and view detailed daily summaries.

 Features

- Splash Screen**: Displays the app name, user information, and options to navigate to the main screen or exit the app.
- Main Screen**: Allows users to input daily water intake data, clear the data, and navigate to the detailed view screen. It also calculates and displays the average water intake for the week.
- **Detailed View Screen**: Provides detailed information for each day's water intake, including morning and afternoon values and hydration notes.

 Screenshots

![Splash Screen](screenshots/splash_screen.png)
![Main Screen](screenshots/main_screen.png)
![Detailed View Screen](screenshots/detailed_view_screen.png)

## Data Storage

The app uses parallel arrays to store the data:
- days: List of dates.
- **morning**: List of morning water intake values.
- **afternoon**: List of afternoon water intake values.
- **hydration**: List of hydration notes.

Functionality

- **Adding Data**: Users can enter daily data and save it.
- **Clearing Data**: Users can clear all previously entered data.
- **Calculating Average**: The app calculates the average water intake for the week using loops.
- **Navigation**: Users can navigate between the main screen and detailed view screen.

## Code Implementation

Key code components:
-MainActivityScreen: Handles data entry, saving, and navigation.
- DetailedViewScreen: Displays detailed data for each day.
- Data Storage**: Uses parallel arrays for storing user data.

## How to Run

1. Clone the repository:
   git clone https://github.com/yourusername/hydration-haven.git

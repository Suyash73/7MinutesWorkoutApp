Name : SUYASH RAI <br>
Company : CODTECH IT SOLUTION <br>
ID: CT12DS400 <br>
Domain: Android Development <br>
Duration: June to July 2024 <br>
Mentor : Sravani Gouni <br>

# 7-Minute Workout App

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Usage](#usage)


## Introduction

The 7-Minute Workout App is designed to help users perform a quick and effective workout routine. The app guides users through a series of exercises with a 10-second rest period followed by a 30-second exercise period. Upon completing all exercises, the app stores the date and time of completion in a Room database, allowing users to track their activity over time. Additionally, the app includes a BMI calculator to help users monitor their fitness progress.

## Features

- Guided 7-minute workout routine with timed intervals
- 10 seconds of rest followed by 30 seconds of exercise
- Tracking of workout completion dates and times
- BMI calculator for fitness monitoring
- User-friendly interface with visual and audio cues
- RecyclerView for displaying lists of exercises and workout history
- Custom Progress Bar for visualizing workout progress
- Custom dialog boxes for user interactions and alerts

## Screenshots

![image](https://github.com/user-attachments/assets/c40f69b5-f4ae-4f29-ad6c-49c6552c733c) ![image](https://github.com/user-attachments/assets/d5d9de30-f94a-4691-ab1f-56d1e1682cf4)
![image](https://github.com/user-attachments/assets/25ac22fe-7023-4de2-b222-9fb4b1926321) ![image](https://github.com/user-attachments/assets/e6514ad7-adfc-409b-ba6e-3b21a1b437ed)
![image](https://github.com/user-attachments/assets/e6f48998-0d5e-47b9-a4fc-0061022a54e9)



## Architecture

The app follows the MVVM (Model-View-ViewModel) architecture pattern, ensuring a clear separation of concerns and making the codebase more maintainable.

## Technologies Used

- **Kotlin**: Programming language used for Android development
- **Jetpack Compose**: Modern toolkit for building native UI
- **ViewModel**: Manage UI-related data in a lifecycle-conscious way
- **LiveData**: Data objects that notify views when the underlying data changes
- **Room**: SQLite database with in-app data storage
- **RecyclerView**: For displaying lists of exercises and workout history
- **Progress Bar**: Custom progress bar for visual feedback
- **Custom Dialog Boxes**: For enhanced user interactions
- **Coroutines**: For asynchronous programming


## Usage

- Open the app and navigate to the workout section.
- Follow the guided workout routine with visual and audio cues.
- After completing the workout, the date and time of completion will be saved automatically.
- Use the BMI calculator to input your height and weight and monitor your fitness progress.
- Check the activity log to view your workout history, displayed using RecyclerView.
- The custom Progress Bar will provide visual feedback during exercises.
- Custom dialog boxes will enhance user interactions and provide alerts.


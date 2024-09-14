# Hotel Sheraton

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Screenshots](#screenshots)
4. [Technologies Used](#technologies-used)
5. [Setup](#setup)
6. [Usage](#usage)
7. [Folder Structure](#folder-structure)
8. [Testing](#testing)
9. [Contributing](#contributing)
10. [License](#license)

## Introduction
Hotel Sheraton is a comprehensive hotel booking and management app designed to provide a seamless experience for users looking to find and book hotels. This project encompasses features like hotel listings, room details, booking options, and user management.

## Features
- **User Authentication:** Login and signup functionalities with secure password storage.
- **Hotel Listings:** Browse and search for hotels based on location, price, and rating.
- **Booking System:** Book rooms with real-time availability checks.
- **User Profiles:** Manage user information and view booking history.
- **Admin Panel:** For hotel managers to update room details and view statistics.

## Screenshots
Here are some glimpses of the application in action:
***

 | `Light Mode`                      |
 | OnBoarding Page                   | Intro Page                     | Login Page                       | Signup Page                       |
 | -----------                       | -----------------              | -------------                    | -------------                     |
 | ![](/screenshots/onboarding.png)  | ![](/screenshots/intro.png)    | ![](/screenshots/login.png)      | ![](/screenshots/signup.png)      |

 | `Dark Mode`                       |
 | OnBoarding Page                   | Intro Page                     | Login Page                       | Signup Page                       |
 | -----------                       | -----------------              | -------------                    | -------------                     |
 | ![](/screenshots/onboarding.png)  | ![](/screenshots/into_drk.png) | ![](/screenshots/login_drk.png)  | ![](/screenshots/signup_drk.png)  |
 


## Technologies Used
- **Flutter** for cross-platform mobile app development.
- **Firebase** for authentication, database, and hosting.
- **Stripe API** for handling payments.
- **Google Maps API** for location-based services.

## Setup
To run this project locally, follow these steps:

```bash
git clone https://github.com/yourusername/hotel_sheraton.git
cd hotel_sheraton
flutter pub get
flutter run

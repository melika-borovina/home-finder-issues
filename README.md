# HomeFinder

## Introduction

HomeFinder is a web application that helps users find their dream homes. It provides a platform for real estate agents and homeowners to add their properties, and for potential buyers to browse and book tours.

## Features

HomeFinder includes the following features:

-   Login
-   Signup
-   Admin privileges
-   Add real estate
-   Update real estate
-   Delete real estate
-   Display real estate
-   Book a tour with an agent

## User Interface

HomeFinder includes the following pages:

-   Login page
-   Signup page
-   Home page/Display of real estate
-   Display of specific real estate
-   Book a tour page

## Functionality

### Login page

The login page functionality allows registered users to securely access their accounts by providing their login credentials. The page must include a form with fields for the user to enter their email address and password and a "Login" button to submit credentials. The system must return an appropriate error message if the credentials are invalid.

User flow:

1.  The user enters their registered email address and password.
2.  The user clicks the "Login" button to submit their credentials.
3.  The system verifies the user's credentials.
4.  If the credentials are valid, the system logs the user into their account and redirects them to the designated landing page.
5.  If the credentials are invalid, the system displays an error message and prompts the user to enter their credentials again.
6.  If the user does not have an account, then they press "Signup" button and are redirected to a signup form page.

### Signup page

The signup page functionality allows new users to create an account on the website or application by providing their personal information. The page must include a form with fields for the user to enter their personal and contact information. At the bottom, the form must include a "Sign up" button to submit the information. The system must securely store the password using a hashing algorithm.

User flow:

1.  The user navigates to the signup page by clicking the "Sign up" link or button on the login page.
2.  The user enters their personal information, including their full name, email address, and password.
3.  The user clicks the "Sign up" button to submit their information.
4.  The system creates a new user account and logs the user in automatically.
5.  If the user already has an account, then they press "Login" button and are redirected to a login form page.

### Home page

The home page displays a list of available real estate properties that users can browse. Users can filter properties based on location, price range, and other criteria.

### Display specific real estate

Users can view detailed information about a specific property, including its features, location, and photos.

### Book a tour

Users can book a tour of a property with a real estate agent by selecting a convenient date and time slot.

## Technical Requirements

HomeFinder is built using the following technologies:

Backend: Java, Spring, PostgreSQL 
Frontend: Angular 
The app Frontend/Backend is hosted on AWS Amplify cloud server.



## Out of scope

-   Nonresponsive UI design: Design is not responsive. It might not offer the best user-friendly experience on smaller resolutions.
-   Map of real estate: When we open specific real estate, we have a map that displays the location. For confidentiality reasons, it might only display the area of the house rather than specific address.

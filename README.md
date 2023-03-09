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

The home page of the real estate website should provide users with a comprehensive view of all real estate options available, including properties for sale and rent. Users should be able to easily navigate and filter through the options based on their preferences. The home page should display all available properties based on the user's search criteria. Each property should be displayed with a thumbnail image and when clicking the real estate the user can get further information on the listing.

### Display specific real estate

Users can view detailed information about a specific property, including its features, location, and photos.

### Book a tour

Users should be able to book a tour with an agent for a specific property by clicking a "Book a Tour" button on the real estate record. The website should allow users to choose a date and time for the tour and provide their contact information to the agent. The status of the tour is pending until the agent approves the date and time.

### Admin Privileges

Admin privileges refer to the elevated level of access granted to a user account, which enables them to perform certain tasks on a website or application that regular users cannot. In the context of a real estate website, granting admin privileges would allow a user to create, edit, and delete real estate listings from the page.

With admin privileges, the user would have access to an administrative panel that would allow them to manage the content of the website. This panel would include options for creating new real estate listings, editing existing ones, and deleting listings that are no longer relevant. The admin user would be able to add photos, descriptions, and other details to the listings, making them more attractive to potential buyers or renters.

The ability to create, edit, and delete real estate listings is crucial for a real estate website as it allows the website to stay up-to-date with the latest properties available on the market. With admin privileges, the user can ensure that the website is always presenting accurate and timely information to its users.

Overall, granting admin privileges to a user on a real estate website provides them with the necessary tools to manage the content of the website and keep it updated with the latest property listings. This functionality enhances the user experience and ensures that the website remains a valuable resource for those looking to buy or rent real estate.



## Technical Requirements

HomeFinder is built using the following technologies:

Backend: Java, Spring, PostgreSQL 
Frontend: Angular 
The app Frontend/Backend is hosted on AWS Amplify cloud server.



## Out of scope

-   Nonresponsive UI design: Design is not responsive. It might not offer the best user-friendly experience on smaller resolutions.
-   Map of real estate: When we open specific real estate, we have a map that displays the location. For confidentiality reasons, it might only display the area of the house rather than specific address.
-   Booking a tour with an agent will be limited to the agent sending an email to the interested user. Currently out of the scope of our project to have a notifications page, where the user would be notified that their request for a tour with an agent has been approved/denied.

# HomeFinder
1. Introduction
HomeFinder is an application designed to serve as a common platform for real estate agents and potential buyers. It allows agents to post real estate listings and enables users to discover properties, leave reviews, and schedule tours. Furthermore, it features an articles section, where users can keep abreast of the latest developments in the real estate industry. Users can also connect with customer support via a dedicated form.

## Features
HomeFinder includes the following features:

For Users:
- Login/Signup
- Browse real estate listings
- Review real estate properties
- Book tours
- Read articles
- Send messages through the customer support form

For Agents/Admins:
- Post real estate listings
- Create, update, and delete real estate features (like pool, elevator, garage, etc.)
- Create, update, and delete articles
- View messages from the customer support form
- View tour booking requests
- Access the list of users and promote them to admin roles

## User Interface
HomeFinder includes the following pages:

- Login/Signup page
- Feed of all real estate listings
- Real estate showcase page (includes Google Map)
- Articles feed
- Individual article page
- Customer support page
- About Us page

## Functionality
### Login/Signup page
The login/signup page provides fields for users to input their credentials. New users can sign up while existing users can log in to their accounts.

### Feed of all real estate listings
This page presents a comprehensive view of all available real estate listings. Users can browse, review, and book tours from this page.

### Real estate showcase page
Each property has its own showcase page, which contains detailed information, images, and a Google Map indicating its location. Users can also review the property and book tours on this page.

### Articles feed
The articles feed aggregates all available articles related to real estate. Users can access these for the latest industry news and insights.

### Individual article page
This page presents the full content of an individual article, including text, images, and any other relevant media.

### Customer support page
This page hosts a form that users can fill out to get in touch with the HomeFinder customer support team.

### About Us page
The About Us page contains information about the company, the team, and the mission and vision of HomeFinder.

## Technical Requirements
HomeFinder is built using the following technologies:

- Backend: Java, Spring, PostgreSQL
- Frontend: Angular
The app's Frontend/Backend is hosted on a Netlify/Heroku cloud server respectively.


## Out of scope

-   Nonresponsive UI design: Design is not responsive. It might not offer the best user-friendly experience on smaller resolutions.
-   Booking a tour with an agent will be limited to the agent sending an email to the interested user. Currently out of the scope of our project to have a notifications page, where the user would be notified that their request for a tour with an agent has been approved/denied.
